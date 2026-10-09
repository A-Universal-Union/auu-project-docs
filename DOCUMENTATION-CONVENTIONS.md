# AUU Documentation Conventions

**Status:** Proposed standard for the modular v5 documentation structure.  
**Applies to:** Document directories such as `v5/mission-statement/` and, progressively, other v5 documents.  
**Audience:** Human editors, contributors, and AI agents.

## 1. Principles

A **document** is an authored work; it does not have to be a single Markdown file. A directory can contain the document's thesis, chapters, change history, and version identity while remaining easy to browse on GitHub.

- The directory represents the document; chapter files represent substantial sections.
- A GitHub-rendered `README.md` communicates the argument and its reading order, not just a list of files.
- Stable paths matter. Avoid renames for order changes and avoid filenames containing version numbers.
- Git tracks every individual file edit. A single version identifies a reviewable state of the **whole document directory**.
- Documentation may explain beliefs and ambitions, but must not confuse them with tested features or empirical findings.

## 2. Target organization

```text
v5/
├── README.md                         # V5 document collection index
├── mission-statement/
│   ├── README.md                     # Thesis and annotated table of contents
│   ├── VERSION.md                    # Version of the complete mission statement
│   ├── CHANGELOG.md                  # Significant changes to the complete document
│   ├── human-invitation.md
│   ├── faith-in-humanity.md
│   ├── civilizational-problem.md
│   ├── collective-wisdom.md
│   ├── civic-infrastructure.md
│   └── work-before-us.md
├── ethical-discussion/               # Future modularization, not a present fact
│   └── ...
└── ...                                # Other documents migrate only when authorized
```

The existing repository currently uses `v5-documents/` and standalone files. The target above is a proposed **one-time transition**, not an assertion that these paths already exist. Migrate deliberately, keep links working, and avoid competing canonical copies. The mission can be migrated separately from other documents. Do not move all documents merely to achieve visual symmetry.

## 3. README contract

The section order is fixed:

1. `# <Document title>`
2. `## Thesis` — one or a few paragraphs stating the central proposition, why it matters, and the document's scope.
3. `## Documents List` — a Markdown table showing the logical progression of chapters and any noteworthy subsections.

Example for `v5/mission-statement/README.md`:

```markdown
# A Universal Union: Mission Statement

## Thesis

A Universal Union begins with faith in humanity: human dignity, agency,
relationships, and the capacity for cooperation must remain the foundations
of civic life. It proposes institutional conditions that could make collective
learning, accountability, and peaceful correction more achievable without
requiring ideological uniformity or surrendering freedom.

## Documents List

| Document / section | Thesis / purpose |
| :--- | :--- |
| **I. [The Human Invitation](human-invitation.md)** | From lived concerns and failed discourse to a shared need for civic agency. |
| ↳ [From Engagement to Division](human-invitation.md#from-engagement-to-division) | Why attention and outrage do not reliably produce reform. |
| **II. [Faith in Humanity](faith-in-humanity.md)** | People and their relationships, not machinery, supply the ethical foundation. |
| ↳ [Human Trust](faith-in-humanity.md#human-trust) | Distinguish relational trust from credentials and mechanisms. |
| **III. [The Civilizational Problem](civilizational-problem.md)** | Explain the technological/civic maturity gap, power, and incentives. |
| **IV. [The Evolution of Collective Wisdom](collective-wisdom.md)** | Reclaim cooperation, institutional adaptation, learning, and peaceful correction. |
| **V. [Civic Infrastructure](civic-infrastructure.md)** | Connect the purpose to the proposed civic functions and safeguards. |
| **VI. [The Work Before Us](work-before-us.md)** | Acknowledge uncertainty, invite criticism, and call for participation. |
```

These headings and summaries are a working outline, not a claim that the chapters have been written. Replace example links to subsection anchors with actual headings before publication. GitHub generates heading anchors; verify their spelling and uniqueness.

For `v5/README.md`, use the same structural pattern, but the Documents List contains **document directories** rather than chapters. It may also link to legacy single-file documents during a staged migration. The root repository `README.md` remains the public Reader's Map; the v5 index should complement, not duplicate, that role.

