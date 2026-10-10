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
- For the documentation architecture and navigation standard, follow [`docs/DOCUMENTATION-CONVENTIONS.md`](docs/DOCUMENTATION-CONVENTIONS.md) when that file is present.
- Treat the root `README.md` (Reader's Map), `CONTRIBUTING.md`, `REVIEW.md`, the controlled glossary, ethical discussion, research documents, and current mission as mutually connected sources. Maintain their conceptual distinctions.
- When reconstructing the mission, consider the original PDF, v3.x drafts, v4, the early June 2026 v5 mission, the human-centered August revision, and the available salvage corpus. Trace consequential ideas to actual source text or history; do not invent historical positions or citations.
- Where documents disagree, report the difference instead of silently declaring one interpretation correct. Distinguish the current model from past proposals and future recommendations.

## Documentation architecture

- **README-first discovery:** A reader should enter through the repository's root `README.md` and reach relevant material through coherent directory READMEs. The root is AUU's public introduction, compact conceptual overview, and navigation gateway—not merely a file index. `v5/README.md` organizes the current document collection; each authored document's `README.md` presents its own thesis and chapters.
- **Index responsibility stops at the next README:** A parent's `## Documents List` normally links to immediate child README entry points and delegates detailed chapter/subsection inventories to those children. This is an **indexing rule, not a prohibition on explanation or direct links**: retain contextual links to significant chapters, examples, diagrams, review routes, and other useful destinations when they spare readers unnecessary navigation.
- **Protect the root Reader's Map:** Preserve, in concise form, its explanation of what AUU proposes and is not; conceptual/development status; nine-stage civic cycle and embedded functional-model diagram; linked, zoomable civic-agency diagnostic; concrete dangerous-intersection example; indispensable distinctions about identity, authority, standing, privacy and records; limits of current capabilities; and routes to documents, review and contribution. It must be independently understandable to a newcomer even if they open no other file. Do not replace it with a generic README template or shift its entire conceptual explanation into the mission statement.
- **Edit the root for progressive disclosure:** Aim for a scannable first screen and an economical overview, not maximal detail. The approximately 800–1,200-word range discussed for the root README is a **provisional editorial target, not a hard limit or acceptance criterion**. Condense or delegate specialist explanations only when the essential distinction remains clear and there is a reliable link to fuller treatment. Assess redundancy and first-reader comprehension rather than applying arbitrary word-count cuts; retain the strongest diagrams and example.
- A **document** may consist of a directory. Its `README.md` is the GitHub-rendered entry point; individual Markdown files are chapters. Collection and reference directories may also have READMEs without being independently versioned authored documents.
- **Common README shape, not one rigid template:** Begin with `# Title`, then meaningful orientation (`## Thesis` for an argumentative document; `## The Proposal`, `## Overview`, `## Purpose`, `## Model`, or similar for other purposes). Use an annotated `## Documents List` table for navigable documents or chapters. A document README may list significant chapter subsections; a parent collection README should not reproduce them. The root README may require substantial narrative and multiple visuals before its index, while `v5/README.md` should be a lean collection map rather than a duplicate Reader's Map.
- **Diagrams are first-class explanatory content.** Preserve and use the existing civic-agency diagnostic, functional model, logical architecture, issue-experience diagram, and their `docs/diagrams/README.md` index. Embed a readable diagram near the argument it explains; link oversized/zoomable diagrams rather than forcing them inline. Keep descriptive link text/alt text, conceptual-status qualifications, and relative paths correct when moving Markdown files. Do not reduce useful diagram-led READMEs to generic Thesis/Contents templates.
- Provide **Previous | Contents | Next** navigation tables immediately under each chapter title and at the bottom of each chapter. Align columns left, center, and right using GitHub Flavored Markdown (`:---`, `:---:`, `---:`). Contents points to the containing document's `README.md`; previous/next follow its reading order. Leave unavailable first/last links unlinked. Directory READMEs are navigation hubs and do not need chapter-style previous/next tables.
- Each authored document directory maintains one `VERSION.md` and one `CHANGELOG.md`. **Version the document, not each chapter or every parent index.** Git records individual file edits. Do not create version-numbered copies or rename chapter files with every release.
- Use meaningful, stable chapter filenames. For new mission chapters, use two-digit reading-order prefixes (`01-` through `06-`) so files sort in reading order, as requested by the author on 2026-10-10. Keep the document README and Previous / Contents / Next navigation consistent with that order. Preserve filenames across ordinary revisions; any later reorder or rename requires deliberate link updates. Split chapters at substantive conceptual boundaries, not merely to make files small.
- Use relative links and check them, including GitHub heading anchors. Keep the root Reader's Map, diagram references, contributor and review links functional when paths change. A directory migration is a deliberate one-time operation, never an incidental side effect of a prose edit.
- For complete specifications and Markdown examples, follow [`docs/DOCUMENTATION-CONVENTIONS.md`](docs/DOCUMENTATION-CONVENTIONS.md) when that file is present.

## Writing and evidence discipline

- Preserve the current human-centered invitation as the mission's approachable entry point; restore earlier philosophical and civilizational arguments around it instead of replacing it with a technical overview.
- Prefer a sustained, readable argument over repetitive lists of requirements. The mission may be long where length earns its place. Supporting documents should retain their specialist requirements, evidence and safeguards.
- Distinguish ethical principles, empirical assertions, open questions, candidate designs, and demonstrated capabilities. Do not promote hypothetical identity, voting, privacy, safety, accessibility, or governance properties into guarantees.
- Do not equate correct procedure with just outcomes, consensus with wisdom, credentials with authority, or membership with standing. Respect protected dissent, affected nonparticipants, rights floors, transparency of authority, and privacy of persons.
- Avoid unsupported universals; cite sources accurately when making specific empirical claims. Do not invent sources, contributors, public support, tests, or a collective mandate. Do not imply AUU has an operational system or external endorsement.
- Keep the author's first-person convictions distinct from statements that would imply an existing organization speaks unanimously. AI assistance and uncertainty should not be disguised.
- Preserve controlled terminology or explicitly propose changes to the glossary. Keep accessibility, reasonable cognitive load, and nontechnical readers in mind.

### Authorial voice and agency

- The author's requested voice is **serious, empathetic, intelligent, analytical, and fanatical**. Give that intensity a clear object: human dignity, agency, and the possibility of improvement. Arguments and mechanisms remain open to criticism and revision.
- Let conviction appear in direct judgments, concrete consequences, and attention to what people experience. Allow the prose to express care, frustration, and determination where the argument earns them. A transition should carry meaning and personality, rather than merely announce the next editorial step.
- Preserve the distinction between **feeling powerless** and **being powerless**. Describe the experience of helplessness without automatically declaring an absence of capacity to judge, cooperate, resist, or change conditions. Equally, do not assume effective power is available to everyone or that confidence alone can overcome material barriers. Identify actual restrictions precisely when the evidence supports them.
- The author's wording correction provides a calibration example: “AUU begins with faith in humanity. Human beings deserve more than increasingly efficient ways to feel powerless.” Here, **feel** leaves the possibility of agency open while taking the experience seriously. Carry that distinction into future writing; do not mechanically replace factual descriptions of power with descriptions of feeling.
- When humor serves the argument, use **dry absurdism and dark humor**. Let institutional contradictions, exercises of power, and the project's own pretensions supply the target. Keep empathy for people bearing the consequences, and let serious passages stand without an obligatory joke.

## Change discipline and stopping boundaries

- Make focused, reviewable changes. Before substantial edits, state the intended scope and identify affected documents and links.
- For significant removals, reversals, reinterpretations, or migrations, provide a provenance/change map explaining what was preserved, altered, or omitted and why. For root README shortening, map each existing section to **retain / condense / move with direct link / remove with reason** before editing. Do not delete hard-won arguments as an accidental consequence of compression.
- Keep `VERSION.md` and `CHANGELOG.md` consistent with **meaningful reviewable states**; ordinary commits need not change a document's version.
- Verify local relative links, headings, navigation order, expected files, and any automated checks available. Report which checks were actually run; do not claim independent review.
- **Stop at the requested boundary.** A request for audit or plan is not authorization to rewrite or publish. A request for scaffolding is not authorization to complete the philosophical manuscript, migrate unrelated documents, tag a release, or push changes. Surface unresolved editorial or architectural choices explicitly, and stop for review where a phase requires authorial judgment.
- Do not commit, tag, publish, push, or perform broad migrations unless the active task explicitly authorizes those actions.

## Git commit attribution

- Commit only when the active task explicitly authorizes committing; this section does not grant permission to commit, tag, or push.
- Preserve the repository's configured Git author and committer identity unless the user explicitly instructs otherwise. Do not put multiple email addresses in `user.email` or alter Git configuration merely to acknowledge AI involvement.
- When Codex has substantively contributed to an authorized commit, append the following trailer to the **end** of the commit message, separated from the message body by a blank line:

  ```text
  Co-authored-by: Codex <codex@openai.com>
  ```

- This acknowledges Codex alongside the configured human author; it does not replace the author or committer fields. Include the trailer **once per applicable commit**, not once per file.
- Do not use this trailer for changes Codex did not substantively contribute to. Preserve other required trailers and do not claim human contributions or independent review that did not occur.
