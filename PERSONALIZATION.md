# Personalized Learner Tracks

`Course-Agentic-AI` is the canonical general curriculum.

A personalized learner repository may adapt the course to a person's background without becoming a second source of truth for the reusable curriculum.

## Layering model

```text
Course-Agentic-AI
canonical curriculum + methodology
        ↓
learner repository
personal background + pace + examples + domain projects + personal work
```

## Keep canonical

These normally belong in the general course:

- core learning outcomes;
- general lesson structure;
- methodology;
- Git/GitHub operating patterns;
- Skill-building principles;
- Codex/coding fundamentals;
- APIs/MCP fundamentals;
- debugging/evaluation methods;
- architecture principles;
- generic labs, playbooks and templates.

## Personalize

These normally belong in the learner track:

- learner background;
- current technical level;
- preferred analogies;
- domain-specific exercises;
- personal project choices;
- pace;
- skipped/proven prerequisites;
- personal outputs and reflections;
- capstone specialization.

## Learner-profile pattern

When a learner track has meaningful prior evidence, keep one durable learner-profile file as the local owner for personalization. Use [templates/learner-profile.md](templates/learner-profile.md) as a starting point.

Keep these evidence types distinct:

```text
VERIFIED EVIDENCE
certificates, portfolio, demonstrated work, inspected artifacts

LEARNER-DECLARED CONTEXT
self-reported background, preferences, interests, current goals

DEMONSTRATED CURRENT CAPABILITY
what the learner can actually perform and explain now

UNKNOWN / UNPROVEN
skills that must still be tested
```

Do not infer a current skill merely because the learner has adjacent experience. A strong engineer, analyst, designer or operator may still be new to Git, coding, APIs, MCP or Agentic AI.

A learner profile guides teaching; it does not replace the baseline.

If the learner profile already contains known background, Module 0 should **confirm/correct it and test the unknowns** rather than making the learner restate the same history.

## Privacy

A personalized learner repository may be public.

Do not store unnecessary sensitive identifiers or private records merely to improve personalization.

Examples that normally do **not** belong in a public learner repository:

- government identity/passport numbers;
- employee/account numbers;
- passwords or credentials;
- private contact details;
- medical information;
- unrelated personal records.

Keep only the minimum evidence needed to improve coaching decisions.

## Personalization as a bridge, not a crutch

Use familiar expertise to accelerate learning:

```text
known domain concept
→ map to new Agentic AI concept
→ learner operates it
→ verify understanding
→ gradually remove the analogy
→ transfer the method to a different problem
```

Do not force every lesson into the same domain analogy.

A strong personalized course should eventually prove that the learner can transfer the method beyond the exact examples used during teaching.

## Promotion rule

If a learner track discovers a reusable improvement:

```text
personal track observation
→ ask whether it helps learners generally
→ if yes, improve Course-Agentic-AI
→ keep only learner-specific adaptation downstream
```

Do not maintain two competing versions of a general lesson.

## Downstream rule

When the canonical course improves, pull/adapt the relevant change into the learner track only when it benefits that learner.

Do not copy changes mechanically merely to keep every file identical.

## No synchronization machinery by default

Do not build an automated synchronization service until repeated manual reconciliation proves a real need.

The initial operating method is deliberately simple:

```text
build canonical
→ verify
→ adapt relevant delta to learner track
→ verify learner experience
```

## Example

[Course-Andre-Venter](https://github.com/tbhrc/Course-Andre-Venter) is a personalized learner track.

Its technical examples, pacing and capstone choices may differ from the canonical course while its reusable Agentic AI learning principles remain aligned.
