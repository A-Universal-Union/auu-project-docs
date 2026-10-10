# Codex Handoff — AUU Mission Statement Reconstruction

**Prepared:** 2026-10-09  
**Task:** Establish a reviewable plan and initial modular documentation structure for the expanded mission statement.  
**Boundary:** This handoff does **not** authorize writing the complete 25-page mission, migrating all v5 documents, making a release, or pushing changes.

## 1. Context and decisions

AUU's previous document iterations have gradually shifted emphasis. The earliest and v4 materials foreground human relational trust, social cooperation, ideological adaptation, civilizational incentives, civic agency, and peaceful reform. The current v5 material is stronger on limited authority, standing, verifiability, privacy, rights, challenge, repair, and non-overclaiming, but the mission's explicit civilizational argument was substantially compressed.

The goal is **not to revert to v4**. It is to preserve v5's rigor and approachable opening while restoring the earlier philosophical and evolutionary foundations.

The author has made these decisions:

- **Faith in humanity and human relationships is foundational.** The mission can assert this ethical commitment without first empirically proving that human beings outperform machines on every task. Distinguish it from the *engineering hypothesis* that witnessed social trust graphs or any particular identity mechanism will be effective and safe. Do not exclude unconnected people.
- **The mission may be a long, serious work**—25 pages or more if justified—rather than a conventional short mission statement. Its existing human-centered opening remains the hook.
- **A document is a directory** with a GitHub-rendered README, thesis, annotated linked table of contents, chapters, document-level version, and changelog.
- **README-first hierarchy:** root `README.md` -> `v5/README.md` -> document `README.md` -> chapters. A parent's **index** normally terminates at its child's README, but explanatory responsibility does not. Keep useful direct links to significant chapters, diagrams, review and contribution routes; do not require needless click-throughs.
- **The root README is a public Reader's Map, not a bare index:** Preserve its accessible explanation of the proposal and maturity, nine-stage civic cycle, functional-model diagram, zoomable civic-agency diagnostic, dangerous-intersection example, indispensable identity/authority/standing/privacy/records distinctions, and pathways to documentation and participation. The `v5/README.md` is the lean *collection map*, not a second copy of the Reader's Map.
- **Root README length warrants review, not automatic cutting:** Evaluate cognitive load, redundancy, navigation, and the value of content to a first-time reader. Roughly 800–1,200 words is an optional editorial target, not a requirement. Never shorten it by losing the model, diagram-led explanation, practical example, limitations, or important safeguards. First document a retain/condense/move-with-link/remove rationale for each existing section.
- **Flexible README structure:** start with `# <title>`, then a scope-appropriate introduction (`## Thesis` for argumentative documents; `## Overview`, `## Purpose`, or `## Model` for other READMEs). Include an annotated `## Documents List` table wherever documents/chapters need listing. A document README owns significant chapter subsection links; a collection README links only to document README entry points. Preserve readable prose and diagrams outside this minimal skeleton when useful.
- **Diagrams are essential:** preserve the existing civic-agency diagnostic (zoomable link), root functional model (inline), logical architecture diagram, issue-experience diagram, and the `docs/diagrams/README.md` index. Retain their explanatory placement, conceptual-status caveats, accessible descriptions, and correct paths throughout migration.
- **Navigation:** each chapter has Previous / Contents / Next tables at its top and bottom, with left/center/right aligned columns. First/last chapters show no link for the missing neighbor. Reading order comes from the README.
- **Version at the document-directory level.** Keep chapter filenames stable, without per-chapter version numbers or renaming on subsequent revisions. Git provides file history.
- **Target architecture:** directories inside `v5/` (starting with `v5/mission-statement/`). The repository presently uses `v5-documents/`; this requires a deliberate, link-safe transition, not an unannounced bulk rename.

Read the root `AGENTS.md` and `docs/DOCUMENTATION-CONVENTIONS.md` first if installed. Those files are part of this handoff package.

## 2. Verify current source state

Inspect before changing anything; if the repository has advanced beyond this handoff, adapt to the actual files and report differences.

Known current repository (as checked on 2026-10-09):