## 4. Previous / Contents / Next navigation

Every chapter gets the same navigation table **twice**: directly below its H1 chapter heading and after its final content. The links must reflect the order in its document README, not alphabetic filename order.

Example inside `faith-in-humanity.md`:

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

For the first chapter, use `—` in the Previous cell; for the last, use `—` in the Next cell. Keep all three columns for consistency. Do not turn a missing neighbor into a dead link. `Contents` always returns to the document's `README.md`.

GitHub Flavored Markdown table markers `:---`, `:---:`, and `---:` align the **contents** left, center, and right. They do **not** guarantee that a table spans the page width. Prefer portable Markdown; don't introduce HTML/CSS solely to force full-width navigation. The navigation tables supplement, rather than replace, semantic Markdown headings and direct links to subsections.

The document README is the table-of-contents landing page, so it does not need chapter-style previous/next controls. A short link to the collection-level index (`../README.md`) is appropriate.

## 5. Version and change history

Each document directory, **not each chapter**, contains `VERSION.md` and `CHANGELOG.md`. Example:

`VERSION.md`:

```markdown
# Version

**Document:** A Universal Union: Mission Statement
**Version:** 0.1.0-draft.1
**Status:** Draft
**Scope:** Entire `v5/mission-statement/` document
**Previous published version:** Unversioned legacy mission (if applicable)
```

This version is illustrative; establish the baseline deliberately. The project's v5 designation is a **collection/generation**, not an instruction to set every document version to `5.0.0`.

`CHANGELOG.md`:

```markdown
# Changelog

## Unreleased

### Added
- Document directory, thesis, and linked chapter outline.

### Restored
- Human trust, institutional adaptation, and collective learning as explicit arguments.

### Preserved
- Accessible, human-centered invitation from the existing mission.

### Open editorial questions
- [Specific unresolved question and its source/context.]
```

Meaningful reviewable milestones can use major/minor/patch numbers:

- **Major:** Substantially changes the thesis or governing commitments.
- **Minor:** Develops, extends, or reorganizes the work without replacing its core commitments.
- **Patch:** Corrects language or references without materially changing meaning.

Do not increment for every keystroke or ordinary commit. Git provides file-level history. Published versions can later be anchored with Git tags such as `mission-statement/v1.0.0` if release/tagging has been authorized. Keep a clear distinction between draft and published status, and do not fabricate release dates or adoption.

## 6. Migration and link integrity

The original canonical location is currently `v5-documents/0.mission-statement.md`. The proposed permanent location is `v5/mission-statement/README.md`, with chapter files below it. Treat the move as a **controlled migration**:

1. Inventory inbound links in the root README, contributing/review documentation, other v5 files, planning files, diagrams, and external-facing resources where known.
2. Preserve the original mission text in version control and an explicit provenance/mapping record before decomposition.
3. Prepare and review the new modular destination; do not mark it canonical while it is only an incomplete scaffold.
4. At an authorized cutover, switch internal links to the new canonical location and preserve the old path as a small pointer where appropriate; do not maintain two independently evolving copies of the same canonical text.
5. Verify Markdown relative links, target files, generated heading anchors, and all previous/next navigation (including first/last chapters).
6. Migrate other documents in separately approved, bounded work. Do not move them only because the mission moved.

Avoid changes to existing paths **after** their canonical destination has been established. Stable URLs take precedence over numbering files for display order.

## 7. Editorial boundaries

The mission may be long (roughly 25 pages if the argument warrants it), but should not become a copy of the feature specification or research index. Use chapter divisions to maintain one sustained progression:

**Human invitation → faith in humanity → civilizational problem → evolution of collective wisdom → civic infrastructure → work before us.**

Treat human trust as a foundational moral premise, while treating proposed technical trust graphs as hypotheses. Preserve the distinction between personhood, credentials, membership, standing, authority, and legitimacy. Defend learning and cooperation without asserting that evolutionary competition automatically produces wisdom or justice. Retain the current mission's approachable introduction and explicit invitation to critics.

Do not silently discard substantive historical reasoning. Important restorations, exclusions, and reinterpretations belong in an editorial provenance map and, once accepted, in the document changelog.
