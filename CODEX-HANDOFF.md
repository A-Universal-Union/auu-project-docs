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
- **README order:** `# <title>`; `## Thesis`; `## Documents List`. The Documents List must be a Markdown table that links to chapters and nested subsections, with a purpose/thesis for each entry.
- **Navigation:** each chapter has Previous / Contents / Next tables at its top and bottom, with left/center/right aligned columns. First/last chapters show no link for the missing neighbor. Reading order comes from the README.
- **Version at the document-directory level.** Keep chapter filenames stable, without per-chapter version numbers or renaming on subsequent revisions. Git provides file history.
- **Target architecture:** directories inside `v5/` (starting with `v5/mission-statement/`). The repository presently uses `v5-documents/`; this requires a deliberate, link-safe transition, not an unannounced bulk rename.

Read the root [`AGENTS.md`](AGENTS.md) and [`DOCUMENTATION-CONVENTIONS.md`](DOCUMENTATION-CONVENTIONS.md) first if installed. Those files are part of this handoff package.

## 2. Verify current source state

Inspect before changing anything; if the repository has advanced beyond this handoff, adapt to the actual files and report differences.

Known current repository (as checked on 2026-10-09):

- `README.md` — v5 Reader's Map; the civic cycle is **originate → deliberate → authorize → delegate → act → record → challenge → repair → federate**.
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
2. Enumerate inbound links to the mission and other `v5-documents/` paths; identify potential navigation breakage.
3. Produce the historical argument inventory, prioritizing significant missing/weakened arguments, not superficial wording differences.
4. Note any conflicts between historical aspirations and v5's clearer rights, safety, and evidence standards.

**Phase B — Prepare documentation architecture for review**

1. Propose `v5/mission-statement/README.md` using `# Title`, `## Thesis`, and `## Documents List` with annotated chapter and actual subsection links.
2. Specify the chapter split, top/bottom navigation, `VERSION.md`, and `CHANGELOG.md` according to the conventions document.
3. Establish a **migration/link plan** for the transition from `v5-documents/` to `v5/`, including a controlled cutover and how old inbound links remain meaningful. Other documents need not migrate immediately.
4. If asked to implement scaffolding in this run, you may create the new draft directory, README, versions, changelog and chapter outline; **keep the current mission canonical until a complete replacement is approved**. Preserve the existing mission's source content and avoid publishing incomplete placeholder chapters as a finished document.
5. Do not automatically copy generated speculative text into specialist documents. Record suggested later cross-document edits separately.

**STOP AND REPORT.** Deliver the idea inventory, outline/README, migration proposal, open editorial issues, and exact files changed. The full manuscript is a separately authorized phase.

## 6. Future phases — require a separate instruction

- Draft a sustained six-chapter mission, using historical text thoughtfully rather than concatenating old versions. Aim for as much length as the argument deserves; ~25 pages is acceptable.
- Test the text adversarially for authoritarian implications, exclusion of isolated people, unsupported claims about political evolution, violations of minority rights, and unearned privacy/security assurances.
- At an approved publication boundary, designate the new directory as canonical, update inbound links, keep old paths as clear historical pointers where feasible, synchronize changelogs, and optionally tag a published revision.
- Migrate or decompose other v5 documents in later, individually scoped changes, avoiding unnecessary simultaneous rewrites.

## 7. Acceptance checks for the initial milestone

- The author can identify every chapter's thesis from the README table without opening its file.
- The six-chapter order is coherent and existing mission prose is preserved, not silently replaced.
- Faith in humanity is clear as a value, and social-trust implementations remain testable proposals.
- The inventory accounts for foundational lost/altered arguments and major v5 safeguards, with verified source references.
- Versioning occurs once per document directory, not independently per chapter.
- All written relative links resolve; all existing inbound links are accounted for; no published reader is silently directed to incomplete scaffolding.
- Any chapter already populated contains navigation at both ends; first/last boundary behavior is correct.
- The report states what was inspected, changed, deferred, unverified, and what approval is needed next.
- No release, push, broad rename, or substantive philosophical rewrite occurs without a separate instruction.