- `README.md` — v5 Reader's Map (about 14,000 characters at review), already a substantial conceptual introduction rather than a conventional index. It explains the civic cycle **originate → deliberate → authorize → delegate → act → record → challenge → repair → federate**, embeds `docs/diagrams/auu-functional-model.svg`, links the zoomable *Political Insanity Loop* diagnostic, walks through a dangerous-intersection case, gives five important distinctions, covers authority and record visibility, and ends with the current documentation/participation routes.
- `CONTRIBUTING.md`, `REVIEW.md`, and project-planning material — incoming links and public participation workflows.
- `v5-documents/0.mission-statement.md` — current short mission; a human-centered invitation beginning **“What do you want to change?”**, ending with **“Help Build It”**.
- `v5-documents/1.ethical-discussion.md` through `7.tool-comparison.md`, plus `GLOSSARY.md` — specialist documents that should not be rewritten merely because the mission's architecture changes.
- `project.v3.2.md` and `project.v4.0.md` — earlier material in the root; v4 includes *Evolutionary Pressures on Ideologies*, *Bottom-Up Convergence*, trust, social structures, and feedback mechanisms.
- Older v3.3–v3.5, the original 2024 PDF, early June 2026 v5 mission, and `temporary-corpus.md` salvage material are available through repository history (not necessarily the current working tree).

Useful historical anchors, if available in local Git history:

- Original PDF: commit `bad6e949be741f158578fffd9c89acf1dfc2180c`, `a-universal-union.pdf`.
- Historical v3.3–v3.5: commit `8d63185b9d17d525b026d07cd0a66620a35f2797`.
- Early June 2026 mission: commit `67ecdd90247ffbe407f1735106724decb340a911`, `v5/0.mission-statement.md`.
- Salvage corpus: commit `76c52956f3a496db91e5bef50c729e207b4323be`, `v5-documents/temporary-corpus.md`.

If historical blobs are unavailable in local Git, report the gap or use verified GitHub sources. Do not reconstruct missing text from memory as though it were verbatim.

## 3. Required conceptual outline

Build the document outline in this logical order, keeping filenames stable and assigning provisional chapter theses:

| File | Chapter | Central purpose |
| :--- | :--- | :--- |
| `human-invitation.md` | I. The Human Invitation | Retain the accessible present-day concerns, incompatible perspectives, better disagreement, and the need for action. |
| `faith-in-humanity.md` | II. Faith in Humanity | Human dignity, conscience, agency, relationships and trust; machinery serves persons, not vice versa. |
| `civilizational-problem.md` | III. The Civilizational Problem | Institutional power, financial capture, technological acceleration, degraded discourse and normalized incentives. |
| `collective-wisdom.md` | IV. The Evolution of Collective Wisdom | Cooperation, reciprocal learning, ideological/institutional adaptation, evidence, memory and peaceful correction. |
| `civic-infrastructure.md` | V. Civic Infrastructure | Explain AUU's intended civic cycle and social-trust rationale, while retaining privacy, rights, standing, bounded authority, and appeal. |
| `work-before-us.md` | VI. The Work Before Us | Uncertainty, research, external criticism, participation, and the existing invitation to help build. |

The README must make the argument visible as a whole and provide subsection links only for real headings. Avoid repeating the whole argument in the README.

## 4. Historical ideas to account for

Make a source-grounded inventory before deciding what to move, rewrite, or exclude. Minimum coverage:

- The premise of **humanly grounded social trust**, distinct from whether a seven-witness/connection graph works technically.
- Human agency and dignity; humans are not merely economic units or data points.
- The mismatch between accelerating technological power and civic capacity.
- Financial/institutional concentration of power and manipulation of discourse.
- Conditions that reward cooperation versus deception, domination, and capture.
- Civic learning, ideological/institutional experimentation, evidence, feedback, memory, and correction.
- The difference between structured disagreement and coerced unanimity; protecting minorities and dissent.
- Privacy for persons and reviewability for authority.
- Peaceful correction as an alternative to paralysis or violent rupture.
- The current v5's contributions: nonparticipating affected persons, scoped authority, consent, challenge, repair, rights protections, accessibility, honest capability boundaries, and reuse/research before engineering.

