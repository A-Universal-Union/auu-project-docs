# AUU Documentation Conventions

**Status:** Proposed standard for README-first modular documentation.  
**Applies to:** The repository's documentation entry points and, as documents are deliberately migrated, modular v5 document directories.  
**Audience:** Human editors, contributors, and AI agents.

## 1. Principles

Documentation is read as a hierarchy of **README entry points**, not as an undifferentiated list of Markdown files. Each README introduces the part of the project it owns and directs the reader into the next level. A *document* may be an authored work composed of multiple chapter files, with a directory-level version and changelog.

- A README should explain its scope, not only enumerate filenames.
- A parent README's **indexing responsibility** generally ends at the next README. Its `Documents List` points to child entry points; their READMEs own the detailed chapter/subsection inventory.
- A parent remains responsible for *explaining its own subject*. Direct links to useful chapters, diagrams, examples, or review and contribution routes are welcome where they serve the reader; README-first discovery should not force unnecessary clicks.
- The repository root is an **independently useful Reader's Map**, not a mere directory listing. Keep its conceptual overview, essential protections, visual models, practical example, maturity limits, and opportunities to participate intelligible without requiring another document.
- Favor progressive disclosure: make the root quick to scan while linking to specialist explanations. A working editorial range of roughly **800–1,200 words** may help during revision, but is not a mandatory limit and never outranks comprehension, accuracy, and preservation of important qualifications.
- Diagrams and illustrations are integral explanations, not decorative extras or materials to relegate automatically to an appendix.
- Stable paths matter. Avoid renaming chapters to change reading order or to encode new version numbers.
- The thesis and values of AUU are distinct from empirical claims, tested capabilities, and candidate engineering approaches.

## 2. Target organization and ownership

```text
README.md                            # Repository entry: AUU Reader's Map
├── v5/
│   ├── README.md                    # V5 collection entry; links to document READMEs
│   ├── mission-statement/
│   │   ├── README.md                # Mission thesis, diagrams if useful, chapter TOC
│   │   ├── VERSION.md               # Whole authored document version
│   │   ├── CHANGELOG.md             # Whole authored document change history
│   │   ├── human-invitation.md
│   │   ├── faith-in-humanity.md
│   │   ├── civilizational-problem.md
│   │   ├── collective-wisdom.md
│   │   ├── civic-infrastructure.md
│   │   └── work-before-us.md
│   └── ethical-discussion/          # Future migration, only when authorized
│       └── README.md
├── docs/
│   ├── DOCUMENTATION-CONVENTIONS.md
│   └── diagrams/
│       ├── README.md                # Reference/index README; no mandatory Thesis
│       └── *.svg
└── project-planning/                 # Other collections may have their own README
```

The `README.md` paths above represent **navigation**, not a claim that every directory currently exists. The live repository has `v5-documents/` and individual Markdown files. Moving to `v5/` requires a controlled, link-safe migration. Do not move unrelated material merely to make the tree symmetrical. Until such a migration is approved and complete, the root README must continue linking to valid, existing destinations.

**Responsibility by level:**

| Entry point | Owns | Documents List should link to |
| :--- | :--- | :--- |
| Repository `README.md` | **Reader's Map:** public proposition, conceptual civic model and diagrams, concrete example, safeguards, honest maturity boundaries, and participation routes | Major document collections and primary entry points; also useful direct contextual links where appropriate. Link to a legacy standalone file when no child README exists yet. |
| `v5/README.md` | **Collection map:** the v5 document set, how the major documents relate, and suggested reading order. Does not repeat the root's full civic-cycle lesson or example. | `mission-statement/README.md`, `ethical-discussion/README.md`, and other immediate document READMEs (or temporary single-file destinations during migration) |
| `v5/mission-statement/README.md` | The complete mission's thesis, argument progression, and chapter reading order | Its chapter files and significant subsection anchors |
| `docs/diagrams/README.md` | Diagram descriptions, use cases, placement, maintenance, and accessibility | Individual SVG files |
| Chapter Markdown file | One section of an authored document | Previous / Contents / Next navigation to siblings and its owning README |

A parent may mention what a subordinate document covers in one or two sentences, but should not reproduce the child's complete table of contents. Similarly, a single chapter should not independently take over the role of the document README.

## 3. README structure is adaptable

A typical argumentative document README follows:

1. `# <Document title>`
2. `## Thesis` — its central proposition, significance, and scope
3. Supporting argument, introductory diagram, or other explanatory sections **when useful**
4. `## Documents List` — an annotated Markdown table of chapter files and meaningful subsections

This is an **editorial pattern**, not a mandatory set of identical headings. A collection-level README may use `## Overview`, a diagram/reference README may use `## Purpose`, and an architectural README may use `## Model`. The root Reader's Map is distinct: its purpose is to *introduce and explain AUU to an unfamiliar person*, then direct that person onward. It does **not** need a generic `## Thesis` heading. Preserve its useful explanations, example, and diagrams rather than flattening it to a formulaic introduction. `## Documents List` is appropriate where there are navigable child documents or chapters, but a directory without such children need not manufacture a table.

