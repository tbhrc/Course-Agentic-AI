# Methodology — How This Course Builds Agentic Systems

This course is not based on one framework or one vendor. It teaches a practical operating method derived from repeated real-world work with AI agents, GitHub, Skills, tools, automation and business systems.

The methodology is applied throughout the course rather than taught once and forgotten.

## 1. One capable agent before multi-agent complexity

Start with the smallest system that can solve the problem:

```text
capable model
→ clear instructions
→ useful context
→ one agent
→ tools only when needed
→ additional agents only when separation creates real value
```

Multiple agents do not automatically make a system more agentic, intelligent or reliable.

The first question is:

> Can one well-instructed capable agent with the right context and tools do this reliably?

If yes, start there.

---

## 2. Agent Brief before execution

Turn vague requests into an executable contract:

```text
OUTCOME
CONTEXT
INPUTS
CONSTRAINTS
TOOLS
ACCEPTANCE
STOP
```

This prevents the agent from guessing what “done” means.

The acceptance criteria matter more than decorative planning.

---

## 3. Project instructions before repeated prompting

If the same operating rule matters across sessions, move it out of chat history and into the project.

Use a small root instruction file such as `AGENTS.md` to answer:

- what this project is;
- what outcome it serves;
- where material belongs;
- which Skills or references own repeatable work;
- what must be verified;
- which boundaries matter;
- when the agent should stop.

The instruction file should route, not preload the entire project.

---

## 4. One canonical owner

For every important piece of durable meaning, decide where truth lives.

Avoid:

```text
same rule in AGENTS.md
+ same rule in a Skill
+ same rule in a README
+ same rule in a checklist
+ same rule in chat memory
```

Prefer:

```text
one canonical owner
→ other surfaces link or route to it
```

Duplicated truth eventually drifts.

---

## 5. GitHub as durable agent memory

GitHub is not only a code-hosting site.

For agentic work it can provide:

- durable instructions;
- inspectable files;
- version history;
- diffs;
- Issues for continuity;
- Pull Requests for review;
- tests;
- Skills;
- architecture records.

The practical Git loop is:

```text
inspect
→ change
→ inspect diff
→ verify
→ commit
```

A claim that a file changed is weaker than an inspected diff.

---

## 6. WF1 — lowest sufficient execution level

Do not turn every task into a project-management process.

Use the lowest sufficient execution level:

```text
direct execution
→ isolated branch/review when useful
→ additional coordination only when real risk or parallelism earns it
```

Issues, labels and PRs are tools for continuity and review. They are not permission ceremonies.

A good durable work record preserves only what future continuation needs.

---

## 7. SB1 — smart-agent-first Skills

A Skill is a reusable capability, not a giant prompt.

Use this structure:

```text
DISCOVERY
name + description

CONTROL PLANE
small SKILL.md

CONDITIONAL DEPTH
references / scripts / assets only when needed
```

### SB1 principles taught in this course

- reuse before creating;
- define one owned reusable job;
- keep the control plane small;
- use discovery metadata that describes positive owned actions and outcomes;
- progressively load detailed context;
- keep semantic judgement with the agent;
- add deterministic helpers for proven repeated mechanics;
- test representative real work;
- fix observed failure instead of theoretical failure;
- keep volatile public facts at their live authoritative source.

A Skill should improve execution enough to justify its maintenance.

---

## 8. Live truth vs durable HOW

Before copying information into project instructions or a Skill, classify it.

### Durable HOW

Keep locally:

- workflow;
- decision logic;
- invariants;
- naming conventions;
- acceptance criteria;
- stable internal operating rules.

### Volatile public truth

Verify live:

- current prices;
- product plans;
- model availability;
- provider limits;
- current regulations;
- software feature matrices.

Do not create a stale internal copy of information the authoritative owner can answer directly.

---

## 9. Lessons — learning must change future behaviour

A failure log is not learning by itself.

Use this loop:

```text
observe material failure or success
→ identify changed assumption
→ extract reusable rule
→ change the smallest correct owner
→ verify the old failure is harder to repeat
→ stop
```

Capture only lessons worth making another agent remember.

Do not create a diary of every mistake.

---

## 10. KA1 / KISSS — complexity must earn its place

Before adding another:

- file;
- folder;
- Skill;
- script;
- database;
- approval gate;
- agent;
- service;
- automation;
- dashboard;
- workflow;

test:

```text
DELETE
→ COLLAPSE
→ REUSE
→ DIRECT
→ only then ADD
```

The operating system must not become the work.

### The Wolf test

A process can look like control while actually adding friction.

Examples:

- mandatory approval with no real risk boundary;
- duplicate checklist nobody needs;
- an automation that blocks direct repair;
- a second source of truth;
- a connector hop that adds no capability;
- creating multiple agents where one would work.

Ask:

> What real failure becomes materially harder because this control exists?

If there is no clear answer, the control may be unnecessary.

---

## 11. Deterministic acceleration vs deterministic restriction

Code and automation are valuable when they:

- make repeated work faster;
- make exact transformations reliable;
- remove mechanical repetition;
- validate machine contracts;
- reduce known error.

They become harmful when they prevent a capable authorised agent from:

- inspecting;
- correcting;
- handling exceptions;
- finishing the real outcome;

without a genuine machine, safety, security or compliance reason.

Build helpers, not cages.

---

## 12. Verification is part of execution

Use evidence appropriate to the claim.

```text
agent says it happened
< output exists
< target was inspected
< representative test passes
< independent state proves the real outcome
```

Verify once with the smallest decisive evidence.

Do not turn verification into an endless ceremony.

---

## 13. Real boundaries, not friction theatre

Protect:

- secrets;
- credentials;
- destructive actions;
- irreversible changes;
- legal/compliance boundaries;
- untrusted input;
- material privacy boundaries;
- external commitments.

Do not add approval layers merely because a tool is powerful or a process feels more formal.

The objective is controlled capability, not artificial restriction.

---

## 14. Source-first architecture

When a system already owns the truth, use it.

Examples:

```text
CRM owns customer state
Git owns repository history
database owns application state
calendar owns scheduled events
email system owns sent/received messages
authoritative docs own current provider facts
```

An AI layer should retrieve and act on source truth rather than maintain unnecessary duplicate copies.

---

## 15. The course build loop

Every major capability in this course follows:

```text
UNDERSTAND
→ BUILD THE SMALLEST VERSION
→ USE IT
→ OBSERVE FAILURE
→ FIX THE SMALLEST CAUSE
→ VERIFY
→ PROMOTE REUSABLE LEARNING
```

This is the central operating habit the learner should carry beyond the course.

---

# Methodology mapping

| Course area | Main methodology applied |
|---|---|
| Agent fundamentals | one capable agent, Agent Brief, verification |
| AGENTS.md | progressive loading, canonical ownership |
| Git/GitHub | WF1, durable work, diffs, reversible change |
| Skills | SB1, smart-agent-first, live-source rule |
| Codex | inspect → change → diff → test → verify |
| APIs/MCP | source-first tools, real boundaries |
| State/data | canonical source of truth |
| Debugging | fault isolation, representative tests |
| Evals | observed behaviour over prose quality |
| Architecture | KA1/KISSS, smallest useful system |
| Multi-agent | separation only when it earns its complexity |
| Production | verification, recovery, real boundaries |