A helpful inventory schema is:

| Idea or argument | Historical source / exact heading | Current location / treatment | Status (retained, weakened, altered, absent) | Proposed chapter | Evidence or qualification needed | Editorial action |

Use precise references, and indicate uncertainty. The schema is an editorial tool, not a request to manufacture citations or populate invented facts.

## 5. Authorized execution sequence — stop after the initial milestone

**Phase A — Inspect and inventory**

1. Read standing instructions, repository map, current mission, relevant v4/v3 passages, and available history.
2. Enumerate inbound links to the mission and other `v5-documents/` paths, including existing diagrams and their index; identify potential navigation breakage.
3. Produce the historical argument inventory, prioritizing significant missing/weakened arguments, not superficial wording differences.
4. Note any conflicts between historical aspirations and v5's clearer rights, safety, and evidence standards.
5. Audit the **current root README section by section**, identifying: what a newcomer needs immediately; what is a necessary qualification; what repeats specialist documents; what the diagrams/examples uniquely contribute; and what could be condensed or delegated once a valid child README exists. Record each section as **retain / condense / move with link / remove with justification**. This is an editorial audit, not authorization to rewrite the root.

**Phase B — Prepare documentation architecture for review**

1. Propose a hierarchy that begins at the **root README**, continues through `v5/README.md` listing **document README entry points**, and reaches `v5/mission-statement/README.md`, which owns the annotated chapter/subsection table. Avoid duplicating child inventories in parents.
2. Propose a **concise but self-contained root Reader's Map** using the existing civic model, important distinctions, diagrams, example, honest status, and participation links. The working outline is: `# A Universal Union` (with v5/status as metadata), **The Proposal → The Problem → How It Works → Principles and Safeguards → Documents List → Review, Contribute, and Discuss**. These headings are provisional. Do not impose `## Thesis` on the root or require a precise word count; the guiding test is novice comprehension plus skimmability.
3. Keep `v5/README.md` a compact map of current documents without copying the civic-cycle table, the full intersection example, or the root's five distinctions. For other READMEs, propose scope-appropriate `## Thesis`, `## Overview`, `## Purpose`, or `## Model` introductions.
4. Specify the chapter split, top/bottom navigation, `VERSION.md`, and `CHANGELOG.md` according to the conventions document.
5. Establish a **migration/link plan** for the transition from `v5-documents/` to `v5/`, including root-to-v5-to-document README navigation, diagram placement, a controlled cutover, and how old inbound links remain meaningful. Other documents need not migrate immediately.
6. If asked to implement scaffolding in this run, you may create the new draft directory, README, versions, changelog and chapter outline; **keep the current mission canonical until a complete replacement is approved**. Preserve the existing mission's source content and avoid publishing incomplete placeholder chapters as a finished document.
7. Do not automatically rewrite the root README or copy generated speculative text into specialist documents. Record proposed later edits and evidence needs separately.

**STOP AND REPORT.** Deliver the idea inventory, mission outline/README, **root README section audit and recommended shorter structure**, migration proposal, open editorial issues, and exact files changed. The full manuscript and published root README rewrite are separately authorized phases.

## 6. Future phases — require a separate instruction

- Draft a sustained six-chapter mission, using historical text thoughtfully rather than concatenating old versions. Aim for as much length as the argument deserves; ~25 pages is acceptable.
- Test the text adversarially for authoritarian implications, exclusion of isolated people, unsupported claims about political evolution, violations of minority rights, and unearned privacy/security assurances.
- At an approved publication boundary, designate the new directory as canonical, update inbound links, keep old paths as clear historical pointers where feasible, synchronize changelogs, and optionally tag a published revision.
- Following the root README audit and explicit authorization, edit the root Reader's Map for progressive disclosure; preserve its self-contained explanatory role, embedded functional model, diagnostic link, practical illustration, safety distinctions, and invitation to participate. Update the diagram placement index and verify every navigation destination. Test novice comprehension when feasible.
- Migrate or decompose other v5 documents in later, individually scoped changes, avoiding unnecessary simultaneous rewrites.

