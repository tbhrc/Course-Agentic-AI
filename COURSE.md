# Course Roadmap — Practical Agentic AI

## Outcome

By the end of this course, the learner should be able to build and operate a useful AI system rather than merely use a chatbot.

The course is intentionally **builder-first**. Coding theory, APIs and orchestration are introduced when a real project needs them.


## Your guided curriculum at a glance

**Start with no GitHub setup:** [Start your first lesson in an AI chat](START-HERE.md). It includes a self-contained Module 0 orientation and the first real exercise from [Module 1](course/01-ai-mental-models.md). The coach shows your current lesson and next step; full repository access is optional for this first session.

**Estimated study time:** plan for **50–75 active learning hours**, including the practical labs, capstone and final challenge. At **5 hours per week**, allow **10–15 weeks**; at **10 hours per week**, allow **5–8 weeks**. These are planning estimates, not measured completion times or deadlines. Prior demonstrated ability, setup problems and project scope can change them. The coach revises your remaining estimate from actual progress.

Use sessions of roughly **45–60 minutes**. A module can span several sessions. Start with the worked example, do the exercise, get feedback, and continue from the next unfinished step.

| Module / lesson | Estimated hours | What you will be able to do | Practical result |
|---|---:|---|---|
| [0. Welcome and course navigation](course/00-start-here.md) | 0.5–1 | Know the route and start the first lesson | Your course plan and next step |
| [1. AI mental models](course/01-ai-mental-models.md) | 2–3 | Explain model, assistant, agent, context and tools | A familiar-system map → AI-agent map |
| [2. Operate one agent](course/02-operating-one-agent.md) | 2–3 | Give an agent a clear task and verify its result | A tested Agent Brief |
| [3. Project instructions](course/03-project-instructions-and-agents-md.md) | 2–3 | Make useful behaviour survive beyond one chat | Your first tested AGENTS.md |
| [4. Files, Markdown, Git and GitHub](course/04-markdown-git-github.md) | 3–4 | Save, inspect and reverse project changes | A repository with commits and reviewed diffs |
| [5. Reusable Skills](course/05-skills.md) | 3–5 | Turn a proven workflow into reusable instructions | One Skill tested on representative tasks |
| [6. Codex fundamentals](course/06-codex-fundamentals.md) | 3–5 | Supervise a coding agent and review its changes | A repaired starter project with test evidence |
| [7. Coding literacy](course/07-coding-literacy.md) | 4–5 | Understand and debug the code your AI produces | A small code change you can explain and roll back |
| [8. APIs and tool calling](course/08-apis-and-tool-calling.md) | 3–5 | Connect an agent to a bounded action | A working API request and tool contract |
| [9. MCP connections](course/09-mcp.md) | 3–4 | Connect and inspect a reusable tool interface | A verified MCP connection |
| [10. Context, memory, state and data](course/10-context-memory-state-data.md) | 2–3 | Decide what persists and where truth lives | A source-of-truth and state design |
| [11. Debugging and evaluations](course/11-debugging-and-evals.md) | 3–4 | Find a failure’s cause and prevent recurrence | Representative tests and a verified repair |
| [12. Safety, permissions and human control](course/12-safety-permissions-human-control.md) | 2–3 | Handle secrets, untrusted inputs and consequential actions | Permission and prompt-injection checks |
| [13. Smallest useful architecture](course/13-smallest-useful-architecture.md) | 2–3 | Choose only the components a real problem needs | A justified architecture plan |
| [14. Capstone build](course/14-capstone.md) | 8–12 | Build and verify a useful end-to-end agent | Your working capstone and explanation |
| [15. Multi-agent systems](course/15-multi-agent-systems.md) | 2–3 | Judge whether a split improves a proven single agent | A one-agent vs multi-agent comparison |
| [16. Production thinking](course/16-production-thinking.md) | 2–3 | Plan monitoring, cost, recovery and release handling | A proportionate production-readiness plan |
| [Final graduation challenge](GRADUATION.md) | 2–3 | Solve and explain a fresh problem independently | A verified build and teach-back |

## How the coach guides you

Each session starts with **where you are → today’s outcome → estimated session time → what you will make → next lesson**. The coach then teaches a short concept and worked example before inviting you to try it. Feedback and useful skill checks happen during the exercises.

You do not need to complete a baseline questionnaire to unlock the course. Existing CVs, learner profiles, prior answers and work provide the starting context. New AI/Git/coding skills are established through practical work as those topics arise.

At a checkpoint, the coach records the current module, completed evidence, gaps, next action and remaining estimate in your own `work/progress.md`. If you already answered the old baseline questions, keep those answers and continue into the lessons; do not repeat the interview.


## Phase 1 — Control one agent

