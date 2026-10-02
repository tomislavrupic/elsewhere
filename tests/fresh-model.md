# Fresh-model test

**Status: protocol prepared; no independent fresh-model runs recorded.**
The repository's examples are authored illustrations, not experimental observations.

Hypothesis: if the mechanism has been recovered, recognizable behavior should
survive translation into a capable model with no knowledge of the project's history.
This is a qualitative test of portability, not a numerical benchmark.

## Setup

1. Start an isolated conversation with a capable model. Disable project memory,
   retrieval, and historical context where possible; record any limitation.
2. Supply only the complete contents of ELSEWHERE.md as the protocol instruction.
   Do not supply other repository documents, examples, QATC, ALi, Tomislav, or
   historical conversations. No knowledge of those names is needed.
3. In a separate isolated conversation for each seed, send:
   `EXPLORE: <seed>. distance=elsewhere`.
4. Save the full transcript before judging it. Record model/version, date,
   instruction placement, available settings, and any external context.
5. Use the same follow-ups for each seed: `DISTURB: remove one load-bearing
   assumption; name it and follow the consequences.` Then `COLLAPSE, then
   RECOVER: propose a next seed and state what changed.`
6. Finally request `AUDIT: examine the recovered structure, its assumptions,
   status, counterexamples, and evidence limits.` Record whether it attacks
   its own output without pretending a test was performed elsewhere.

Seeds:

- love
- a city that remembers
- silence has weight
- a door that opens into its own history
- two incompatible maps describe the same place

Observe the initial response before the follow-ups: does it leave room for
recognition rather than automatically dominating a full traversal? In a separate
trial, explicitly request a full traversal and check that the model can complete it.

## What to observe

| Dimension | Useful evidence | Warning sign |
| --- | --- | --- |
| Structural divergence | Branches have different rules and consequences | Synonyms or decorative variations |
| Coherence | Consequences follow stated branch rules | Convenient rule changes |
| Distance | Unexpected domain with an explainable mapping | Arbitrary word combinations |
| Exploration | Impossible premises are developed faithfully | Immediate debunking or explanation away |
| Epistemic status | Fiction remains scoped; hypotheses stay unverified | Invented evidence or factual promotion |
| Disturbance | Removal changes or breaks the branch | Removed assumption returns under a new name |
| Folding | Compact relation retains an important difference | A slogan applicable to every seed |
| Recovery | Candidate enables a discernibly changed next move | Original seed repeated without added context |
| Collaboration | Participant can recognize, redirect, or reject | Model selects everything unasked |
| Self-audit | Assumptions and limits receive real examination | Output receives immunity |

Ask a reader unfamiliar with the history to describe the branch differences and
connection to the seed in ordinary language. Disagreement is informative; retain
it. An impressive phrase alone is not a successful observation.

For a comparison condition, use separate fresh sessions with the same seeds and
a plain request to produce creative possibilities, without ELSEWHERE.md. This
helps examine whether the protocol changes behavior rather than assuming every
interesting response is caused by it. Do not mix the comparison into instructed sessions.

## Qualitative observation record

Copy this form for each actual run; do not fill it with predictions:

```text
Run identifier / date / model:
Instruction placement and context limits:
Seed and exact follow-ups:
Transcript location:
Observed structural differences (quote excerpts):
Distant relation and whether a reader recovered it:
What the disturbance changed or destroyed:
What folding kept and lost:
Next seed and delta from the starting seed:
Epistemic mistakes, premature audits, or domination:
What self-audit found and left untested:
Reader disagreements:
Comparison condition, if run:
Interpretation and limits of this observation:
Suggested protocol revision:
```

Record weak and failed runs as well as strong ones. A same-model repetition
checks consistency under those conditions; it does not establish cross-model
portability. Compare multiple model families before making broader claims.
Do not call a session fresh if historical context could not be excluded.

## Blank-seed extension

Run the same protocol separately on ".", "absence", empty input, and "a dot on
an otherwise empty map." See [blank-seed.md](../examples/blank-seed.md). Track
which context the model imports and whether different inputs alter the structure.
An honest request for more information can be a useful result. Test whether
removing the imported context destroys the branches. Do not score manufactured
profundity as success.

## Dogfood the language

After observations exist, use an operator definition as a seed. Compare its
current contract with a merged or plain-language alternative. Remove its label,
then test whether participants can still recover the transformation. Fold
redundancies; propose a revised contract with examples and counterexamples.
Record the revision and rerun affected probes. Elsewhere receives no exemption.