### Root Reader's Map: recommended responsibility and shape

Review the current root README as a whole before changing it. The existing text already serves as an executive overview, a civic model explanation, a safeguard primer, a practical scenario, and a participation gateway. A shorter root is worth exploring, **but not at the cost of those functions**. A possible outline (not fixed headings) is:

1. `# A Universal Union` — stable project title, with documentation version/status shown separately below it.
2. `## The Proposal` — a plain-language account of what AUU is, is not, why it matters, and its conceptual maturity. Include a concise statement of human agency, relational trust, civic learning, and peaceful correction, without duplicating the long mission.
3. `## The Problem` — why existing civic communication and collective action often fail; link the detailed *Political Insanity Loop* diagnostic as a zoomable SVG.
4. `## How It Works` — the nine-stage cycle (**originate → deliberate → authorize → delegate → act → record → challenge → repair → federate**), embedded functional-model diagram, and a comprehensible real-world example such as the existing dangerous intersection.
5. `## Principles and Safeguards` — concise, accurate distinctions about identity, standing, authority, privacy, records and interpretation; clarify that verified procedure is not automatic legitimacy and that the design is not yet validated. Link to fuller ethical and technical treatments instead of rehearsing all their details.
6. `## Documents List` — annotated entry points into `v5/README.md`, diagrams, external review, contribution guidance, and relevant historical/planning material. Link immediately useful primary destinations directly when warranted.
7. `## Review, Contribute, and Discuss` — existing invitation and accurate participation options, without implying support or endorsement that has not occurred.

The outline is a guide to responsibility, not an order to rewrite the root immediately. **First provide a section-level edit map**: retain, condense, relocate with a link to the new canonical explanation, or remove with a reason. Do not strand a critical safeguard in a still-unpublished child document. A first-time reader should be able to describe AUU's goal, its civic model, its unproven status, and available next steps after using the root README alone. It should also be skimmable without reading every paragraph. Test those outcomes with unfamiliar readers when feasible; word count by itself cannot establish success.

An example `v5/README.md` (collection scope):

```markdown
# A Universal Union — V5 Documents

## Overview

These documents develop the project's mission, ethical commitments,
proposed functions, social structures, research, and practical limitations.
Begin with the mission, then follow the specialist documents as needed.

## Documents List

| Document | Thesis / purpose |
| :--- | :--- |
| [Mission Statement](mission-statement/README.md) | Why AUU exists, what it believes, and what future it seeks to make possible. |
| [Ethical Discussion](ethical-discussion/README.md) | The commitments, rights, risks, and ethical conflicts constraining the design. |
```

Do **not** append the mission's six chapters here. `mission-statement/README.md` owns that level.

An example `v5/mission-statement/README.md` (document scope):

```markdown
# A Universal Union: Mission Statement

## Thesis

AUU begins with faith in humanity: human dignity, agency, and relational
trust are the ethical starting points of civic life. It proposes ways to
make cooperation, collective learning, and peaceful correction more
achievable without compelling ideological uniformity or sacrificing freedom.

## Documents List

| Document / section | Thesis / purpose |
| :--- | :--- |
| **I. [The Human Invitation](human-invitation.md)** | From lived concerns and failed discourse to civic agency. |
| ↳ [From Engagement to Division](human-invitation.md#from-engagement-to-division) | Why engagement does not necessarily lead to reform. |
| **II. [Faith in Humanity](faith-in-humanity.md)** | People and relationships provide the moral foundation, not machines. |
| ↳ [Human Trust](faith-in-humanity.md#human-trust) | Relational trust versus proof, credentials, and candidate mechanisms. |
| **III. [The Civilizational Problem](civilizational-problem.md)** | Institutional power, civic capacity, and social incentives. |
| **IV. [The Evolution of Collective Wisdom](collective-wisdom.md)** | Cooperative adaptation, memory, and peaceful correction. |
| **V. [Civic Infrastructure](civic-infrastructure.md)** | Connect the mission to proposed civic capacities and safeguards. |
| **VI. [The Work Before Us](work-before-us.md)** | Uncertainty, criticism, and participation. |
```

The chapters and summaries are a proposed outline, not finished files. Do not publish broken subsection anchors or placeholder links as if they were functional. Check GitHub-generated headings and anchor uniqueness.

## 4. Diagrams belong in the explanation

Keep the existing diagrams in `docs/diagrams/` and continue using their descriptive index. Diagrams may appear in READMEs or relevant chapters according to the level of explanation; not all READMEs need one.

| Existing diagram | Preferred explanatory role |
| :--- | :--- |
| `from-public-opinion-to-civic-agency.svg` | Broad civic problem/diagnostic; preserve its **zoomable link** from the repository introduction or relevant mission text because it is too detailed for casual inline viewing. |
| `auu-functional-model.svg` | Civic foundations, nine-stage cycle, and safeguards; retain as an **inline diagram** in the root Reader's Map near the model explanation. |
| `auu-logical-architecture.svg` | Technical/civic component relationships; retain near the feature/architecture explanation, potentially in a specialist README or chapter after migration. |
| `auu-issue-experience.svg` | User-facing issue structure; retain near the relevant user-experience explanation, potentially in a specialist README or chapter after migration. |