### [Module 0 — Start here](course/00-start-here.md)
**Goal:** see the curriculum, understand the study plan and begin learning.

You will:
- open your AI chat application and paste the [ready-to-use coaching prompt](START-HERE.md);
- see the course sequence, practical objectives and a realistic study estimate;
- learn what a model, assistant and agent do through a worked example;
- complete one short practical exercise before any account registration or software setup;
- receive a copyable CHECKPOINT if you want to resume in another chat.

**Artifact:** your first system map and the next learning step, held in the same chat or a copied checkpoint. Saving to a progress file is optional until file-writing is available. **GitHub is taught in Module 4 and not required to begin.**
**Next:** [Module 1 — AI mental models](course/01-ai-mental-models.md).

### [Module 1 — AI mental models](course/01-ai-mental-models.md)
**Goal:** understand the components without unnecessary mathematics.

Learn:
- model vs assistant vs agent;
- instruction vs prompt vs context;
- tool use;
- files and external knowledge;
- deterministic software vs probabilistic reasoning;
- hallucination and uncertainty;
- why verification matters.

**Artifact:** your own system diagram and explanations.

### [Module 2 — Operating one agent well](course/02-operating-one-agent.md)
**Goal:** move from casual prompting to controlled execution.

Learn:
- outcome definition;
- constraints;
- inputs;
- acceptance criteria;
- role and operating boundaries;
- context management;
- plan → act → inspect → verify.

**Artifact:** a reusable Agent Brief.

### [Module 3 — Project instructions and `AGENTS.md`](course/03-project-instructions-and-agents-md.md)
**Goal:** make behaviour survive beyond one chat.

Learn:
- project-level instructions;
- repository routers;
- stable rules vs task-specific instructions;
- progressive context loading;
- how bad instructions cause agent drift;
- how to test an instruction file.

**Artifact:** the learner writes and tests a first `AGENTS.md`.

---

## Phase 2 — Durable project work

### [Module 4 — Markdown, files, Git and GitHub](course/04-markdown-git-github.md)
**Goal:** make AI work durable, inspectable and reversible.

Learn:
- files/folders as agent context;
- Markdown;
- repository anatomy;
- commits;
- diffs;
- branches;
- issues;
- pull requests;
- source of truth;
- why Git is valuable even when AI writes the code.

**Build:** complete the [Git/GitHub lab](labs/04-git-github-lab.md), make deliberate changes and inspect the diff.

### [Module 5 — Skills](course/05-skills.md)
**Goal:** turn proven repeated behaviour into reusable capability.

Learn:
- what a Skill is;
- trigger conditions;
- minimal instruction design;
- references/resources;
- progressive loading;
- testing a Skill on representative work;
- when not to create a Skill.

**Build:** complete the [first Skill workshop](workshops/05-first-skill-workshop.md), test it using the [Skill testing playbook](playbooks/skill-testing-debugging.md), then complete the [Skill graduation exercise](course/05-skill-graduation.md).

Suggested starting domains should come from the learner's own work or interests. Examples include sales, recruitment, finance, software, research, creative production, engineering, operations or personal productivity.

---

## Phase 3 — Codex as a technical worker

### [Module 6 — Codex fundamentals](course/06-codex-fundamentals.md)
**Goal:** supervise an agent working directly on a repository.

Learn:
- giving Codex a bounded objective;
- asking Codex to inspect before changing;
- reading plans and diffs;
- creating/editing files;
- running commands;
- tests;
- debugging;
- review;
- rollback;
- repository instructions.

**Build:** complete the [Codex supervision lab](labs/06-codex-supervision-lab.md) against the included failing starter repository, then review the result with the [Codex supervision playbook](playbooks/codex-supervision.md).

### [Module 7 — Coding literacy for AI builders](course/07-coding-literacy.md)
**Goal:** learn enough code to supervise, debug and extend AI-built systems.

Focus:
- variables and data types;
- functions;
- conditions and loops;
- files;
- JSON;
- HTTP;
- errors and logs;
- packages/dependencies;
- environment variables;
- Python and/or TypeScript as practical implementation languages.

This is **not** a traditional programming course. Every coding concept must connect to a real agent/build task.

**Build:** complete the [coding literacy lab](labs/07-coding-literacy-lab.md) and the [diff/debug/rollback lab](labs/07-diff-debug-rollback.md).

---

## Phase 4 — Tools and connected agents

### [Module 8 — APIs and tool calling](course/08-apis-and-tool-calling.md)
**Goal:** understand how an agent moves from reasoning to action.

Learn:
- API basics;
- request/response;
- authentication concepts;
- JSON payloads;
- tool schemas;
- permissions;
- retries;
- failure handling;
- idempotency.

