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
