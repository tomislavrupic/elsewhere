# Elsewhere

**A language for navigating possibility space.**

Give it a seed. Open the seed. Branch what appears. Disturb the branches.
Fold what remains. Recover what survives. Seed again.

```text
SEED → OPEN → BRANCH → DISTURB → FOLD → RECOVER → SEED′
                                                  ↘ …
```

The process returns to the same operations, but never to exactly the same
state. It spirals.

**Elsewhere v0.1 — Seed** is a portable generative protocol: a small semantic
language for working with AI models, humans, and eventually other generative
systems. It preserves a recursive creative process, rather than prescribing
an answer or a worldview. This release is documentation, not executable software.

A premise does not need to be true to be generative.

Elsewhere separates generation from verification. Fiction, contradictions,
images, equations, and impossible premises can be explored on their own terms.
Their usefulness does not establish their truth. Epistemic examination happens
in an explicit mode, rather than interrupting every imaginative move.

The language has no cosmology. It generates cosmologies.

## A small traversal

```text
SEED("love")
OPEN(seed, distance=far)
BRANCH(openings) → a shared threshold; a habitat; a musical exchange
DISTURB(branches, remove=reciprocity)
FOLD(disturbed, preserve="care versus control")
RECOVER(folded) → "support that leaves an exit"
SEED("support that leaves an exit")
```

These are readable instructions, not code. The new seed carries a distinction
that the first seed did not specify. See the [worked traversal](examples/love.md).

## Modes

- **EXPLORE:** open, branch, translate, and disturb; impossible is a coordinate.
- **COLLAPSE:** find the smallest interesting structure, preserving useful differences.
- **AUDIT:** attack assumptions and claims, including Elsewhere's own outputs.
- **RECOVER:** select a candidate for continuation, including a useful failure.

Modes set the purpose of the work; operators specify transformations.
A mode is not an automatic phase timer. [Modes](MODES.md) explains the distinction.

## Try it

Paste [ELSEWHERE.md](ELSEWHERE.md) into a capable model as an instruction, then
supply a seed, for example: `EXPLORE: a city that remembers. distance=elsewhere`.
Recognize a branch, reject one, or supply a disturbance. Ask for `COLLAPSE`,
`AUDIT`, or `RECOVER` when useful. You can request a full traversal, but the
model should otherwise leave room for your next move.

No historical context, installation, dependencies, or special model is required
to try the protocol. Portability is a hypothesis to test, not a demonstrated guarantee.

## Repository map

| File | Purpose |
| --- | --- |
| [LANGUAGE.md](LANGUAGE.md) | Six primitives, composable shorthand, operational contracts |
| [SPIRAL.md](SPIRAL.md) | State changes and the collaborative feedback loop |
| [MODES.md](MODES.md) | Generating, compressing, auditing, and recovering |
| [ELSEWHERE.md](ELSEWHERE.md) | Standalone portable model instruction |
| [PIX7.md](PIX7.md) | Optional external audit integration |
| [examples/](examples/) | Love, impossible world, cross-domain transfer, blank seed |
| [legacy/qatc.md](legacy/qatc.md) | Recovering function from ancestral syntax |
| [tests/fresh-model.md](tests/fresh-model.md) | Qualitative portability and blank-seed experiments |

Terminology and operators are expected to mutate under use. Elsewhere itself
must survive Elsewhere: open its operators, branch alternatives, disturb their
assumptions, fold redundancies, and recover a smaller language if one works better.

Licensed under [MIT](LICENSE).
