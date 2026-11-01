# Coopyrightdmin

**Applied AI research · Agentic enterprises · Systems engineering**

I research and build systems that turn AI capabilities into useful work inside organizations. As the founder of [Alien6](https://alien6.com), I combine computer science research, enterprise architecture and hands-on software engineering: framing problems, designing experiments, writing code and working through deployment constraints.

My long-term focus is the **agentic enterprise**: an organization in which people, AI agents, knowledge and existing software cooperate to achieve business outcomes. The ambition to build an AI-driven company has guided my work since 2016. Today, I pursue it through applied research and engineering at Alien6, connecting organizational design with the systems required to make it work.

## Research and engineering directions

**Enterprise knowledge and decision-making.** Making organizational knowledge usable by people and agents: retrieval, memory, context construction, provenance and reasoning over incomplete information. I am interested in how goals, constraints and operational evidence inform decisions, and how knowledge survives beyond an individual task or interaction.

**Agentic workflows and human–AI collaboration.** Investigating task decomposition, planning, multi-agent coordination and long-running execution across business and engineering processes. This includes deciding where model-driven behavior is useful, where deterministic workflows are preferable, and where human judgment, approval or escalation should remain part of the system.

**Reliable action in existing systems.** Connecting agents to enterprise applications, APIs, data and tools while preserving transaction boundaries and accountability. My work spans tool contracts, workload identity, bounded delegation, durable state, idempotency, recovery and execution controls: the mechanisms that connect an intended action to an observable result.

**Evaluation and operational learning.** Studying how to evaluate complete workflows rather than isolated responses: task completion, correctness, failure recovery, human intervention and cost. I am interested in turning execution traces and feedback into reproducible evaluations and reviewed improvements to tools, workflows and policies.

**Frugal AI and execution infrastructure.** Exploring how to allocate work across deterministic software, retrieval, models and human expertise, alongside CPU/GPU placement and resource budgets. The objective is useful capability under real constraints: quality, latency, compute cost, energy and operational complexity.

## Selected implementations

These open-source projects implement parts of that research agenda. Their repositories document the code, examples, maturity and qualification scope.

| Project | Engineering contribution |
| --- | --- |
| [OuterSpace Apizr](https://github.com/Alien6-Studio/outerspace-apizr) | Static inspection of Python capabilities, typed REST/MCP interface generation and experiment tooling that connects existing code to new workflows. |
| [hankoShell Operator](https://github.com/Alien6-Studio/hankoshell-operator) | Declarative identity management on Kubernetes, including Keycloak configuration, workload integration and recovery mechanisms. |
| [Keycloak Bounded Delegation](https://github.com/Alien6-Studio/keycloak-bounded-delegation) | Explicit permission, audience, lifetime and depth limits for delegation between software identities. |
| [Continuum Attest](https://github.com/Alien6-Studio/continuum-attest) | Signed pipeline receipts and verification tools for examining execution evidence under explicit trust policies. |
| [OuterSpace OS](https://github.com/Alien6-Studio/outerspace-os) | Experimental immutable Linux workers with separate agent-execution and CPU-inference profiles. |

## Engineering evidence

The published [hankoShell qualification report](https://github.com/Alien6-Studio/hankoshell-operator/blob/main/docs/qualification.md#measured-results-and-limits) records a **24-hour synthetic endurance campaign with 1,230 managed identity resources**, alongside separately scoped fault-injection and recovery tests. It identifies tested revisions, workloads and limitations; these are infrastructure results, not a benchmark of agent intelligence.

The [hands-on labs](https://github.com/Alien6-Studio/hankoshell-labs) provide disposable environments for exercising identity configuration, workload authentication and operational checks.

## How I work

I move between business objectives, research questions and implementation. I make assumptions explicit, build testable systems, investigate failure cases and turn findings into code, architecture decisions, integration examples and operational guidance. I work across application logic, distributed systems and infrastructure, keeping technical choices connected to the people who will use and operate the result.

**My aim is to make AI a dependable organizational capability: something teams can deploy, evaluate, improve and take responsibility for.**

[Alien6](https://alien6.com) · [Open-source work](https://github.com/Alien6-Studio)
