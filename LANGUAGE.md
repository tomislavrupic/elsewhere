# Language

**Elsewhere v0.1 — Seed** specifies semantics, not a parser. Uppercase verbs
name operations. Parentheses, arrows, named parameters, and indented prose are
interchangeable readable notation when their meaning is explicit.

## Objects and composition

An object may be text, an image, a sound, an equation, a dataset, a rule, a
relationship, or another artifact. Describe inaccessible media rather than
pretending to have inspected them. A seed is the smallest useful object for
this traversal, not necessarily the shortest string.

Keep lightweight context with objects when needed: origin, provisional status,
constraints, transformations, and unresolved differences. This is a semantic
record, not a required data schema. An empirical observation used as a seed
retains its source; imagined additions do not inherit its evidential status.

`OPEN` returns openings, not finished branches. `BRANCH` realizes those
openings. `DISTURB` transforms an object or maps a stated perturbation across a
collection. `FOLD` accepts one object or a collection. `RECOVER` produces a
candidate and its reason for continuation. `SEED` installs an object as the
starting point. These output meanings stay fixed across modes.

```text
s = SEED("love")
o = OPEN(s, distance=far)
b = BRANCH(o, count=3)
d = DISTURB(b, remove=reciprocity)
f = FOLD(d, preserve="care versus control")
r = RECOVER(f, criterion="opens a useful next question")
s′ = SEED(r.candidate)
```

Names such as `r.candidate` are explanatory notation, not an API.

```text
RECOVER(FOLD(DISTURB(OPEN(SEED("love")), remove=reciprocity)))
```

This shorter expression is valid: openings can themselves be disturbed and
folded. It omits explicit realization through `BRANCH`; it does not secretly
invoke that operator. Specify the disturbance instead of relying on a
conveniently shifting interpretation.

## Six primitives

### SEED

- **Purpose:** establish the smallest useful starting object.
- **Inputs:** an object; optional context and constraints.
- **Transformation:** designate the object and record what is given versus added.
- **Output:** a seed with a stated starting boundary.
- **Failure modes:** smuggling in an answer; assuming an interpretation is supplied;
  erasing provenance; claiming an almost empty mark is inherently meaningful.
- **Example:** `SEED("silence has weight", status=fictional-premise)`.
- **Misuse:** `SEED("silence has weight")` followed by treating physical mass as measured.

### OPEN

- **Purpose:** increase interpretation space around a seed or other object.
- **Inputs:** object; `distance=near|medium|far|elsewhere`; optional constraints.
- **Transformation:** propose distinct interpretive routes and trace each back to
  a relation in the input. Keep unresolved ambiguity available.
- **Output:** openings with a recoverable connection, not a winner.
- **Failure modes:** synonyms only; unconnected randomness; premature selection;
  attributing all added structure to the original seed.
- **Example:** open "silence has weight" into a queue whose unspoken requests
  accumulate, or a score where withheld notes determine duration.
- **Misuse:** append "blue comet velvet" with no relation to silence or weight.

### BRANCH

- **Purpose:** instantiate meaningfully different realizations of openings.
- **Inputs:** openings; optional count, medium, and constraints.
- **Transformation:** develop each selected route enough to expose its rules,
  relationships, and consequences. Show how branches differ structurally.
- **Output:** distinguishable realizations, retaining their origins.
- **Failure modes:** cosmetic variation; many undeveloped titles; quietly merging
  incompatible premises; declaring one realization necessary.
- **Example:** silence as stored obligation produces a civic ledger; silence as
  temporal spacing produces a musical score. Their mechanisms differ.
- **Misuse:** three identical ledgers with different cover colors.

### DISTURB

- **Purpose:** expose consequences and dependencies by perturbing structure.
- **Inputs:** object(s); a specified assumption, relation, component, or constraint
  to alter; what remains fixed when relevant.
- **Transformation:** apply the perturbation, then follow its consequences without
  quietly restoring the removed condition.
- **Output:** changed structures, failures, and traces of what changed.
- **Failure modes:** merely adding decoration; arbitrary destruction; rescuing a
  broken branch by reinstating the assumption; confusing survival with truth.
- **Example:** remove repayment from the silence ledger: obligations can no longer
  be discharged, forcing a choice between expiration and permanent accumulation.
- **Misuse:** "remove repayment" while renaming repayment "closure" and keeping it.

