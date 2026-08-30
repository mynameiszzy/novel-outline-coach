# Snowflake outline workflow

Use the Snowflake Method as a visible, traceable expansion process. Continue from the most developed reliable layer. Do not make the author repeat completed work, and do not force optional late layers when the requested outline is already usable.

## Operating invariants

Snowflake is more than a sequence of increasingly long summaries:

1. **Progressive** — each layer expands an approved or clearly labeled candidate parent.
2. **Traceable** — every child keeps a stable parent ID.
3. **Bidirectional** — a discovery below may require an explicit revision above.
4. **Visible** — the response states the current layer, artifact, status, and next expansion.

Use stable IDs:

- `SF-L1` — one-sentence story promise;
- `SF-L2-S1` through `SF-L2-S5` — five-sentence causal skeleton;
- `SF-L3-C1`, `SF-L3-C2` — character snowflakes;
- `SF-L4-P1` through `SF-L4-P5` — expanded synopsis paragraphs;
- later beats and scenes retain their nearest Snowflake parent, for example `SC-014 ← SF-L4-P3`.

When information is incomplete, fill non-blocking gaps with `candidate` assumptions. Ask only blocking decisions. Preserve detail at its proper layer and do not solve scene mechanics while the upper skeleton is unstable.

## Fast Snowflake snapshot

Fast pace compresses interaction, not the layer chain. For a vague premise, one response may contain:

```text
Current reliable layer and status
SF-L1: one-sentence promise
SF-L2-S1..S5: five-sentence causal skeleton
Causal links: S1 therefore S2 ...
SF-L3: one or two provisional character snowflakes when useful
Drift check
Next expansion
```

Do not substitute an unlabeled three-act outline for this snapshot. Apply three-act and multi-line analysis only after `SF-L2` exists.

## SF-L0: project frame

Capture only information that changes outline decisions:

- genre and intended reading experience;
- approximate length or format;
- existing premise, characters, ending, and non-negotiable elements;
- viewpoint, audience, or content boundaries when already known;
- areas the author wants help deciding.

Exit when there is enough context to propose `SF-L1`. Unknown fields may remain unknown.

## SF-L1: one-sentence story promise

Express the focal character or group, destabilizing situation, central pursuit, primary opposition, and distinctive stakes in one economical sentence. Avoid names and lore density unless essential.

Test:

- Does the focal character or group make consequential choices?
- Does the sentence contain a repeatable conflict engine rather than only a setting?
- Does it imply what can be won or lost?
- Does it distinguish this story from a generic genre premise?

Propose a candidate sentence immediately when enough material exists. Record its status as `candidate` or `confirmed`.

## SF-L2: five-sentence causal skeleton

Expand `SF-L1` into five functional sentences by default:

- `SF-L2-S1 — Setup and pressure`: establish the focal group, unstable normal, and immediate pressure.
- `SF-L2-S2 — First disaster and commitment`: remove the easy path and force the story's central pursuit.
- `SF-L2-S3 — Second disaster and strategic change`: defeat the first strategy or change the goal, knowledge, or scale.
- `SF-L2-S4 — Third disaster and final necessity`: create the loss, revelation, or irreversible choice that makes the climax necessary.
- `SF-L2-S5 — Climax and ending`: state the decisive action, external result, and new equilibrium.

The five-sentence shape is a working constraint, not a reason to distort an unusual story. Vary it only for a clear structural reason while preserving setup, escalating irreversible turns, climax, and ending.

After drafting, write the causal chain using `because`, `therefore`, or `but`. Flag any link that functions only as “and then.” Every disaster must change available options and arise from prior choices, competent opposition, or established world pressure.

This is the first whole-story checkpoint. Do not advance merely because five sentences exist; advance when they form a causal path that still fulfills `SF-L1`.

## SF-L3: character snowflakes

For every major viewpoint or decision-maker, create a concise character layer:

```text
ID and status
Parent sentences affected
Personal one-sentence story
External goal
Internal need or misbelief
Motivation and stakes
Capability and constraint
Central conflict
Decisive change, refusal, or tragic realization
Contribution to SF-L2-S5
```

