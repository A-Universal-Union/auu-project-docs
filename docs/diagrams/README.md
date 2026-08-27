# A Universal Union diagrams

**Status:** Concept diagrams derived from the AUU v5 replacement drafts dated 27 August 2026. They describe intended civic and user-facing relationships; they do not claim that a production system exists or that any privacy, security, voting, identity, accessibility, or federation property has been demonstrated.

The numbered v5 documents and controlled glossary remain authoritative when a diagram and prose appear to conflict.

## Included set

| File | Job | Placement in this repository |
| --- | --- | --- |
| [`from-public-opinion-to-civic-agency.svg`](./from-public-opinion-to-civic-agency.svg) | Repository edition of *The Political Insanity Loop*. It tests recurring political responses, keeps the useful component of partial answers, and arrives at the missing functions of correctable civic agency. | Linked from the root Reader's Map and `0.mission-statement.md`. It is intentionally too detailed for an inline first-read image. |
| [`auu-functional-model.svg`](./auu-functional-model.svg) | Shows the three-part functional model: foundations, the nine-stage civic cycle, and protections that apply throughout. | Embedded after “The model in one line” in the root Reader's Map. |
| [`auu-logical-architecture.svg`](./auu-logical-architecture.svg) | Shows participant control, the AUU civic core, stable civic contracts, evidence and records, replaceable systems, external institutions, and cross-cutting governance. | Embedded after the dependency map in `2.feature-sets.md`. |
| [`auu-issue-experience.svg`](./auu-issue-experience.svg) | Shows the information architecture of one issue: status sentence, process bar, four persistent cards, current-stage work, progressive disclosure, audience preview, and challenge access. | Embedded after the four persistent cards in `6.user-experience.md`. |

## Suggested Markdown

From the repository root:

```md
![AUU functional model: foundations, civic cycle, and cross-cutting protections](docs/diagrams/auu-functional-model.svg)
```

From a file inside `v5-documents/`:

```md
![AUU logical architecture: participant control, civic core, stable contracts, records, and replaceable external systems](../docs/diagrams/auu-logical-architecture.svg)
```

For the large diagnostic map, prefer a link so the reader knowingly opens a zoomable SVG:

```md
[Open the complete civic-agency diagnostic map](docs/diagrams/from-public-opinion-to-civic-agency.svg)
```

## What changed from the earlier diagram set

The comprehensive source map was retained because it was the accepted master diagram. Its repository edition keeps the title *The Political Insanity Loop* while using the more descriptive filename `from-public-opinion-to-civic-agency.svg`.

The revision also:

- treats “Power won't listen” as the invariant exposed across the map, not as one failed tactic;
- uses the five plain tests: who wants it, who can stop it, how it happens, what happens to people who say no, and who controls the next decision;
- replaces the rejected “Change the People” framing with “Change the Operator” while preserving “same structural bet”;
- generalizes country- and event-specific examples where the structure matters more than the proper noun;
- marks the map as conceptual rather than implying an implementation; and
- aligns the AUU endpoint with the v5 cycle: originate, deliberate, authorize, delegate, act, record, challenge, repair, and federate.

The seven-panel carousel, optional eighth panel, preview sheet, expanded election map, and poster are not included. They were designed as raster social-media graphics and repeat material now expressed more accurately in the four repository diagrams:

- carousel panels 1–6 are absorbed into the complete diagnostic map;
- panel 7 is replaced by the functional model;
- the useful claim from optional panel 8—that AUU is one open proposal rather than a final answer—is preserved by the diagrams' explicit concept status and the v5 evidence boundaries;
- the expanded election map's translation-gap argument remains inside the complete diagnostic map; and
- the poster's six-stage compression is superseded by the complete nine-stage v5 cycle.

## Accessibility and maintenance

Each SVG contains a `<title>` and extended `<desc>`, uses real text rather than outlined letters, and pairs color with headings, labels, position, and line direction. The dark palette is part of the AUU diagram family; the files should still be tested wherever a different renderer, theme, or accessibility mode is expected.

When the civic vocabulary changes, update the prose first and then check every diagram for these controlled distinctions:

- person, identity, pseudonym, role, collective, institution, and federation;
- participation, affected standing, membership, consent, representation, delegation, authority, and recognition;
- public, participant- or member-visible, protected review, and private;
- poll, vote, mandate, action, record, interpretation, challenge, appeal, and repair; and
- technical interoperability versus transferred political or legal authority.

Do not remove the concept-status labels until the corresponding claims have passed the evidence, adversarial, accessibility, legal, operational, and pilot gates defined by the v5 research strategy.
