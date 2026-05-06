# Introduction Draft

## Current Working Version

Generative AI is changing software interaction from direct tool operation toward task delegation. Instead of clicking through every step, users increasingly describe goals and expect AI agents to plan, execute, and report progress. As agent systems become more capable, the interface challenge is also changing: users may no longer interact with a single assistant, but with a set of agents that search, reason, debate, verify, and execute together.

Current agent interfaces still tend to rely on two familiar patterns. One pattern treats AI as a single conversational assistant, where the user writes prompts and receives responses. Another pattern uses fixed role-based agents, where several agents play predefined roles such as planner, researcher, reviewer, or executor. These patterns are useful, but they leave an interaction gap. When a task becomes complex, users need to understand not only what each agent says, but how the whole agent team is organized, which collaboration mode is currently active, where the task is risky, and when human intervention is needed.

This project explores a formation-based interface for multi-agent collaboration. Here, a formation means a recognizable collaboration mode for a group of agents, such as scouting, debating, executing, or auditing. Rather than controlling each agent through detailed prompts, users can switch formations to change how the agent team works. This idea is inspired by real-time strategy games, where players manage multiple units through grouping, role assignment, situation monitoring, alerts, and timely intervention. The goal is not to gamify AI tools, but to translate mature command patterns into a new interface language for agent collaboration.

The project asks a human-computer interaction question: when AI systems evolve from single assistants into collaborative agent teams, how should humans command, understand, and take over their work? To investigate this question, the project will design a prototype with formation switching, task map visualization, agent state display, and collaboration replay. A user study will compare formation-based interaction with chat-based agent interaction and fixed-role multi-agent interaction, focusing on situation awareness, perceived control, orchestration burden, and error recovery.

## Notes for Revision

This draft should become more academic after the literature map is expanded. The next version should cite mixed-initiative interaction, levels of automation, supervisory control, human-swarm interaction, and multi-agent LLM frameworks.
