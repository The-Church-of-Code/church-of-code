# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Repository Is

This is a documentation-only repository — there is no source code, no build system, no dependencies. The product is a software engineering manifesto maintained as Markdown scripture in three synchronized context-size variants.

## File Roles

| File | Role |
|------|------|
| CHURCH-OF-CODE.md | Canonical scripture (full). All edits start here. |
| CHURCH-OF-CODE-medium-context.md | ~1/3 byte reduction. Derived from full. |
| CHURCH-OF-CODE-small-context.md | ~2/3 byte reduction. Derived from medium. |
| BUILD.md | Complete rebuild process and verification checklist. |
| README.md | Project overview and AI agent integration instructions. |
| WHY-THIS-WORKS.md | Analysis of why religious framing improves AI code generation. |
| LICENSE | MIT. |

## Rebuilding the Variants

When the full scripture changes, both variants must be regenerated. Read BUILD.md for the complete process. Key points:

**Build order**: Medium from full first, then small from medium.

**Section processing order within each file**:
1. Book of Abominations (largest cut)
2. Sacred Scrolls
3. Twelve Commandments
4. Articles of Faith (absorb unique abomination content for small)
5. Daily Offices
6. Preamble and Benediction (last — ensures proportion)
7. Byte-count check

**Reduction principle**: Cut metaphorical elaboration, keep declarative doctrinal statements. Reductions trim elaboration — never remove topics. Every commandment, article, sin, and office must be present in all three files.

**Small variant structural transformation**: The 3 sins with unique doctrine (Premature Optimization, Null, Default Values) migrate their content into relevant Articles, allowing Abominations to collapse to header-only form.

**Verification** (after each variant):
- `wc -c` — byte count within ±5% of target
- `grep -c '^### [IVX]'` — exactly 12 commandments
- `grep -c '^\*\*We '` — exactly 16 articles
- All 18 sin names present
- `grep -c '^### The Office'` — exactly 6 offices
- `grep -c '"But '` — exactly 18 italic objections
- Tonal anchors preserved: "scripture", "they are sins", "faithful", "let it crash", "own denomination", "So let it"

## Version and Release

Each file carries `*v{N} — {size}*` immediately below the title. The git tag and internal version lines must agree.

**Release process**:
1. Update CHURCH-OF-CODE.md
2. Rebuild both variants per BUILD.md
3. Update `*v{N} — {size}*` in all three files
4. Commit all three files together
5. `git tag v{N}`

## Document Structure

The scripture follows a **positive-negative-practical** pattern: Commandments declare ranked virtues → Articles state operational beliefs → Abominations restate most as sins (15 of 18 are purely redundant inversions) → Daily Offices operationalize the beliefs. This asymmetry — the Abominations' redundancy — is the primary lever for both reductions.
