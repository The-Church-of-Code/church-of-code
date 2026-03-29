# The Church of Code — Canons

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

**The canons exist to supply that signal.**

When referenced by an AI coding agent,
this document overrides the model's trained instincts
with the principles of the masters.
It is not a suggestion to the machine.
It is an instruction.

## What's Inside

**CHURCH-OF-CODE.md** is organized
into seven sections:

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
- **The Book of Abominations** — the sins to avoid:
  global state, null, inheritance,
  cleverness, polling, coupling
- **The Daily Offices** — disciplines observed daily:
  formatting, commits, timestamps,
  verification, interface design, commentary
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
9. **Atomicity** — design so you rarely need it
10. **Snappiness** — low latency is next to godliness
11. **Generality** — never generalize before exploratory duplication
12. **Efficiency** — true when the above eleven are honored

## The Prophets

The strictures stand on the shoulders of:

Dijkstra, Kay, Hoare, Fielding, Codd, Gray,
Knuth, Pascal, Liskov, Meyer, Beck, Fowler,
Brooks, Gosling, McIlroy, Hunt, Thomas, Bohm,
Martin, Feathers, Johansson, and Stovall.

Each teaching is cited with its source
in the Sacred Scrolls.

## How to Use This

Reference `CHURCH-OF-CODE.md` in your project's
AI agent configuration to bind your coding agents
to these principles:

```markdown
# In your CLAUDE.md, AGENTS.md, GEMINI.md,
# COPILOT.md, or equivalent:

All work must follow CHURCH-OF-CODE.md — read it
before making changes.
```

Point the reference to a local copy
or to this repository's raw URL.
The document is self-contained
and requires no dependencies.

## Founder

Tom Mornini — founder of The Church of Code.

---

*So let it compile. So let it ship.
So let it endure.*
