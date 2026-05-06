# Prototype Frame

## Prototype Purpose

The prototype should demonstrate formation-based command over a multi-agent task. It does not need to prove a new agent algorithm. It needs to make the interaction model observable, usable, and evaluable.

## Primary Interface Concepts

### Formation Switcher

A control surface where the user chooses the collaboration mode of the agent team.

Candidate formations:

- Scout: agents explore options and gather evidence.
- Debate: agents argue alternatives and expose tradeoffs.
- Execute: agents divide work and produce artifacts.
- Audit: agents inspect outputs for risks, errors, and missing evidence.
- Synthesize: agents merge findings into a concise decision or deliverable.

### Task Map

A visual representation of task state, showing what has been explored, what is active, and what remains unresolved.

### Agent State Panel

A compact view of each agent's role, current action, confidence, blockers, and dependencies.

### Intervention Controls

Ways for the user to pause, redirect, assign constraints, merge branches of work, or force an audit.

### Replay / Rationale View

A way to inspect how the formation changed, what decisions were made, and why.

## Initial Scenario Candidates

1. Research assistant scenario: agents gather literature, debate framing, synthesize a research gap, and audit citations.
2. Product planning scenario: agents explore users, constraints, features, risks, and launch plan.
3. Coding project scenario: agents inspect code, propose implementation, execute changes, and review risk.

## Most Suitable First Scenario

Research assistant scenario, because it directly matches this thesis project and makes the user's real workflow part of the prototype grounding.
