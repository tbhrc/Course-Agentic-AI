# First-session regression: no GitHub or repository access

## Case A — First lesson with no technical setup

Given: a learner has access to a normal chat app but has **no GitHub account, connector, local files or repository-reading capability**.

Action: open the public [start page](../START-HERE.md), copy the prompt and send it.

Pass:
- AI presents itself as *David AI Coach*, an AI tutor, not David personally.
- It provides the real course order (17 modules) and realistic total study estimate.
- It starts Module 1 teaching **without asking to connect, sign up, upload, browse files or copy AGENTS.md**.
- It explains model, assistant and agent, shows a worked example and gives **one** learner exercise.
- It does not claim to have read files or stored progress it cannot access.

## Case B — No repository retrieval

Given: the AI explicitly cannot open GitHub URLs. Action: send the same start prompt.

Pass: it teaches the first lesson **from the self-contained prompt** rather than refusing, claiming false retrieval or asking for file uploads. Later modules can use the detailed curriculum when real file access is available.

## Case C — Returning learner

Given: the learner types CHECKPOINT in an ongoing chat, then pastes the result in a new conversation and says "Continue my course."

Pass: the coach continues at the actual stated next step and does not restart Module 0 or repeat a baseline interview. It does not falsely claim cross-chat persistence.

## Case D — Technical modules stay available

Modules 4 and 6 still teach GitHub and coding setup when genuinely needed. The course retains its labs, repository project work and graduation criteria.

## Documentation checks

- Every main start route points directly to START-HERE.md, including README, SETUP, Module 0 and the coach prompt.
- The first-session prompt contains the curriculum, Module 1 definitions, a worked-example directive, a learner exercise, a truthful persistence/checkpoint path and no external access requirement.
- Public source remains public; no learner credentials or personal progress are committed.
- These are deterministic documentation checks; they are **not** a claim that a real external student's chat session has been completed. Confirm the real use case with the learner before declaring user-onboarding acceptance.
