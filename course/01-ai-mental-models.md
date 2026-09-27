# Module 1 — AI Mental Models

## Objective

Build a practical mental model of modern AI without beginning with neural-network mathematics.

## 1. Model, assistant and agent

A useful engineering distinction:

```text
MODEL
reasoning/generation engine

ASSISTANT
model + instructions + conversation interface + capabilities

AGENT
model + goal + instructions + context + tools + state + execution loop + verification
```

These are working definitions, not universal legal definitions.

### Systems analogy

A powerful processor is not the whole system.

A useful technical system also has inputs, routing, controls, state, outputs, feedback and an operator.

Agentic AI is similar: the model matters, but the surrounding environment determines what it can see, do, remember and verify.

## 2. Probabilistic reasoning vs deterministic software

Traditional code often follows explicit rules.

A model reasons probabilistically. That makes it strong at ambiguous semantic work, but it can also:

- infer the wrong intent;
- fabricate missing information;
- choose a poor path;
- produce an answer that sounds correct without evidence.

Good agent engineering combines model judgement with deterministic components where exactness or repeated mechanics justify them.

## 3. Instructions

Instructions define stable behaviour.

Examples:

- what the agent's job is;
- where truth lives;
- what files it should read;
- what tools it may use;
- what must be verified;
- when it should stop.

A one-off task prompt is not the same as durable project instructions.

## 4. Context

Context is what the model can use for the current decision.

Possible context:

- your current message;
- previous conversation;
- project instructions;
- files;
- retrieved documents;
- tool results;
- database records.

More context is not automatically better. Wrong, stale or duplicated context can make the system worse.

## 5. Tools

A model can reason about sending an email.

A tool is what actually allows the agent to send it.

Common tools include:

- filesystem;
- terminal;
- browser;
- email;
- calendar;
- GitHub;
- database;
- APIs;
- MCP servers.

## 6. State

State is information that survives beyond a single reasoning step.

Examples:

- files;
- Git commits;
- database rows;
- issue status;
- saved configuration;
- durable memory.

A chat response is not automatically durable state.

## 7. Hallucination and evidence

Treat fluent output as a proposal until the result is verified.

A useful reliability hierarchy:

```text
agent says it happened
< agent shows generated output
< agent inspects the actual target
< independent state/test proves the real outcome
```

## Practical exercise — map a familiar system

Create `work/01-system-map.md`.

Choose any system you already understand well, for example:

- a sales process;
- a recruitment workflow;
- an audio or video chain;
- a financial approval process;
- a software deployment;
- an industrial machine;
- a research workflow;
- a personal productivity system.

Map:

- inputs;
- processing/reasoning;
- instructions/settings;
- tools/actions;
- state;
- outputs;
- feedback/verification;
- failure points.

Then create the equivalent map for an AI agent.

## Teach-back

Without looking at this lesson, explain:

1. Why is a model not automatically an agent?
2. What is context?
3. What is state?
4. What makes a tool different from an instruction?
5. Why can a confident AI answer still require verification?

## Pass condition

Your AI coach should challenge unclear answers rather than simply congratulate you.
