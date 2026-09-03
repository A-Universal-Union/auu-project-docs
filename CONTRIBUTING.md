# Contributing to A Universal Union

Thank you for considering a contribution to A Universal Union (AUU).

AUU is an open proposal for shared civic infrastructure: tools that could help people and groups originate issues, deliberate, authorize limited action, delegate, act, record what happened, challenge failure, repair harm, and coordinate across communities without surrendering all local control.

The project is still conceptual, architectural, ethical, and research-oriented. No production platform exists. The documents define commitments, requirements, candidate approaches, and open questions; they do not prove that the proposed privacy, identity, voting, governance, moderation, accessibility, or federation designs can be built safely.

Contributions do not need to be technical, large, polished, or supportive. A question that exposes an ambiguity, a lived experience that reveals a false assumption, an accessibility concern, a source that weakens a claim, or an objection the current model cannot answer may be more valuable than a large implementation.

A GitHub account is not required. If someone invited you by email, you can reply with questions, review notes, proposed wording, or an attached file. You can also participate through the [AUU Discord](https://discord.gg/5dsAEVt4Zy). Contributors who already use GitHub may open issues or pull requests instead.

The most important requirement is good faith. Good faith does not require agreement, and it does not make a claim correct. It means engaging honestly, making criticism specific enough to examine, accepting challenge in return, and helping the project become clearer, safer, more accurate, more accountable, or more useful.

AUU cannot be a club for people who already agree.

## Start with the model

Begin with the root [Reader's Map](./README.md). It gives the shortest complete account of what AUU is, what it is not, how the civic cycle fits together, and which claims remain unproven.

You are not expected to read every document before asking a question. Read enough to locate your concern and determine whether the project has already attempted to address it.

| If your concern is mainly about… | Start with… |
| --- | --- |
| AUU's purpose or public case | [Mission Statement](./v5-documents/0.mission-statement.md) |
| Values, rights, consent, privacy, power, or ethical tensions | [Ethical Discussion](./v5-documents/1.ethical-discussion.md) |
| Required capabilities and their dependencies | [Feature Sets](./v5-documents/2.feature-sets.md) |
| Research order, evidence gates, prototypes, pilots, or adoption | [Research and Development Strategy](./v5-documents/3.research-and-development-strategy.md) |
| Membership, representation, institutions, authority, or federation | [Social Structures](./v5-documents/4.social-structures.md) |
| Sources, evidence status, standards, and unanswered research questions | [Research Index](./v5-documents/5.research.md) |
| Comprehension, accessibility, participant journeys, or interface requirements | [User Experience Requirements](./v5-documents/6.user-experience.md) |
| Existing civic tools, demonstrated maturity, or possible reuse | [Tool and Platform Comparison](./v5-documents/7.tool-comparison.md) |
| The project's controlled meaning of a term | [Glossary](./v5-documents/GLOSSARY.md) |

If the relevant treatment exists but seems wrong, contradictory, incomplete, unsafe, difficult to find, or difficult to understand, that is still a valid contribution. Point to the passage and explain where it fails.

## Ways to contribute

AUU needs more than software. Useful contributions include:

- asking a question that a first-time reader could reasonably ask;
- identifying ambiguity, contradiction, repetition, jargon, or a misleading assurance;
- documenting a lived failure, institutional process, or affected-person need;
- reviewing accessibility, cognitive load, translation, low-bandwidth access, and assisted participation;
- finding, classifying, verifying, or challenging evidence;
- supplying counterevidence or an important minority interpretation;
- writing scenarios, process models, requirements, threat cases, abuse cases, or test fixtures;
- examining privacy, identity, recovery, voting, coercion, moderation, records, or security;
- reviewing governance, law, rights, funding, conflicts of interest, operations, maintenance, exit, and remedy;
- comparing existing tools or testing whether an open-source component can be reused;
- improving prose, diagrams, examples, navigation, or controlled terminology;
- testing whether a representative reader can accurately explain a consequential process; and
- implementing a bounded artifact after its purpose, authority, dependencies, evidence needs, and test conditions are clear.

Critics, researchers, designers, developers, organizers, security reviewers, governance thinkers, legal analysts, ethicists, translators, accessibility specialists, community members, and people who would be affected by such systems are all relevant contributors.

Credentials may support a specialist claim, but they are not required to notice a real problem. Lived experience is evidence of an experience and its conditions; it is not automatically evidence that one explanation or universal remedy is correct. Both forms of knowledge should be stated with their limits.

## Choose the right channel

If someone invited you by email, replying to that message is the simplest route. You may write informally, paste completed review notes, suggest replacement wording, or attach a document. No knowledge of Git or GitHub is expected.

Use the [AUU Discord](https://discord.gg/5dsAEVt4Zy) for informal conversation, orientation, early ideas, and lower-friction contact. Discord is not the authoritative project record. A conclusion, objection, source, decision, or proposed rule that materially affects AUU should eventually be preserved in the repository, but the person who first raised it does not need to perform that transfer.

If emailed or Discord feedback should become part of the durable project record, AUU will ask whether it may be quoted, summarized, and attributed before transferring it. A contributor may ask to remain unnamed.

If you already use GitHub, use a **GitHub issue** to:

- ask a question;
- identify a problem, risk, contradiction, or missing case;
- propose a substantial or controversial change;
- request evidence or specialist review; or
- begin a discussion that should leave a durable public record.

Use a **pull request (PR)** when you have a concrete change to repository files and are comfortable using GitHub. Small, focused PRs are easier to understand and review. A large, ethically significant, architectural, or uncertain change should normally begin as an issue.

Public GitHub discussions and contributions are durable and searchable. Do not include private information, identifying details, protected records, credentials, secrets, or material you do not have permission to publish.

## If you want to use GitHub

GitHub is optional. You can participate by replying to an invitation or using Discord. If you want to create a public issue or submit a pull request yourself, you will need a free GitHub account, but you do not need to master Git before participating.

| Term | Plain meaning |
| --- | --- |
| Repository or repo | The project folder, including its files and history. |
| Issue | A public record for a question, problem, proposal, or discussion. |
| Pull request or PR | A proposed set of changes that can be reviewed before it enters the main project. |
| Fork | Your own GitHub copy of the repository. |
| Branch | A separate line of work used to keep one change isolated. |
| Commit | A saved change with a short explanation of what changed. |

If you can read a passage, notice a problem, and explain it, you can contribute. Send the observation by email reply or Discord, or open an issue if you use GitHub. For a small documentation correction, GitHub may also let you edit the file in the browser and propose the change directly.

## Before opening an issue or pull request

Make a reasonable effort to:

1. Read the relevant part of the Reader's Map and specialist document.
2. Search the repository and existing issues for the same concern.
3. Identify the text, assumption, process, or missing case involved.
4. Separate what you know from what you suspect or propose.
5. Remove private, dangerous, or unnecessary personal information.

This is not a test of whether you understand the whole project. Early questions and misunderstandings are useful evidence about the documents. The request is simply to engage with what is already present rather than assume the concern was never considered.

A weak issue says:

> The system does not consider criminal misuse.

A stronger issue says:

> The ethical and feature documents discuss harmful coordination, but I cannot determine how a protected pseudonym can be investigated without exposing unrelated participants. The current text may be missing the reviewer, evidence boundary, and appeal path.

The stronger version gives other people something concrete to inspect. You do not need to know the solution before raising the problem.

## Make the contribution reviewable

For a significant issue or PR, answer whichever of these questions apply:

1. **Location:** Which file, section, process, claim, or open question does this concern?
2. **Present model:** What do you understand the project to say now?
3. **Problem:** What appears wrong, missing, unsafe, contradictory, or difficult to understand?
4. **Consequence:** Who could be affected, and what could happen if the problem remains?
5. **Basis:** Is this an ethical argument, experience, source, test result, threat hypothesis, technical analysis, or design preference?
6. **Proposed response:** What should be clarified, researched, tested, changed, split, paused, or removed?
7. **Uncertainty:** What remains unknown, disputed, or outside your expertise?
8. **Conflicts:** Do you have a financial, professional, institutional, personal, or tool-related interest that may matter?

Not every contribution needs a complete proposal. A well-bounded unresolved question is better than a confident answer that hides its assumptions.

Pull requests should:

- explain what changed and why;
- avoid mixing unrelated changes;
- preserve links and controlled terminology;
- identify new claims that require evidence;
- state which checks were performed;
- update connected documents only when their meaning actually changes; and
- remain understandable without requiring reviewers to reconstruct a private conversation.

A PR is a proposal, not a demand. Review may change it substantially.

## Evidence and claim discipline

AUU distinguishes kinds of claims because they require different forms of support.

| Kind of claim | What a useful contribution should show |
| --- | --- |
| Ethical commitment | The value being defended, its boundary, the people affected, and the unresolved tension. |
| Functional requirement | What must be possible, why it matters, its dependencies, and how success or failure could be recognized. |
| Empirical or historical claim | A checked source, relevant context, limits, uncertainty, and known counterevidence. |
| Threat hypothesis | The actor, capability, target, possible harm, assumptions, and uncertainty. |
| Candidate approach | Why it may help, what it depends on, and what remains untested. |
| Demonstrated capability | The exact artifact and version, test or deployment, population and setting, result, limitations, and independent review where available. |
| Open question | What remains unresolved, why it blocks progress, and the next evidence, decision, or artifact needed. |

A citation does not transfer the authority of a standards body, paper, product, or institution into AUU. “Described,” “implemented,” “tested,” “worked in one setting,” and “safe for this civic use” are different claims.

Do not invent sources or cite material you have not checked. Verify that a source exists, says what you claim, and remains current. When evidence conflicts, represent the conflict. When the result is uncertain, say so. Negative results and invalidated assumptions are contributions.

Do not convert a requirement into a guarantee. Words such as *anonymous*, *secure*, *private*, *verifiable*, *unbiased*, *cannot*, *always*, and *everyone* require a defined observer, threat model, context, and evidence.

## Ethical, safety, and accessibility expectations

AUU concerns civic power, identity, privacy, collective decisions, institutional accountability, and potentially vulnerable participants. Contributions should therefore consider not only whether something works, but who gains power, who carries risk, who is absent, and how mistakes can be challenged and repaired.

The controlling ethical discussion is in [v5-documents/1.ethical-discussion.md](./v5-documents/1.ethical-discussion.md). In practical terms:

- Protect persons from unnecessary exposure.
- Make exercised power appropriately visible and reviewable.
- Do not confuse participation, membership, consent, representation, standing, delegation, authority, or recognition.
- Preserve a meaningful path to question, correct, challenge, appeal, revoke, exit, or repair.
- Do not treat a platform record as proof that the recorded claim is true or legitimate.
- Do not hide coercion, exclusion, or unreviewable discretion behind a friendly interface or community label.
- Do not use wealth, popularity, reputation, diagnosis, identity, or technical access as a substitute for civic worth.
- Do not describe automated summaries, classifications, warnings, or rankings as neutral facts.
- Do not publish harmful or identifying material merely because accountability requires a record.
- Remain open to serious criticism, including criticism of the project's foundational commitments.

Accessibility is part of legitimacy, not final-stage polish. Review should include people who vary in literacy, disability, language, civic knowledge, digital experience, device and connection quality, available time, institutional trust, and personal exposure risk. A process that experts can operate but intended participants cannot understand is not ready.

Proofreading can improve clarity. It cannot establish cryptographic feasibility, legal validity, coercion resistance, safe moderation, representative legitimacy, or an appropriate rights floor. Those claims require relevant specialists, affected people, explicit protocols, evidence, and independent challenge.

## How AI is used in AUU

A project about reviewable power should describe its own production process honestly.

AUU is human-directed and heavily AI-assisted. Joshua originated and directs the project. He supplies and develops its conceptual model, priorities, examples, source material, constraints, objections, and judgments. He decides what work is accepted, changed, rejected, published, or removed, and he is responsible for the repository in its current form.

ChatGPT and Codex have played a substantial role. They have been used to:

- explore and challenge concepts;
- produce substantial first drafts and replacement passages;
- restructure and compress documents;
- compare repository versions and recover prior decisions;
- audit consistency, terminology, claims, omissions, and unsafe assurances across files;
- locate and summarize possible sources for human checking;
- generate examples, tables, diagrams, and accessibility descriptions;
- propose research, product, governance, and technical structures;
- prepare repository-ready files, branches, commits, and patches; and
- run mechanical checks such as link validation, rendering, and format inspection.

Some published passages and artifacts began largely as AI-generated drafts. Describing this only as spelling, grammar, or editing assistance would understate the role. Describing AI as the project author, authority, or independent decision-maker would also be inaccurate.

ChatGPT and Codex did not originate AUU, possess civic standing, represent affected communities, verify a claim merely by stating it, or assume responsibility for the consequences of the design. They can produce confident errors, false synthesis, fabricated details, flattened disagreement, and prose that appears more settled than the evidence. Their output is material for judgment, not a source of legitimacy.

Joshua's acceptance of AI-assisted work establishes what the repository currently says. It does not establish that the claim is true, feasible, safe, democratic, or complete. Merge history is a record of project decisions, not proof of the model.

The current division of work also creates risks: dependence on one maintainer, dependence on commercial AI systems, uneven independent review, inherited model bias, and a volume of prose that can exceed available human scrutiny. Contributions that expose those risks, reconstruct the model independently, or provide qualified review are especially valuable.

## AI use in contributions

Contributors may use AI, but remain responsible for everything they submit.

Before submitting material AI helped shape:

- read and understand the result;
- verify important factual and source-dependent claims;
- test code and technical assertions at a level appropriate to the risk;
- revise errors, false confidence, repetition, and hidden assumptions;
- check that affected people and serious objections have not been synthesized away;
- avoid uploading private, confidential, identifying, or security-sensitive material without authorization; and
- be able to explain and defend the submitted result without appealing to the AI's authority.

Meaningful AI use should be disclosed in the issue or PR. Minor spelling, formatting, or autocomplete assistance does not need a formal declaration. If AI materially shaped the reasoning, wording, code, research process, diagrams, or tests, briefly state what it did and what you checked.

For example:

> **AI use:** ChatGPT helped draft sections 2–4 and compare terminology across the v5 documents. I reviewed and revised the text, checked the cited sources directly, and remain uncertain about the voting-security claim identified in the PR.

Do not use AI to fabricate citations or evidence, impersonate another person, conceal responsibility, mass-produce low-quality submissions, or convert private conversation into public material without permission.

The goal of disclosure is accountability, not stigma.

## Security-sensitive concerns

Architectural security concerns, threat-model gaps, privacy risks, and abuse scenarios can usually be discussed in public issues. Do not publicly post:

- usable exploit instructions against a live system;
- private keys, credentials, secrets, or sensitive configuration;
- personal information or identity mappings;
- protected evidence; or
- operational detail that would materially enable real harm.

AUU does not currently have a formal private vulnerability-reporting program. If a concern cannot be described safely in public, open an issue containing only a high-level, non-exploitable description and ask for a private reporting route. Do not send the sensitive details until an appropriate route and recipient are confirmed.

This is an early documentation project, not a deployed platform. A private reporting process, response ownership, and disclosure policy must be established before AUU handles production code, live credentials, sensitive civic data, or real participants.

## Review, disagreement, and project authority

AUU is presently directed and maintained primarily by Joshua, with extensive AI assistance and limited independent review. There is no claim that the current repository represents a community mandate, expert consensus, or implemented institution.

Not every contribution will be accepted. A proposal may be declined, postponed, split, or redirected because it is unsupported, unsafe, out of scope, too broad, difficult to maintain, premature for the current research stage, or inconsistent with a stated commitment. A merge means the contribution fits the project's present direction; it does not make the contribution true or permanently settled.

Review capacity is limited. Response times may vary, and some claims cannot responsibly be accepted until an appropriate specialist or affected-person review is available.

Strong disagreement is welcome. Personal attacks, harassment, threats, deliberate deception, spam, and unnecessary hostility are not. Good criticism identifies what is wrong, why it matters, and what evidence, clarification, test, or change may improve it. Criticism does not need to protect the project from discomfort.

Where a serious objection cannot be resolved, preserving the objection and the reason for the decision is preferable to manufacturing agreement.

## Basic pull-request flow

For a direct repository change:

1. Open an issue first if the change is large, controversial, uncertain, or ethically consequential.
2. Fork the repository and create a focused branch.
3. Make and check the change.
4. Commit it with a clear message.
5. Open a pull request explaining the purpose, scope, evidence, uncertainty, tests, and any meaningful AI use.
6. Respond to review and revise the proposal where appropriate.

Contributors remain responsible for the work they submit and for explaining it during review. If a contribution would require continuing maintenance, state who is expected to provide it.

## Rights and licensing

Submit only material you have the right to contribute. By submitting a contribution, you agree that it may be distributed under the repository's [license](./LICENSE). Identify third-party material and its license; do not copy material whose terms are incompatible or unknown.

## Final note

A Universal Union is about building civic systems that can be understood, challenged, corrected, and improved. Its contribution process should attempt the same.

Bring questions. Bring criticism. Bring corrections. Bring evidence. Bring lived experience. Bring proposals. Bring caution. Bring imagination.

But bring responsibility too.