Each character must own or materially alter at least one `SF-L2` turn. If a supposedly major character can be removed without changing the five-sentence skeleton, merge, demote, or redesign that character.

For ensemble stories, show how the personal one-sentence stories disagree about the same central problem. Do not produce isolated biographies before establishing their structural ownership.

## SF-L4: expand sentences into paragraphs

Expand each `SF-L2-Sn` into its own paragraph `SF-L4-Pn`. Each paragraph should contain:

- entry state inherited from the parent sentence;
- attempted strategy;
- opponent or system response;
- consequential character choice;
- cost, information, or relationship change;
- exit state that causes the next paragraph.

Do not add a new major antagonist, central pursuit, disaster, or ending here without flagging the required `SF-L1` or `SF-L2` revision.

At this checkpoint, three-act and narrative-line tools may diagnose rhythm, line intersections, and climax load. They remain lenses over the Snowflake parents.

## SF-L5: viewpoint versions

For multi-POV or ensemble stories, summarize the `SF-L4` plot from each major viewpoint. Track what each character wants, believes, knows, hides, and misunderstands at every parent paragraph. Secondary viewpoints may need only a concise arc.

Keep true chronology distinct from reader reveal order when needed. Skip this layer for simple single-viewpoint projects.

## SF-L6: detailed synopsis and beats

Recursively expand each `SF-L4-Pn` into causal beats. Retain the parent ID for every beat. Track decisions, counter-actions, consequences, new information, and irreversible state changes.

The middle must escalate or transform the strategy rather than accumulate episodes. If new beats reveal that a parent paragraph is inaccurate, revise the parent before continuing.

## SF-L7: character and world constraints

Add only details that affect choices or plot feasibility: relationships, resources, obligations, secrets, knowledge, power limits, institutions, costs, and exceptions.

Every material rule should identify the Snowflake items it enables or constrains. A worldbuilding detail that changes no parent, choice, or consequence remains deferred texture.

## SF-L8: chapter or scene inventory

Create stable IDs and record for each unit:

- Snowflake parent ID;
- viewpoint and time;
- immediate goal and opposition;
- active narrative lines;
- new information;
- turn or decision;
- consequence and changed story state;
- setup or payoff links.

Every planned unit must change at least one meaningful state. Merge, remove, or redesign units that only repeat information or mood without intentional pacing value.

## SF-L9: optional scene briefs

Expand only complex scenes into entry condition, tactics, reversals, emotional movement, exit condition, and next-scene pressure. This remains outline work, not prose drafting.

## Layer-boundary checks

At every completed layer, report:

- **Causal integrity** — which parent-to-child or sentence-to-sentence link is weakest?
- **Promise drift** — does the expansion still deliver `SF-L1`?
- **Agency drift** — do major turns still arise from character choice and opposition?
- **Ending drift** — does the current ending answer the story promise and character arguments?
- **Scale drift** — has the story silently changed format, scope, or required length?
- **Propagation** — which lower artifacts become stale if an upper item changes?

Classify issues as `blocking`, `candidate repair`, or `accepted-risk`. Surface only the 3–5 highest-impact issues.

## Upstream revision rule

When a lower layer produces a discovery:

1. identify its current parent;
2. decide whether it elaborates, contradicts, or replaces the parent;
3. if it contradicts or replaces, propose the smallest upper-layer revision;
4. list affected sibling and lower-layer IDs;
5. update only after author approval when the change affects confirmed canon;
6. mark descendants `stale` until reconciled.

Do not hide story drift by simply adding more detail.

## Drafting readiness review

An outline is ready for drafting when:

- `SF-L1` survives every expansion;
- the `SF-L2` chain is causal and ends decisively;
- major characters own necessary turns;
- lower layers map cleanly to parents;
- the middle escalates rather than accumulates;
- planted elements and active lines are paid off, intentionally deferred, or accepted as open;
- no confirmed upper layer has unresolved stale descendants.