## 7. Acceptance checks for the initial milestone

- The repository's reading route begins with READMEs; the root, collection, and document READMEs link to the next level without unnecessary duplication of child contents.
- A section-by-section root README audit explains exactly what to retain, condense, delegate with a canonical link, or remove with justification; no rewrite is silently made. The proposed root remains self-contained and skimmable, preserving the nine-stage model, diagnostic link, functional diagram, practical example, protections, unproven status, and participation routes.
- Each README's introduction fits its purpose (`Thesis` is not mandatory for navigational/reference indexes), and existing diagrams retain their explanatory role and accessibility/status information.
- The author can identify every chapter's thesis from the mission README table without opening its file.
- The six-chapter order is coherent and existing mission prose is preserved, not silently replaced.
- Faith in humanity is clear as a value, and social-trust implementations remain testable proposals.
- The inventory accounts for foundational lost/altered arguments and major v5 safeguards, with verified source references.
- Versioning occurs once per document directory, not independently per chapter.
- All written relative links resolve; all existing inbound links are accounted for; no published reader is silently directed to incomplete scaffolding.
- Any chapter already populated contains navigation at both ends; first/last boundary behavior is correct.
- The report states what was inspected, changed, deferred, unverified, and what approval is needed next.
- No release, push, broad rename, or substantive philosophical rewrite occurs without a separate instruction.

## 8. Initial milestone review package

The [Mission Reconstruction Review](mission-reconstruction/README.md) records the October 9, 2026 source inventory, root README audit, proposed mission outline, and migration/link plan. It uses repository baseline `ef4d1997eaac4f17d07731dd0c8e4c366a2d3487` and preserves the current public documents. Its recommendations await author review; the manuscript, scaffold, root rewrite, and canonical cutover have not been executed.

## 9. Authorized draft phase — October 10, 2026

The author authorized creating the six-chapter structure and drafting Chapters I–II, with two-digit filename prefixes for sorting. The [working mission draft](../v5/mission-statement/README.md) records progress and document-level versions. Chapters III–VI remain outlines, and the current mission remains canonical. This later instruction supersedes the earlier unnumbered filename proposal and the initial milestone's scaffold boundary; it does not authorize the full manuscript, root rewrite, or public cutover.

That milestone is complete for author review at mission version `0.1.0-draft.3`. Chapter I preserves the mapped invitation passages; Chapter II develops the human foundation in new draft prose. The mission changelog records the source and change maps. Acceptance of the new wording and drafting the remaining chapters are later decisions.

## 10. Public voice revision — October 10, 2026

The author requested that the voice guidance apply to public writing for a general audience, and asked for both a revision of the new draft and a temporary revision of the short public mission. The [expanded draft](../v5/mission-statement/README.md) is now at `0.1.0-draft.4`, with the introduction and Chapters I–II revised and a source/change map in its changelog. Chapters III–VI remain outlines.

The [temporary public mission revision](mission-reconstruction/05-public-mission-voice-draft.md) is a separate comparison copy in the review package, which is now at `0.1.0-draft.5`. Its changelog accounts for every original source block. The original short mission remains canonical. The public root, specialist documents, and diagrams retain their contents and routes.

## 11. Mission development after form review — October 10, 2026

The author accepted the recommendation to retain the six-chapter structure, make a focused pacing revision to Chapter II, and draft Chapters III–IV before another comprehensive voice pass. This extends the drafting authorization to those two chapters. Chapters V–VI remain outlines; preserving deferred design questions in Chapter V's outline is part of the Chapter II revision.

The pacing stage was completed at mission version `0.1.0-draft.5`, Chapter III at `0.1.0-draft.6`, and Chapter IV at `0.1.0-draft.7`. The phase is complete for author review. The manuscript gives affirmative cooperation and the human costs of exclusion and failed correction more space, develops institutional conditions and peaceful organization, and follows through into experimentation, civic memory, repair, and learning across communities. Its changelog maps the sources, relocation of detailed participation alternatives, and evidence limits. Public routing, the canonical short mission, its temporary revision, and specialist documents remain outside this phase; Chapters V–VI remain outlines.
