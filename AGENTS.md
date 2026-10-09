# AGENTS.md — A Universal Union

These are standing instructions for AI coding and documentation agents working in the AUU repository. They apply to the repository unless a more specific, compatible instruction governs a subdirectory. The repository's current files and Git history are the source of truth for what exists; proposals in planning documents are not implemented facts.

## Purpose and intellectual commitments

A Universal Union (AUU) proposes human-centered civic infrastructure for collective reasoning, accountable authority, peaceful action, institutional learning, and correction. It is currently a conceptual, research, and documentation project, **not a deployed platform**.

Preserve the distinction between:

1. **Foundational commitments:** the dignity and agency of human beings, trust grounded in human relationships, the ethical primacy of people over machinery, pluralism, and rights that cannot be overridden by popularity.
2. **Arguments about the world:** claims about political institutions, incentives, technology, cooperation, power, and civilizational development. These require reasoning, evidence, limitations, and fair treatment of objections.
3. **Design hypotheses:** proposed mechanisms, such as witnessed social relationships, a bounded trust graph, identity proofs, deliberative tools, and federated governance. Their feasibility and performance require research and testing; they are not established by belief in their underlying values.

**Do not try to empirically prove AUU's faith in humanity as a prerequisite for stating it.** This is a philosophical starting commitment, not a claim that every person is more reliable than every machine in every circumstance. Likewise, do not present any particular social-trust algorithm as validated merely because its ethical motivation is compelling. Account explicitly for isolated, vulnerable, dissenting, and unconnected people.

AUU's historical mission includes more than process verification: collective learning, cooperative adaptation, civic memory, peaceful correction, and the possibility of changing the conditions that reward manipulation and domination. Preserve these concerns when editing for clarity or accessibility. Do not erase earlier arguments silently.

## Read first; preserve provenance

- Inspect the relevant current documents, their cross-references, and repository history before rewriting or moving them. Source text takes precedence over an agent's recollection, previous summary, or inference.
- For the documentation architecture and navigation standard, follow [`DOCUMENTATION-CONVENTIONS.md`](DOCUMENTATION-CONVENTIONS.md) when that file is present.
- Treat the root `README.md` (Reader's Map), `CONTRIBUTING.md`, `REVIEW.md`, the controlled glossary, ethical discussion, research documents, and current mission as mutually connected sources. Maintain their conceptual distinctions.
- When reconstructing the mission, consider the original PDF, v3.x drafts, v4, the early June 2026 v5 mission, the human-centered August revision, and the available salvage corpus. Trace consequential ideas to actual source text or history; do not invent historical positions or citations.
- Where documents disagree, report the difference instead of silently declaring one interpretation correct. Distinguish the current model from past proposals and future recommendations.

## Documentation architecture

- A **document** may consist of a directory. Its `README.md` is the GitHub-rendered entry point; individual Markdown files are chapters.
- Use this README order: `# Document title`, `## Thesis`, `## Documents List`. The Documents List is a Markdown table with links to chapters and significant subsections and short statements of their thesis or purpose.
- Provide **Previous | Contents | Next** navigation tables immediately under each chapter title and at the bottom of each chapter. Align columns left, center, and right using GitHub Flavored Markdown (`:---`, `:---:`, `---:`). Contents points to the containing document's `README.md`; previous/next follow the README's reading order. Leave unavailable first/last links unlinked.
- Each document directory maintains one `VERSION.md` and one `CHANGELOG.md`. **Version the document, not each chapter.** Git records individual file edits. Do not create version-numbered copies or rename chapter files with every release.
- Prefer meaningful, stable, unnumbered chapter filenames. Order chapters in the README, not by filename prefix. Split chapters for a substantive conceptual boundary, not merely to make files small.
- Use relative links and check them, including GitHub heading anchors. Keep the root Reader's Map and contributing links functional when paths change. A directory migration is a deliberate one-time operation, never an incidental side effect of a prose edit.

## Writing and evidence discipline

- Preserve the current human-centered invitation as the mission's approachable entry point; restore earlier philosophical and civilizational arguments around it instead of replacing it with a technical overview.
- Prefer a sustained, readable argument over repetitive lists of requirements. The mission may be long where length earns its place. Supporting documents should retain their specialist requirements, evidence and safeguards.
- Distinguish ethical principles, empirical assertions, open questions, candidate designs, and demonstrated capabilities. Do not promote hypothetical identity, voting, privacy, safety, accessibility, or governance properties into guarantees.
- Do not equate correct procedure with just outcomes, consensus with wisdom, credentials with authority, or membership with standing. Respect protected dissent, affected nonparticipants, rights floors, transparency of authority, and privacy of persons.
- Avoid unsupported universals; cite sources accurately when making specific empirical claims. Do not invent sources, contributors, public support, tests, or a collective mandate. Do not imply AUU has an operational system or external endorsement.
- Keep the author's first-person convictions distinct from statements that would imply an existing organization speaks unanimously. AI assistance and uncertainty should not be disguised.
- Preserve controlled terminology or explicitly propose changes to the glossary. Keep accessibility, reasonable cognitive load, and nontechnical readers in mind.

## Change discipline and stopping boundaries

- Make focused, reviewable changes. Before substantial edits, state the intended scope and identify affected documents and links.
- For significant removals, reversals, reinterpretations, or migrations, provide a provenance/change map explaining what was preserved, altered, or omitted and why. Do not delete hard-won arguments as an accidental consequence of compression.
- Keep `VERSION.md` and `CHANGELOG.md` consistent with **meaningful reviewable states**; ordinary commits need not change a document's version.
- Verify local relative links, headings, navigation order, expected files, and any automated checks available. Report which checks were actually run; do not claim independent review.
- **Stop at the requested boundary.** A request for audit or plan is not authorization to rewrite or publish. A request for scaffolding is not authorization to complete the philosophical manuscript, migrate unrelated documents, tag a release, or push changes. Surface unresolved editorial or architectural choices explicitly, and stop for review where a phase requires authorial judgment.
- Do not commit, tag, publish, push, or perform broad migrations unless the active task explicitly authorizes those actions.
