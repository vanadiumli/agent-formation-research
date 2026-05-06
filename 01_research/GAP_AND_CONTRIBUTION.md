# Research Gap and Contribution

## Research Gap

Current multi-agent systems are often powerful at the backend level but difficult to understand and command at the user interface level. Users may see multiple agents chatting, but they often lack a simple way to understand the collaboration structure, change it, or intervene when it fails.

Existing work has explored:

- Mixed initiative and automation levels.
- Supervisory control of robots and swarms.
- Multi-agent LLM frameworks.
- Fixed-role HCI prototypes such as design critique agents.

However, less attention has been paid to how ordinary users can control multi-agent collaboration through a readable, switchable, and task-stage-aware interface language.

## Proposed Contribution

This project proposes **formation-based interaction** for multi-agent collaboration.

A formation is a user-facing collaboration mode that bundles agent roles, communication structure, task flow, and human intervention rules into a recognizable control unit.

## Contribution Claims

1. Conceptual contribution: introduce formation as a command method for multi-agent collaboration.
2. Design contribution: build a prototype with formation switching, task map, agent state, and replay/intervention.
3. Empirical contribution: compare formation-based interaction with chat-based and fixed-role multi-agent interfaces.
4. Practical contribution: derive design implications for future agent command interfaces.

## What Not To Claim

- Do not claim to invent multi-agent systems.
- Do not claim that multi-agent is always better than single-agent.
- Do not claim this is a game interface or gamification.
- Do not claim formation control is new in robotics.

The stronger claim is that formation can be translated into a human-facing interface language for commanding LLM agent teams.