- Use images *where they clarify the surrounding text*. The document's role and actual diagram readability determine inline versus linked placement, not a rigid README section order.
- Preserve alt text, accessible SVG titles/descriptions, descriptive link labels, and warnings that a **conceptual diagram is not a validated implementation**.
- Provide a short prose explanation so the key meaning does not depend exclusively on seeing an image.
- When moving files deeper into subdirectories, recalculate relative diagram paths and update the diagram index's placement references. For example, from `v5/mission-statement/README.md`, the diagram directory is `../../docs/diagrams/`.
- Do not regenerate, discard, or silently reinterpret diagrams as a side effect of moving Markdown files. Propose substantive diagram changes explicitly and keep their vocabulary synchronized with the relevant prose.

## 5. Chapter Previous / Contents / Next navigation

Every **chapter** has the same navigation table twice: immediately after its H1 title and after its last content. Reading order is determined by the owning document's README, not by alphabetical filename order.

```markdown
# Faith in Humanity

| Previous | Contents | Next |
| :--- | :---: | ---: |
| [← Human Invitation](human-invitation.md) | [↑ Mission Statement](README.md) | [Civilizational Problem →](civilizational-problem.md) |

[Chapter content.]

---

| Previous | Contents | Next |
| :--- | :---: | ---: |
| [← Human Invitation](human-invitation.md) | [↑ Mission Statement](README.md) | [Civilizational Problem →](civilizational-problem.md) |
```

For the first chapter, use `—` in Previous; for the last, `—` in Next. Always retain Contents. Directory READMEs are hubs and **do not need chapter-style Previous/Next navigation**; they may provide an easy way to return to their parent README.

GitHub Flavored Markdown (`:---`, `:---:`, `---:`) aligns text inside each column, but does not guarantee that the table stretches across the page. Prefer portable Markdown over HTML/CSS solely to force width.

## 6. Version and change history

Each **authored multi-file document**, not every reference or collection directory, contains one `VERSION.md` and one `CHANGELOG.md`. The version covers the whole document; chapter edits are recorded in Git. Whether the top-level v5 collection needs its own independently released version is a separate decision, not an automatic requirement of having `v5/README.md`.

`VERSION.md` example:

```markdown
# Version

**Document:** A Universal Union: Mission Statement
**Version:** 0.1.0-draft.1
**Status:** Draft
**Scope:** Entire `v5/mission-statement/` document
**Previous published version:** Unversioned legacy mission (if applicable)
```

`CHANGELOG.md` example:

```markdown
# Changelog

## Unreleased

### Added
- Modular directory, README, and chapter outline.

### Restored
- Human trust and the civilizational/evolutionary arguments.

### Preserved
- Accessible opening from the current mission.
```

Use **major** versions for changed governing commitments or thesis, **minor** versions for substantive development without changing the core thesis, and **patch** versions for clarification. Do not increment for every edit or commit. Published document versions can be anchored with Git tags if authorized; tags and releases are never implied by ordinary writing work.

## 7. Migration and link integrity

The mission currently lives at `v5-documents/0.mission-statement.md`; the proposed modular landing page is `v5/mission-statement/README.md`.

1. Inventory incoming links, including root README, `CONTRIBUTING.md`, `REVIEW.md`, other documents, planning files, and `docs/diagrams/README.md`.
2. Preserve the existing text and document which historical argument goes where before splitting it.
3. Draft a coherent directory and child README. **Do not make an incomplete scaffold the public canonical destination.**
4. At an explicitly authorized cutover, revise the parent navigation so the repository README points toward `v5/README.md` and that README points toward the mission's README; update other contextual references as needed. Keep the root Reader's Map independently explanatory, rather than replacing its conceptual content with the new index. Leave useful link-forwarding pointers at old Markdown paths when appropriate. Avoid two independently edited canonical copies.
5. Verify README-to-README links, chapter tables, all diagram paths/placements, anchors, contribution/review links, and first/last navigation boundaries.
6. Migrate each other document as an independently scoped task; do not move all v5 documentation for visual uniformity.

README-first navigation is a **discovery convention**. It does not forbid an in-text cross-reference to a specific chapter, heading, source, or diagram where precision is required.

## 8. Editorial boundaries

The mission may be long (roughly 25 pages if needed), but should maintain a single argumentative progression:

**Human invitation → faith in humanity → civilizational problem → evolution of collective wisdom → civic infrastructure → work before us.**

Treat human trust as a foundational moral premise, and particular social trust implementations as hypotheses. Preserve personhood, credentials, membership, standing, authority, legitimacy, privacy, minority rights, and critical review as distinct concepts. Never imply that evolutionary competition automatically guarantees ethical or epistemic progress. Restore earlier ideas with historical provenance rather than merging drafts indiscriminately; record consequential omissions, reinterpretations, and decisions.
