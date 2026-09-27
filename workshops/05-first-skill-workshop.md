# Workshop 05 — Build Your First Skill

## Objective

Build one small Skill from a repeated job you already understand well.

Do **not** choose a topic you are still learning. Existing expertise lets you judge whether the AI procedure is actually useful.

## Step 1 — Choose a repeated job

Choose something from your own domain.

Examples:

- turn meeting notes into a decision/action brief;
- prepare a candidate-screening summary;
- build a weekly sales account update;
- review a code change against project rules;
- prepare a research evidence brief;
- create a content-production preflight;
- convert technical fault notes into a vendor handover;
- prepare a financial review pack from defined inputs.

Write:

```text
The repeated job:
The input:
The useful output:
Why consistency matters:
```

## Step 2 — Test the task without a Skill

Give your AI one representative example using a normal prompt.

Observe:

- What did it do well?
- What did it guess?
- What did it omit?
- Which instructions did you add?
- Which corrections would you probably repeat next time?

Create `work/05-first-skill-observations.md`.

## Step 3 — Extract reusable rules

Identify 3–8 rules that should survive future sessions.

Examples:

```text
- Preserve source facts exactly.
- Separate evidence from inference.
- Mark missing inputs instead of inventing them.
- Keep the output decision-ready rather than dumping all source text.
```

If you have 40 rules on your first attempt, you are probably writing a manual rather than a small Skill.

## Step 4 — Define discovery

Write three requests that **should** trigger the Skill.

Then write two related requests that **should not** trigger it.

This is your first discovery test.

## Step 5 — Name the Skill

Choose a specific lower-case hyphenated name.

Good:

```text
meeting-decision-brief
candidate-screening-summary
maintenance-vendor-handover
```

Bad:

```text
my-ai-helper
do-everything
general-assistant
```

## Step 6 — Create the smallest folder

Create:

```text
work/my-first-skill/
└── SKILL.md
```

Add `references/`, `scripts/` or `assets/` only when the real job proves they are needed.

## Step 7 — Write frontmatter

```yaml
---
name: <your-name>
description: <what it owns + realistic trigger wording>
---
```

Ask:

> Would a capable AI know from this description when to select the Skill?

## Step 8 — Write the control plane

```markdown
# <Human-readable name>

**Fast links:** Add only if optional references are genuinely useful.

**Execution spine:** request → inspect evidence → core decisions → verify → output

## Rules

- ...

## Output

Describe only what must be consistent.

## Acceptance

- ...
```

## Step 9 — Test representative execution

Use the same representative input from Step 2.

Compare:

```text
WITHOUT SKILL
vs
WITH SKILL
```

Did the Skill materially improve the real outcome?

If not, identify the smallest missing rule rather than adding more architecture.

## Step 10 — Test a neighboring request

Use one of your non-trigger examples.

If discovery is too broad, fix the description.

## Step 11 — Failure-driven revision

Choose one observed weakness and modify only what is needed.

Examples:

- discovery too broad → fix description;
- agent invents evidence → add evidence rule;
- output inconsistent → define output shape;
- detailed stable domain knowledge needed → add one reference;
- repeated exact mechanic fails → consider a helper/script.

## Step 12 — Inspect and commit

Before committing:

```bash
git status
git diff
```

Explain every material change.

Then commit with a meaningful message.

## Workshop completion

Create `work/05-first-skill-result.md`.

Answer:

1. What repeated job does your Skill own?
2. What requests trigger it?
3. Which requests should not trigger it?
4. Which rule produced the biggest improvement?
5. What did you deliberately leave out?
6. Does it need deterministic code? Why?
7. What failure did you observe and correct?
8. What evidence proves the Skill improves the original one-off workflow?

Your first Skill does not need to be impressive. It needs to be **useful, understandable and proven**.