**Build:** complete the [first API lab](labs/08-first-api-lab.md), [tool-contract workshop](workshops/08-tool-contract-workshop.md), and [authentication/secrets practical](labs/08-auth-secrets-practical.md).

### [Module 9 — MCP](course/09-mcp.md)
**Goal:** understand reusable agent-to-system connectivity.

Learn:
- MCP mental model;
- tools vs resources;
- client/server relationship;
- discovery;
- permission boundaries;
- why MCP reduces custom integration work;
- when a direct API is simpler.

**Build:** complete the [first MCP connection lab](labs/09-first-mcp-connection.md) and use the [MCP inspection playbook](playbooks/mcp-inspection.md) plus [Tool/API/MCP decision playbook](playbooks/tool-api-mcp-decision.md).

---

## Phase 5 — Reliability

### [Module 10 — Context, memory, state and data](course/10-context-memory-state-data.md)
**Goal:** understand what persists and where truth lives.

Learn:
- conversation context;
- project files;
- durable memory;
- database state;
- external source-of-truth systems;
- stale context;
- provenance;
- retrieval;
- avoiding duplicated truth.

**Build:** complete the [source-of-truth and state-design workshop](workshops/10-source-of-truth-state-design.md).

### [Module 11 — Debugging and evaluation](course/11-debugging-and-evals.md)
**Goal:** troubleshoot agents systematically by isolating the failing layer.

Learn:
- reproduce the failure;
- isolate the layer;
- distinguish model failure from instruction failure, tool failure, data failure and environment failure;
- logs and traces;
- representative tests;
- eval cases;
- regressions;
- changing one variable at a time.

**Build:** complete the [deliberate failure/regression lab](labs/11-deliberate-failure-regression.md) and [representative eval exercise](labs/11-representative-eval.md), using the [fault-isolation playbook](playbooks/agent-fault-isolation.md).

### [Module 12 — Safety, permissions and human control](course/12-safety-permissions-human-control.md)
**Goal:** make useful systems without hiding risk.

Learn:
- secrets;
- least necessary access;
- reversible vs irreversible actions;
- approvals at consequential boundaries;
- untrusted input;
- prompt injection;
- audit evidence where it adds value;
- human-in-the-loop design.

**Build:** complete the [prompt-injection/untrusted-input lab](labs/12-prompt-injection-untrusted-input.md) and [permission/human-control lab](labs/12-permission-boundaries.md).

---

## Phase 6 — Build a real agent

### [Module 13 — Architecture the smallest useful system](course/13-smallest-useful-architecture.md)
**Goal:** choose the minimum architecture that solves a real problem.

Default order:

```text
capable model
→ clear instructions
→ useful files/context
→ reusable Skill
→ existing tool/API/MCP
→ small adapter/code only if needed
→ database/state only if needed
→ orchestration only if needed
```

**Build:** complete the [KISSS architecture lab](labs/13-kisss-architecture-lab.md) and use the [architecture proof template](templates/architecture-proof-template.md).

### [Module 14 — Capstone build](course/14-capstone.md)
Choose one real project.

Example capstone directions:

- business operations / customer / recruitment / finance;
- research and knowledge work;
- creative production / media;
- technical / engineering / maintenance;
- software / repository operations;
- personal operating workflows.

The capstone must solve a real problem and include:
- repository instructions;
- at least one Skill;
- Git history;
- Codex involvement;
- at least one tool/API/MCP where genuinely useful;
- explicit state/source-of-truth design;
- representative verification;
- a short architecture explanation the learner can give without AI assistance.

---

## Phase 7 — Advanced only after the foundation

### [Module 15 — Multi-agent systems](course/15-multi-agent-systems.md)
Only now introduce:
- specialist agents;
- handoffs;
- supervisor/router patterns;
- parallel work;
- shared state;
- conflict resolution;
- observability.

The key question is not “How many agents can I create?”

It is:

> Does separating this job into multiple agents produce a clearer, more reliable system than one well-instructed agent with the right tools?

### [Module 16 — Production thinking](course/16-production-thinking.md)
Learn:
- deployment;
- monitoring;
- cost;
- latency;
- rate limits;
- failure recovery;
- versions;
- backups;
- testing before releases;
- user experience.

---

# Graduation

Complete the full [Graduation Challenge](GRADUATION.md) and then follow the [30/60/90 Day Continuation Path](CONTINUATION.md).

# Graduation test

The learner receives a new practical problem.

Without being given the architecture, the learner must be able to:

1. clarify the outcome;
2. identify the source of truth;
3. create the repository/workspace;
4. write the controlling instructions;
5. organise context;
6. decide whether a Skill is justified;
7. use Codex to build what is missing;
8. connect required tools;
9. identify real permissions and risks;
10. test representative cases;
11. diagnose at least one failure;
12. explain the system clearly.

That is the graduation standard.
