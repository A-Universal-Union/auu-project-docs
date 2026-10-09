# Root Reader's Map Audit

| Previous | Contents | Next |
| :--- | :---: | ---: |
| [Source inventory](source-inventory.md) | [Review contents](README.md) | — |

## Recommendation

Preserve the root README as a complete first explanation of AUU. Its main opportunity for compression is repeated explanation across the stage table, eight questions, intersection example, authority list, and visibility list. Each has a useful function, but a new reader need not encounter every full treatment before finding a next step.

The proposed edit would keep a short civic-cycle explanation and the intersection example, retain every indispensable distinction, and link to specialist detail already present in the repository. The [functional diagram](../../docs/diagrams/auu-functional-model.svg) should stay inline; the [civic-agency diagnostic](../../docs/diagrams/from-public-opinion-to-civic-agency.svg) should stay a descriptive zoomable link. The detailed chapter inventory belongs in the future collection and document READMEs.

This audit covers the title/orientation block, all eleven H2 sections, and the five H3 distinctions in [the current root README](../../README.md) at baseline `ef4d1997eaac4f17d07731dd0c8e4c366a2d3487`. It proposes changes; it does not rewrite the root. Judgments about redundancy and cognitive load are editorial assessments, not findings from reader testing.

## Section disposition map

“Move with link” below describes a future revision with a working destination. Until that destination exists and is approved, the source stays in place. No entire section is recommended for removal without retaining its purpose or a directly discoverable fuller treatment.

