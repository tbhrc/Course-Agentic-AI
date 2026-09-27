# Module 2 — Operating One Agent Well

## Objective

Learn to control one capable agent before adding more agents, automation or code.

## The Agent Brief

Use this structure:

```text
OUTCOME
What must be true when the task is finished?

CONTEXT
What does the agent need to know?

INPUTS
What material does it have?

CONSTRAINTS
What boundaries must it respect?

TOOLS
What can it use?

ACCEPTANCE
What evidence proves success?

STOP
When should it stop rather than expanding the task?
```

## Example — weak request

> Help me organise our customer research.

Problems:

- no clear outcome;
- no source/location;
- no definition of organised;
- no acceptance check;
- no boundary on what may be changed or inferred.

## Example — controlled task

> Inspect the interview notes in `work/customer-research/`. Create `outputs/research-themes.md` with recurring themes, supporting source references and unresolved contradictions. Do not invent customer statements or merge conflicting evidence into a false consensus. Success means every reported theme points back to at least one source note and uncertain interpretations are labelled.

That is much closer to an executable agent task.

## Operating loop

```text
BRIEF
→ AGENT PLANS
→ AGENT ACTS
→ INSPECT
→ VERIFY
→ CORRECT
→ STOP
```

## Exercise 1 — rewrite vague tasks

Create `work/02-agent-briefs.md`.

Rewrite these as controlled Agent Briefs:

1. “Improve our sales process.”
2. “Research this problem.”
3. “Organise these files.”
4. “Review this code.”
5. One real task of your own.

Each must contain:

- outcome;
- context;
- inputs;
- constraints;
- tools;
- acceptance;
- stop condition.

## Exercise 2 — run one brief

Pick the smallest safe brief.

Before the agent acts, ask:

> Restate the acceptance criteria and tell me exactly how you will verify them. Do not start work yet.

Only then let it execute.

Afterwards ask:

> Show me the evidence for each acceptance criterion. Separate verified facts from assumptions.

## Fault-isolation lesson

When an agent fails, do not immediately change the model.

Ask which layer failed:

```text
Outcome unclear?
Instructions wrong?
Context missing?
Wrong source?
Tool failed?
Permission failed?
Environment failed?
Agent reasoning failed?
Verification missing?
```

This fault tree will become important later.

## Pass condition

You can turn an ambiguous request into an Agent Brief that another capable agent could execute without guessing the definition of success.
