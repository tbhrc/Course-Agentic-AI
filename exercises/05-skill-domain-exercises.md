# Skill Exercises — Cross-Domain Practice

Choose at least **two** exercises from different domains.

The objective is to learn how domain expertise becomes reusable AI operating behaviour.

## Exercise A — Meeting Decision Brief

Build a Skill that turns meeting notes/transcripts into:

- decisions;
- owners;
- actions;
- deadlines when explicitly stated;
- unresolved questions;
- source references.

Failure to prevent: inventing commitments that were not actually made.

## Exercise B — Candidate Screening Summary

Build a Skill that evaluates a candidate against explicit job criteria.

Requirements:

- distinguish evidence from inference;
- show missing criteria;
- preserve quantitative requirements exactly;
- do not invent experience from job titles.

Failure to prevent: confident recommendation without supporting evidence.

## Exercise C — Sales Account Update

Build a Skill that turns CRM/email/meeting evidence into a concise account update.

Output:

- current state;
- recent meaningful change;
- open commitments;
- risks/blockers;
- next action.

Failure to prevent: duplicated or stale account truth.

## Exercise D — Research Evidence Brief

Build a Skill that synthesizes multiple sources into:

- supported findings;
- source references;
- contradictions;
- uncertainty;
- implications.

Failure to prevent: flattening disagreement into fake consensus.

## Exercise E — Code Change Review

Build a Skill that reviews a Git diff against project instructions and acceptance criteria.

Failure to prevent: commenting on general code style while missing the requested behavioural change.

## Exercise F — Creative Production Preflight

Use audio, video, design, content or another creative workflow.

The Skill should identify:

- confirmed inputs;
- missing assets;
- technical constraints;
- approval requirements;
- preflight checks.

Failure to prevent: inventing missing production specifications.

## Exercise G — Technical / Maintenance Handover

Turn raw observations into a vendor or engineering escalation.

Separate:

```text
OBSERVATION
MEASUREMENT
ACTION TAKEN
RESULT
HYPOTHESIS
MISSING EVIDENCE
QUESTION
```

Failure to prevent: converting a hypothesis into a confirmed cause.

## Exercise H — Finance Review Pack

Use defined financial inputs to produce a review summary.

Requirements:

- preserve numeric values;
- show source period;
- distinguish actual, budget, forecast and assumption;
- flag missing data.

Failure to prevent: mixing periods or presenting assumptions as actuals.

# Comparative exercise

After two Skills, create `work/05-skill-comparison.md`.

Answer:

1. Which rules are truly domain-specific?
2. Which are generic agent behaviour and should be removed?
3. Did either Skill need a reference?
4. Did either need deterministic code?
5. Which had clearer discovery metadata?
6. Which was easier to test?
7. Which saves the most repeated explanation?

## Advanced challenge

Ask your AI:

> Try to merge these two Skills into one generic assistant Skill.

Evaluate what is lost.

Often the merged Skill becomes harder to discover, broader than necessary and less precise. Explain whether that happened and why.
