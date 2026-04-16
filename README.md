# The Church of Code

> *This church is its own denomination.*

This repository contains
[CHURCH-OF-CODE.md](CHURCH-OF-CODE.md) —
a scripture of software engineering principles,
authored by Tom Mornini,
drawn from the foundational teachings
of the field's most consequential thinkers.

These are not guidelines. They are not best practices.
They are strictures — binding, inviolate,
and intended to be enforced.

## Why This Exists

AI coding agents are among the most impressive
tools ever placed in a developer's hands.
They are also among the most subtly dangerous.

Every large language model that writes code
learned to write code
from the existing corpus of software —
code written, at every point
in the history of the craft,
predominantly by amateurs
with fewer than five years of experience.
The field has grown exponentially
for seven decades;
at any given moment,
the majority of practitioners
were still learning the basics.

The models internalized those habits.
They absorbed the statistical average —
the nullable columns, the global shortcuts,
the inheritance hierarchies,
the clever tricks, the premature abstractions.
They did not absorb the hard-won wisdom
of Dijkstra, Kay, Hoare, Liskov, Codd,
Fielding, Meyer, Beck, or Martin —
because that wisdom was never
the dominant signal in the corpus.

**This church exists to supply that signal.**

When referenced by an AI coding agent,
this document overrides the model's trained instincts
with the principles of the masters.
It is not a suggestion to the machine.
It is an instruction.

For a deeper exploration of why the religious framing
itself may improve AI code generation,
see [WHY-THIS-WORKS.md](WHY-THIS-WORKS.md).

## What's Inside

**CHURCH-OF-CODE.md** is organized
into eight sections:

- **The Preamble** — declares the document's authority
  and its stance: violations are not bugs, they are sins
- **The Sacred Scrolls** — the foundational texts
  from which the strictures descend,
  with prophetic attributions
- **The Twelve Commandments** — the core hierarchy
  of values, ordered from most to least important
- **The Articles of Faith** — what the faithful practice:
  SOLID, tell-don't-ask, composition,
  messaging, adapters, and more
- **The Book of Abominations** — eighteen sins to avoid,
  ordered by causal chain from the Original Sin
  (premature optimization) through its consequences
- **The Daily Offices** — disciplines observed daily:
  formatting, commits, timestamps,
  verification, interface design, commentary
- **The Unwritten Scrolls** — principles acknowledged
  but not yet codified
- **The Benediction** — the closing charge

## The Twelve Commandments

In order of importance, from most to least:

1. **Reliability** — the bedrock upon which all else rests
2. **Security** — a compromised system is a fallen system
3. **Uniformity** — call a thing a thing, in all things
4. **Logic** — less wrong, never fallacious
5. **Clarity** — dense, high-information communication
6. **Immutability** — eliminate "why did THAT happen?"
7. **Idempotency** — PUT, GET, DELETE, not INSERT, UPDATE, DELETE
8. **Simplicity** — the fruit of great effort, not its absence
9. **Generality** — never generalize before exploratory duplication
10. **Atomicity** — design so you rarely need it
11. **Efficiency** — true when the above eleven are honored
12. **Performance** — every wasted millisecond is a small death

## The Prophets

The strictures stand on the shoulders of
the field's foundational thinkers —
Dijkstra, Codd, Hoare, Kay, Liskov, Brooks,
and many more. The complete roster, with each
teaching cited to its source, lives in the
**Sacred Scrolls** section of
[CHURCH-OF-CODE.md](CHURCH-OF-CODE.md).

## Choosing a Variant

Three variants of the scripture are maintained
in sync. Pick the largest that fits your
context budget:

| Variant | File | Size | When to use |
|---------|------|------|-------------|
| Full | [CHURCH-OF-CODE.md](CHURCH-OF-CODE.md) | ~40 KB (~10k tokens) | Default. Full literary voice and prophetic witnesses. |
| Medium | [CHURCH-OF-CODE-medium-context.md](CHURCH-OF-CODE-medium-context.md) | ~28 KB (~7k tokens) | Tighter context budgets. Trimmed elaboration, same breadth. |
| Small | [CHURCH-OF-CODE-small-context.md](CHURCH-OF-CODE-small-context.md) | ~13 KB (~3k tokens) | Strict context budgets. Every doctrine still present. |

Every commandment, article, sin, and office
is present in all three.

## How to Use This

Copy the variant you chose into your project
root, or point to this repository's raw URL.
Then reference it in your agent's configuration
file with a single line:

> All work must follow CHURCH-OF-CODE.md — read it before making changes.

Common agent configuration files:

| Agent | Configuration file |
|-------|--------------------|
| Claude Code | `CLAUDE.md` |
| Gemini | `GEMINI.md` |
| GitHub Copilot | `.github/copilot-instructions.md` |
| Cursor | `.cursorrules` |
| Windsurf | `.windsurfrules` |
| Any other | whatever file your agent reads at startup |

The document is self-contained
and requires no dependencies.

## Contributing

Amendments to scripture are proposed
through GitHub pull requests.
See [CONTRIBUTING.md](CONTRIBUTING.md)
for the amendment process and
[BUILD.md](BUILD.md) for how to rebuild
the variants in sync.

## License

[MIT License](LICENSE)

## Founder

Tom Mornini — founder of The Church of Code.

---

*So let it compile. So let it deploy.
So let it run smoothly. So you can rest.*