| Existing section | Action | What must survive and where | Reason and qualification |
| :--- | :--- | :--- | :--- |
| Title and orientation, lines 1–7 | Condense | Proposed title `A Universal Union`; keep v5, conceptual status, external-review phase, and an immediate review link as metadata/orientation. | Stable project title and quick purpose help arrival; neither a version number nor a shorter introduction may imply an implemented platform. |
| [The shortest accurate description](../../README.md#the-shortest-accurate-description) | Condense | The Proposal: shared civic tools, the gap from concern to accountable action, institutional plurality, and no production system. The Problem: retain the diagnostic link. | Keep the plain explanation of what AUU proposes and is not. Add only a concise human foundation, leaving the extended philosophical case to the mission. |
| [The model in one line](../../README.md#the-model-in-one-line) | Retain | How It Works: all nine stages, the optional/nonlinear-workflow qualification, the inline functional diagram, and its conceptual-status caption. Shorten row descriptions if useful. | The diagram and sequence are the main model, not expendable duplication. Keep enough prose for readers who cannot use the image. |
| [Eight questions that expose a missing piece](../../README.md#eight-questions-that-expose-a-missing-piece) | Move with link | Preserve the diagnostic questions in a reviewed civic-infrastructure chapter or other approved explanation; retain a direct root link and a short statement about paths from issue to action and correction. | The questions repeat much of the stage table and example, but provide a useful reusable evaluation method. Do not simply delete them or relocate them into an unfinished scaffold. |
| [A short example](../../README.md#a-short-example) | Retain | How It Works: dangerous intersection, affected/absent people, different knowledge, bounded authorization, responsible implementer, follow-through, challenge, and revision. | This is the concrete explanation of how the model fits together. Its distinction between a neighborhood recommendation and municipal authority is indispensable. A shorter example must still show failed follow-through. |
| [Five distinctions to keep in mind](../../README.md#five-distinctions-to-keep-in-mind) | Condense | Principles and Safeguards: retain the five distinctions as short, explicit statements with direct fuller links. | The root must prevent the same misunderstandings that the rest of the documents guard against. The five subsection rows below specify what compression must preserve. |
| [1. A person is not one permanent public identity](../../README.md#1-a-person-is-not-one-permanent-public-identity) | Condense | Context-specific identities may reduce exposure; network, device, issuer, social, or behavioral links can still identify people. Link to [features §4.3](../../v5-documents/2.feature-sets.md#43-pseudonyms-and-presentation-identities). | Preserve the distinction and a concrete limitation. Avoid equating a pseudonym with guaranteed anonymity. |
| [2. Speech is not authority](../../README.md#2-speech-is-not-authority) | Retain | Personal opinion, member decision, and a claim to represent a neighborhood require different support. Link to [authority](../../v5-documents/GLOSSARY.md#authority). | One short example distinguishes speech from a mandate more clearly than a generic promise of transparency. |
| [3. Standing is not one permission](../../README.md#3-standing-is-not-one-permission) | Retain | A member may vote; an affected non-member may be heard or challenge; an expert may advise without deciding. Include people who cannot safely appear. Link to [ethics §4.1](../../v5-documents/1.ethical-discussion.md#41-membership-standing-advocacy-and-representation). | This protects absent people and prevents membership or credentials from becoming universal authority. |
| [4. Privacy is not the same as hidden power](../../README.md#4-privacy-is-not-the-same-as-hidden-power) | Condense | Protect personal information while identifying who can review exercised authority. Link to [ethics §2.3](../../v5-documents/1.ethical-discussion.md#23-privacy-for-persons-accountability-for-power). | Keep room for protected review, secret ballots, and private preparation. Public disclosure is not the only accountability mechanism. |
| [5. A record is not an interpretation](../../README.md#5-a-record-is-not-an-interpretation) | Retain | Summaries, rankings, clusters, and AI outputs remain contestable interpretations linked to underlying records. Link to [features §5.4](../../v5-documents/2.feature-sets.md#54-summaries-and-correction). | Without this, “collective wisdom” could imply that the system's synthesis replaces human judgment or dissent. |
| [Where authority can come from](../../README.md#where-authority-can-come-from) | Condense | Principles and Safeguards: name a few sources such as consent, member decision, delegation, and an external office or law. Retain source, scope, expiry/review, affected people, and challenge. Link to [social structures §5](../../v5-documents/4.social-structures.md#5-membership-consent-standing-and-authority) and [glossary: Legitimacy](../../v5-documents/GLOSSARY.md#legitimacy). | The full enumeration can be delegated, but a credential does not create authority and verified procedure does not establish justice or legitimacy. |
| [How records can be visible](../../README.md#how-records-can-be-visible) | Condense | Principles and Safeguards: name public, participant/member-visible, protected review, and private modes. Retain the harmful-evidence qualification and link to [social structures §7.1](../../v5-documents/4.social-structures.md#71-visibility-follows-function-and-risk). | A compact sentence or small list can replace repeated explanations. Keep the fact that evidence may need restricted handling; an audit is not a publication entitlement. |
| [Visual guides](../../README.md#visual-guides) | Condense | Keep diagnostic and functional diagram at their explanatory locations; offer [the diagram index](../../docs/diagrams/README.md) in Documents List and retain useful direct links to architecture/UX diagrams. | Remove repeated introductions if needed, while retaining access. A reader looking for a visual should not have to infer which prose document contains it. |
| [Reading order](../../README.md#reading-order) | Move with link | At an authorized cutover, the full current-document reading order moves to `v5/README.md`; root Documents List links to that collection, diagram index, review, contribution, and useful historical/planning entry points. | Preserve current legacy links until the collection README exists. Contextual shortcuts to mission or safeguards remain legitimate; the root need not reproduce the collection's full index. |
| [The present boundary](../../README.md#the-present-boundary) | Retain | Put no-production-system status in The Proposal; keep the evidence/testing limits and a path to challenge the institution in Principles and Safeguards. Link to [research strategy](../../v5-documents/3.research-and-development-strategy.md). | Moving the statement earlier can shorten repetition. Its meaning must be visible before readers mistake capabilities for demonstrated results. |
| [Review, contribute, and discuss](../../README.md#review-contribute-and-discuss) | Condense | Retain invitation-email reply, Discord, optional GitHub routes, no account requirement, criticism without endorsement, and consent before transferring private feedback into the public record. Link to [review](../../REVIEW.md) and [contributing](../../CONTRIBUTING.md). | The detailed channel table can be shorter because the route documents exist. Keep the invitation usable directly from the root and preserve the warning against sharing sensitive material. |

## Proposed root structure

The following is an annotated outline, not replacement prose. Heading names can change if first-reader testing finds a clearer arrangement. The optional 800–1,200-word range is a prompt to examine repetition, not a target that permits removing safeguards.

| Proposed section | Reader's question | Content and ownership |
| :--- | :--- | :--- |
| Title and metadata | What project is this, and how mature is it? | Stable project name, conceptual v5 status, and current review phase. |
| The Proposal | What is AUU asking people to consider? | Plain purpose, human dignity/agency and relational trust, collective learning and peaceful correction, limits on the claim, and an invitation to inspect. |
| The Problem | Why would these tools matter? | The gap between scattered concern and accountable collective action; descriptive link to the zoomable civic-agency diagnostic. Avoid adding unsupported numerical or universal claims. |
| How It Works | How could a concern become action and learning? | Nine-stage cycle, non-fixed-workflow qualification, embedded functional diagram and caption, compact stage explanation, intersection example. |
| Principles and Safeguards | Who has power, who is protected, and what can go wrong? | Five distinctions, bounded authority, rights that do not depend on majority popularity, affected nonparticipants, visibility modes, evidence limits, and links to detailed treatment. |
| Documents List | What should I read next? | Annotated entry points, delegating the complete v5 inventory to its collection README once approved. Retain valid standalone links during transition. |
| Review, Contribute, and Discuss | How can I help or object? | Low-friction review and contribution paths, account-optional participation, consent and privacy protections. |

The first screen should orient a reader to the proposal, maturity, and next step. That is a design intent to check in a rendered review, not an assertion about a tested viewport. The root should be useful when read alone; the mission should deepen the philosophical case; the collection README should explain how the documents relate.

## Diagram and example preservation

| Artifact | Disposition in the proposed structure | Verification needed at an approved edit |
| :--- | :--- | :--- |
| [Civic-agency diagnostic](../../docs/diagrams/from-public-opinion-to-civic-agency.svg) | Keep a descriptive zoomable link under The Problem; a second contextual link is acceptable when helpful. | Link opens the intended SVG; label makes its scope and need to zoom understandable. |
| [Functional model](../../docs/diagrams/auu-functional-model.svg) | Keep inline under How It Works, near the full civic cycle. | Alt text, caption, nine-stage vocabulary, diagram title/description, and accompanying prose remain accurate. |
| [Logical architecture](../../docs/diagrams/auu-logical-architecture.svg) | Keep its feature-document placement and diagram-index entry; a root shortcut is optional. | Root shortening must not move or redraw it incidentally. |
| [Issue experience](../../docs/diagrams/auu-issue-experience.svg) | Keep its UX-document placement and diagram-index entry; a root shortcut is optional. | Maintain descriptive access without forcing the diagram into the first-read narrative. |
| Dangerous-intersection example | Keep one complete concern-to-correction story in the root. | A reader can distinguish resident preference, authorized institutional action, actual completion, and a challenge to harmful results. |

## Decisions and comprehension review

Before a root rewrite, decide where the eight diagnostic questions will live and whether their wording should be preserved verbatim. The future mission's civic-infrastructure chapter is a plausible home, but it does not exist yet. Also decide how much of the stage table the example and diagram can carry without making the prose inaccessible.

For review of the eventual draft, use the existing [first-read questions](../../REVIEW.md#first-read-questions). Ask unfamiliar readers to explain AUU, identify who may bind others, name an unproven capability, distinguish privacy from unreviewable power, describe a challenge, and find a participation route without a GitHub account. Include skimming and nonvisual access. Confusion is evidence for revision, not proof that the reader failed. No reader study or rendered accessibility test was performed for this outline.

---

| Previous | Contents | Next |
| :--- | :---: | ---: |
| [Source inventory](source-inventory.md) | [Review contents](README.md) | — |