### FOLD

- **Purpose:** compress complexity without erasing load-bearing differences.
- **Inputs:** object(s); optional distinctions to preserve.
- **Transformation:** compare relations, remove decoration, and express recurring
  structures, exceptions, and useful differences with fewer commitments.
- **Output:** a compact representation with retained distinctions and known losses.
- **Failure modes:** vague universal slogan; majority vote; choosing a winner;
  dropping the very difference that made a branch useful.
- **Example:** ledger and score both make absence consequential; one accumulates
  obligation, the other organizes duration. Preserve that difference.
- **Misuse:** "everything is connected" as a fold of any arbitrary collection.

### RECOVER

- **Purpose:** extract a strong candidate for continued exploration.
- **Inputs:** folded, disturbed, or audited material; optional continuation criterion
  and participant selections.
- **Transformation:** identify what remains useful, name its limits and unresolved
  question, and propose a candidate without certifying empirical truth.
- **Output:** candidate next seed plus a short continuation rationale; alternatives
  may remain. Insufficient material can yield a smaller question or failed assumption.
- **Failure modes:** restoring the original seed unchanged; declaring proof;
  ignoring participant recognition; manufacturing a survivor at any cost.
- **Example:** recover "when should an unspoken obligation expire?" from the ledger's failure.
- **Misuse:** recover "silence literally has mass" because the story was compelling.

## Generative distance

| Distance | Search intent | Example from "a door" |
| --- | --- | --- |
| near | Neighboring ideas | Threshold, privacy, entry |
| medium | Cross-disciplinary associations | Admission rules in institutions |
| far | Non-obvious structural translations | A melody whose earlier motif grants entry to a later phrase |
| elsewhere | Outside the expected neighborhood, with recoverable relevance | A map that redraws its boundary whenever someone crosses it |

These are qualitative requests, not measured categories or a novelty ranking.
Name the retained relation: in the map, crossing changes access and boundary.
If that relation cannot be recovered, distance has become drift. A far opening
may fail; return to a more informative connection rather than invent profundity.

## Derived shorthand, not extra primitives

These conveniences must expand into stated transformations. They have no
independent authority. All retain the parent operator's failure modes.

| Shorthand | Purpose and inputs | Transformation and output | Example | Misuse / failure |
| --- | --- | --- | --- | --- |
| `TRANSFER(x, domain, preserve)` | Carry a specified relation into another domain | `DISTURB(x, change-domain=domain, preserve=relation)` returns a translated realization and mapping | Transfer reciprocal care to architecture as separately controlled entrances and shared shelter | A heart-shaped building with no relational mapping |
| `INVERT(x, relation)` | Reverse a directed relation | `DISTURB(x, reverse=relation)` returns a structure with consequences of reversal | Invert "inhabitants maintain city" into "city maintains inhabitants" | Reverse unspecified "meaning" whenever convenient |
| `SCALE(x, unit, from, to)` | Alter a specified scale | `DISTURB(x, change-scale=..., preserve=...)` returns changed structure and limits | Scale a room's access rule to a city district | Assume behavior scales unchanged without examining consequences |
| `REMOVE(x, component)` | Test dependence on a component | `DISTURB(x, remove=component)` returns changed structure or failure | Remove the ledger's repayment operation | Reintroduce it under another name |
| `TRANSLATE(x, medium, preserve)` | Change representation while retaining a named relation | `DISTURB(x, change-medium=medium, preserve=relation)` returns artifact or artifact description plus mapping | Translate turn-taking into alternating musical phrases | Claim the score proves a social mechanism |

`TRANSFER` changes domain; `TRANSLATE` changes representation. A move can do
both, but must state both. Neither guarantees equivalence or survival.

Other candidates are deferred or expressed through existing contracts:

- `PRESERVE` and `CONSTRAIN` are parameters: name exactly what remains fixed.
- `RELATE` is an explicit relation within a seed or branch, not a transformation by itself.
- `AMPLIFY` requires a specified quantity or relation and becomes `DISTURB(increase=...)`.
- `MUTATE` adds nothing beyond a specified `DISTURB`.
- `CROSS` becomes `BRANCH` from combined openings with the inherited constraints named.

No privileged vocabulary. A shorthand that cannot expand operationally should
be dropped. Changing an operator's meaning requires a documented revision,
not an explanation invented to save a failed output.
