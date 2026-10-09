# Mission Reconstruction Review

## Thesis

AUU can recover a fuller account of human trust, civic agency, cooperative learning, and peaceful correction while preserving the current mission's invitation and v5's clearer limits on authority. Reconstruction needs to distinguish an argument missing from the short mission from one still developed elsewhere in the repository. It must also distinguish a conviction worth stating from an implementation or prediction that needs evidence.

This is an editorial review package for the [handoff](../CODEX-HANDOFF.md), inspected against repository commit `ef4d1997eaac4f17d07731dd0c8e4c366a2d3487`. The [existing mission](../../v5-documents/0.mission-statement.md) remains canonical. This package does not adopt new philosophical wording or establish a new public reading route.

## Documents List

| Document / section | Thesis / purpose |
| :--- | :--- |
| [Source and argument inventory](source-inventory.md) | Recover the historical argument without inheriting unsupported assurances or erasing v5's safeguards. |
| ↳ [Verified sources](source-inventory.md#verified-sources) | Identify the inspected snapshots, exact source locations, and limits of the comparison. |
| ↳ [Argument inventory](source-inventory.md#argument-inventory) | Map retained, weakened, altered, and absent ideas to the six proposed chapters. |
| ↳ [Conflicts and editorial decisions](source-inventory.md#conflicts-and-editorial-decisions) | Expose disagreements requiring an explicit treatment in the future manuscript. |
| [Root Reader's Map audit](root-readme-audit.md) | Shorten repetition while preserving a complete first explanation of AUU. |
| ↳ [Section disposition map](root-readme-audit.md#section-disposition-map) | Account for every current section before any public rewrite. |
| ↳ [Proposed root structure](root-readme-audit.md#proposed-root-structure) | Place the proposal, civic model, safeguards, and participation routes in a scannable progression. |
| [Mission README and chapter outline](mission-outline.md) | Propose a thesis and six-chapter argument with real subsection links, while preserving the current mission as canonical. |
| ↳ [Six-chapter contents](mission-outline.md#documents-list) | Make each chapter's thesis and contribution visible before drafting. |
| [Architecture and migration plan](architecture-and-migration.md) | Establish a staged root-to-collection-to-document reading route and a controlled mission-only cutover. |
| ↳ [Current mission preservation map](architecture-and-migration.md#current-mission-preservation-map) | Account for every nonblank block of current mission prose. |
| ↳ [Link inventory and affected files](architecture-and-migration.md#link-inventory-and-affected-files) | Identify live links, images, literal mentions, examples, and historical paths requiring different treatment. |
| ↳ [Open editorial issues](architecture-and-migration.md#open-editorial-issues-and-later-cross-document-work) | Identify decisions for Joshua and later specialist work without assuming acceptance. |
| [Baseline link inventory](inbound-links.tsv) | Line-addressed supporting data for all recorded v5-document and diagram references at the inspected baseline. |

## Review status

The handoff's initial planning milestone is ready for author review: historical inventory, root README audit, linked mission outline, collection proposal, prose preservation map, and migration/link plan. The full manuscript, mission scaffold, public README rewrite, canonical cutover, and other document migrations remain separate work.

## Verification and limits

Checks performed on October 9, 2026:

- All 27 repository Markdown files: 218 local links/heading anchors checked with no errors; fenced illustrative examples excluded. Eight historical GitHub blob links were verified against local Git objects, not fetched remotely.
- Four review chapters: identical top/bottom Previous / Contents / Next tables, required alignment, README reading order, and first/last boundaries checked.
- All eleven root sections and five nested distinctions accounted for in the audit; all 26 nonblank source lines of the current mission covered exactly once by the preservation map.
- Six proposed mission chapters, eight expected review-package files, and one document-level VERSION/CHANGELOG pair checked.
- All 53 live targets in the 83-occurrence baseline link inventory exist. Historical references, textual mentions, and fenced examples are distinguished from active links.
- The root README, current mission and specialist documents, glossary, diagrams, contribution/review guides, standing instructions, conventions, and current historical source files match the inspected baseline. No `v5/` scaffold was created.
- Git whitespace checks passed for the staged changes. No automated project test suite or CI workflow was present in the inspected repository; its `.github/` content is the review issue template.

External link availability, external research claims, rendered GitHub/mobile/accessibility behavior, and unfamiliar-reader comprehension were not tested. These checks establish local consistency and preservation, not independent review or validation of AUU's proposals.

## Exact file scope

Added in this directory: `README.md`, `VERSION.md`, `CHANGELOG.md`, `source-inventory.md`, `root-readme-audit.md`, `mission-outline.md`, `architecture-and-migration.md`, and `inbound-links.tsv`. The only existing file changed outside this directory is `project-planning/CODEX-HANDOFF.md`, with a new section linking to this review package. No earlier handoff text was rewritten.

[Document version](VERSION.md) · [Change history](CHANGELOG.md) · [Current Reader's Map](../../README.md)

**AI assistance:** Codex inspected repository text and history, prepared this comparison, and performed mechanical checks. This is an editorial proposal for Joshua's judgment, not independent review, empirical validation, or evidence of a community mandate.
