# Architecture and Migration Plan

| Previous | Contents | Next |
| :--- | :---: | ---: |
| [Mission outline](mission-outline.md) | [Review contents](README.md) | — |

## Proposed hierarchy

The public reading route should become root Reader's Map → v5 collection README → mission README → chapters. Each level explains its own subject. The root keeps the model, safeguards, diagrams, example, and participation routes; the collection explains the document set; the mission README presents the argument and reading order. Direct contextual links remain appropriate.

This is a plan for a controlled mission migration. The paths below do not exist as a result of this review:

```text
v5/
├── README.md
└── mission-statement/
    ├── README.md
    ├── VERSION.md
    ├── CHANGELOG.md
    ├── human-invitation.md
    ├── faith-in-humanity.md
    ├── civilizational-problem.md
    ├── collective-wisdom.md
    ├── civic-infrastructure.md
    └── work-before-us.md
```

The [mission README proposal](mission-outline.md#thesis) and its [linked chapter table](mission-outline.md#documents-list) provide the reviewable content for that landing page. They use actual outline headings in this package. Converting the outline into chapter files is a separate scaffold stage, explicitly marked incomplete until the manuscript is ready.

## Collection README proposal

Proposed title: **A Universal Union — V5 Documents**. Proposed orientation heading: **Overview**.

The overview should state that the collection develops AUU's mission, ethical commitments, proposed functions, social structures, research, and practical limits. It should direct first-time readers back to the root model when needed and suggest beginning with the mission before following a specialist route. It should not repeat the full civic-cycle table, intersection example, or root safeguards explanation.

The following table specifies the proposed **Documents List** in the current reading order. Links here open existing sources; path text describes the future collection README's targets at a mission-only cutover.

| Document | Thesis / purpose | Target from `v5/README.md` at cutover |
| :--- | :--- | :--- |
| [Mission Statement](../../v5-documents/0.mission-statement.md) | Human invitation, foundational commitments, civilizational argument, civic purpose, and participation. | `mission-statement/README.md` |
| [Ethical Discussion](../../v5-documents/1.ethical-discussion.md) | Values, rights, power, privacy, standing, and unresolved tensions that constrain the design. | `../v5-documents/1.ethical-discussion.md` |
| [Feature Sets](../../v5-documents/2.feature-sets.md) | Required civic functions, dependencies, and boundaries of proposed capabilities. | `../v5-documents/2.feature-sets.md` |
| [Social Structures](../../v5-documents/4.social-structures.md) | Membership, consent, representation, authority, and federation without manufacturing legitimacy. | `../v5-documents/4.social-structures.md` |
| [User Experience](../../v5-documents/6.user-experience.md) | What participants must understand and be able to do, including accessible alternatives and challenge. | `../v5-documents/6.user-experience.md` |
| [Research and Development Strategy](../../v5-documents/3.research-and-development-strategy.md) | How questions become evidence, specifications, prototypes, pilots, and qualified decisions. | `../v5-documents/3.research-and-development-strategy.md` |
| [Research Index](../../v5-documents/5.research.md) | Evidence classifications, source limits, and research questions. | `../v5-documents/5.research.md` |
| [Tool Comparison](../../v5-documents/7.tool-comparison.md) | Existing approaches, possible reuse, and capabilities still requiring comparison or testing. | `../v5-documents/7.tool-comparison.md` |
| [Controlled Glossary](../../v5-documents/GLOSSARY.md) | Shared meanings and distinctions across the document set. | `../v5-documents/GLOSSARY.md` |

These temporary standalone targets are deliberate. Other documents need not migrate to make the mission readable. The collection requires no independent version merely because it has a README; that release decision remains separate from mission versioning.

## Current mission preservation map

The baseline is `ef4d1997eaac4f17d07731dd0c8e4c366a2d3487:v5-documents/0.mission-statement.md`. Line numbers identify every nonblank source block in that snapshot, not a future file's positions. The full original remains available through Git. This map proposes placement; any later substantive wording change needs an explicit rationale in the mission's changelog or accompanying editorial record.

| Source lines | Existing material | Proposed destination / treatment |
| :--- | :--- | :--- |
| 1 | Mission title | Retain as the mission README's title; chapter titles express their own scope. |
| 3 | Document-role note and Reader's Map link | Adapt for the mission README; recalculate the root link as `../../README.md`. |
| 5–17 | Opening question, local concerns, contrasting perspectives, and fair hearing | Preserve in Chapter I, What do you want to change? |
| 19–23 | Anger/engagement sequence, need for change, and diagnostic link | Preserve in Chapter I, From engagement to action; SVG path becomes `../../docs/diagrams/from-public-opinion-to-civic-agency.svg`. |
| 25 | Plain definition of civic infrastructure | Keep early in Chapter I; Chapter V develops the explanation rather than postponing the reader's first definition until then. |
| 27 | Case, objections, limited authority, peaceful action, and protected record | Carry into Chapter V, From concern to accountable action. |
| 29–31 | Better disagreement and the trans-rights example | Preserve together in Chapter I, Better disagreement, including rights independent of debate victory. |
| 33 | Policy experiment and all its qualifications | Carry into Chapter IV, Learning across disagreement. Preserve the authority, obligations, nonconsent, rights, and external-cost limits. |
| 35 | Party/world-government disclaimer and coordination across difference | Carry into Chapter V, Authority that can be challenged; maintain a concise orientation in the mission README if needed. |
| 37–41 | Software's limits, human work, civic agency, and mission conclusion | Carry into Chapter VI before Help Build It. The short concluding sentence may need a new transition, which should be recorded rather than silently dropped. |
| 43–51 | Help Build It heading and all closing paragraphs | Preserve in Chapter VI, Help Build It. Keep the grain-of-sand progression and invitation to criticism and experience. |

No source block is proposed for unexplained deletion. Chapters II and III and much of IV are substantive future writing informed by the [argument inventory](source-inventory.md#argument-inventory), not spaces to fill with concatenated quotations. The historical sources remain historical; their technical assurances do not automatically become current claims.

## Link inventory and affected files

The accompanying [inbound-links.tsv](inbound-links.tsv) is a frozen, line-addressed inventory of baseline `ef4d1997eaac4f17d07731dd0c8e4c366a2d3487`. It scans all 25 tracked Markdown, SVG, and YAML files at that baseline for inline links/images and textual references to existing v5 documents and diagrams, including directory mentions and fenced examples. It contains **83 occurrences: 50 live links, 3 live images, 14 filename mentions, 12 directory mentions, 2 example links, 1 example mention, and 1 historical path**. Multiple targets on one line have separate rows. This is a repository inventory, not knowledge of external bookmarks or published copies.

For actual links, the final column resolves the target relative to the containing file. For textual filename mentions it identifies the referenced artifact. Fenced examples are context-dependent illustrations, not active links; their apparent containing-file resolution is not a target-validation result. The historical `v5/0.mission-statement.md` reference identifies a Git source and must remain historical. New links in this review package are outside the baseline inventory and are checked separately.

There are **three live inbound links to the current mission** at the baseline: root README line 134, CONTRIBUTING line 25, and REVIEW line 14. The diagram index also names the mission's current filename in prose. Other affected references are accounted for below.

| Source or group | Recorded occurrences | Mission-only cutover action |
| :--- | ---: | :--- |
| `README.md` | 15 | Apply the approved root edit map. Change the collection index route once `v5/README.md` works; retain useful direct contextual links. Keep diagram placements and access. |
| `CONTRIBUTING.md` | 10 | Change the mission entry to its new README; other specialist links remain valid at legacy paths. |
| `REVIEW.md` | 11 | Change the first-read mission link to its new README. Keep focused review routes and account-optional participation. |
| `docs/diagrams/README.md` | 12 | Update the prose placement reference to the mission/Chapter I. Retain existing examples that remain valid for legacy files and add a deeper-path example only when needed. |
| `v5-documents/0.mission-statement.md` | 1 | Its diagnostic link follows the preserved opening to Chapter I; preserve the old path as a clear pointer after approved cutover. |
| `v5-documents/1.ethical-discussion.md` | 2 | Existing specialist-to-specialist links remain valid; no prose rewrite needed. |
| `v5-documents/2.feature-sets.md` | 4 | Existing links and embedded architecture diagram remain in place. |
| `v5-documents/3.research-and-development-strategy.md` | 1 | Research-index link remains in place. |
| `v5-documents/5.research.md` | 3 | Current strategy/comparison links and maintenance reference remain valid. |
| `v5-documents/6.user-experience.md` | 2 | Embedded issue-experience diagram and other recorded diagram reference remain in place. |
| `AGENTS.md` | 1 | Review the statement about canonical sources only if migration changes its accuracy. No automatic terminology or policy changes. |
| `docs/DOCUMENTATION-CONVENTIONS.md` | 10 | Update present-state statements when appropriate; retain examples, staged-migration rules, and historical explanations with clear status. |
| `project-planning/CODEX-HANDOFF.md` | 11 | Preserve the dated source snapshot and historical anchors; add completion/current-location notes instead of rewriting the history. |

No matching target references were found in the four SVG bodies, two other project-planning documents, issue template, v3.2, v4, social structures, tool comparison, or glossary. The outreach plan still describes the numbered document set in prose; review that wording at cutover without treating it as a broken URL. The ignored `todo.md` mentions the mission as a task but has no relevant path. No reference-style Markdown links or SVG hyperlinks to legacy documents were found in the inspected baseline.

Known external-facing routes include GitHub issue URLs and Discord links in the root/review/contribution documents. This review did not check remote availability or discover external inbound links. The configured Git remote uses `Project-Document`, while existing issue routes use `auu-project-docs`; do not infer that either is broken or replace them without verification at publication.

## Cutover sequence

1. **Review the proposal.** Decide the thesis, chapter scope, voice, treatment of historical conflicts, root disposition map, and preservation plan. This package completes that preparation and stops before authorial decisions are assumed.
2. **Authorize a scaffold separately.** Create the proposed mission directory, six chapter outlines, README, VERSION, and CHANGELOG. Mark every unfinished chapter as an outline, including its status near the opening; retain complete top/bottom navigation. Keep the current mission canonical and link the scaffold only from planning/review material. The public root must not send a newcomer into placeholders.
3. **Draft and review the manuscript separately.** Preserve and develop the mapped source blocks; connect restored arguments to evidence where needed. Include adversarial, accessibility, and affected-person review when available, with honest records of what actually occurred. Complete source/claim checks and all reader-facing headings before treating the directory as a replacement.
4. **Prepare a concrete cutover diff.** Add the lean `v5/README.md` collection map. Update the root only under its separately approved edit scope; update the three mission links, diagram-index prose, and any new references since this snapshot. Re-run the inventory against the actual cutover baseline. Keep all unmigrated specialist documents in place.
5. **Keep the old mission URL meaningful.** Replace the old file with a brief pointer only when the replacement is approved. Preserve its H1 and a `Help Build It` heading so both existing heading anchors still lead somewhere useful. Link the main pointer to `../v5/mission-statement/README.md`, its invitation pointer to `../v5/mission-statement/work-before-us.md#help-build-it`, and a frozen Git blob for the previous full text. Do not maintain a second evolving mission.
6. **Verify before publishing.** Check relative destinations, GitHub heading anchors, legacy pointers, top/bottom navigation, diagram paths and accessibility descriptions, collection order, and account-optional review routes. Inspect the rendered result and seek novice comprehension feedback where feasible. Update version/changelog to the actual reviewable state. Publication, tags, and pushes require their own authorization.

If the replacement is incomplete or the cutover checks fail, keep the current mission canonical. An approved rollback after cutover should be an explicit revision restoring links and a known text, with the reason recorded; it should not erase review history.

## Chapter navigation and version baseline

On the future mission's chapter pages, put the same table directly below the H1 and at the end. Use the containing mission README for Contents and the README's order for neighbors. The two missing endpoints stay as `—`.

| Chapter file | Previous | Contents | Next |
| :--- | :--- | :--- | :--- |
| `human-invitation.md` | — | `README.md` | `faith-in-humanity.md` |
| `faith-in-humanity.md` | `human-invitation.md` | `README.md` | `civilizational-problem.md` |
| `civilizational-problem.md` | `faith-in-humanity.md` | `README.md` | `collective-wisdom.md` |
| `collective-wisdom.md` | `civilizational-problem.md` | `README.md` | `civic-infrastructure.md` |
| `civic-infrastructure.md` | `collective-wisdom.md` | `README.md` | `work-before-us.md` |
| `work-before-us.md` | `civic-infrastructure.md` | `README.md` | — |

Required table markers are `:---`, `:---:`, and `---:` for Previous, Contents, and Next. Parent READMEs are navigation hubs and do not need chapter controls. The future mission's README may return to `../README.md` only after the collection README exists; during a scaffold stage, a link to the existing root at `../../README.md` is sufficient.

Proposed mission baseline: `0.1.0-draft.1`, explicitly **outline/scaffold**, scoped to the entire mission directory. Record the previous canonical mission as the unversioned legacy text at the frozen baseline above. The scaffold changelog should say that it adds an outline and identifies intended restorations; it must not claim the full arguments have already been restored. Later meaningful manuscript states can advance the draft version. The collection's v5 name does not require a `5.0.0` document version.

## Open editorial issues and later cross-document work

| Decision | Recommendation for author review | Where to record the eventual choice |
| :--- | :--- | :--- |
| New philosophical voice | Keep Joshua's convictions explicit; distinguish invitational “we” from an existing collective mandate. | Mission drafting notes/changelog; keep current source text until reviewed. |
| Relational trust and controlled terminology | Explain ordinary relational trust in Chapter II; keep the technical definition scoped. Add a glossary entry only if the distinction needs a shared controlled term. | A separately scoped glossary proposal. |
| Evolutionary argument and mock cases | Restore institutional learning with failure cases and continuing pluralism. Keep v4's mock data labeled; verify empirical sources before importing claims. | Chapter IV evidence notes and provenance record. |
| Eight diagnostic questions | Consider the completed civic-infrastructure chapter; preserve them in the root until an approved destination works. | Root disposition map and migration diff. |
| Length and subsection names | Review the linked outline for argumentative progression; length follows substance. | Mission README and document-level changelog. |
| Rights-floor interpretation and unconnected participation | Carry current unresolved governance/research questions into the mission without pretending to resolve them by wording. | Cross-links to ethics, features, and R&D; later specialist changes only when warranted. |
| Empirical evidence | Prioritize institutional influence, cooperation conditions, persuasion, and privacy/inclusion claims identified in the inventory. | Claim-specific research records; this package is not a literature review. |

The first six-chapter draft and root rewrite need authorial direction on these choices. None prevents completing this planning milestone. No specialist text, glossary entry, diagram, or public route is changed by the recommendations themselves.

---

| Previous | Contents | Next |
| :--- | :---: | ---: |
| [Mission outline](mission-outline.md) | [Review contents](README.md) | — |
