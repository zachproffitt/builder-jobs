---
id: ashby-qdrant.tech-2f130d2c-72a2-4542-adde-0fe5cee94a65
company: Qdrant
title: Research Engineer, Agentic Retrieval (North America)
source: ashby
location: Remote - US
remote: Remote
posted_at: 2026-05-08
first_seen: 2026-05-12
url: https://jobs.ashbyhq.com/qdrant.tech/2f130d2c-72a2-4542-adde-0fe5cee94a65
summary: This person will build evaluation infrastructure for agentic retrieval, reference implementations for agent memory architectures, and experiment frameworks to test retrieval patterns in agent loops. They will also design systems for skill/tool retrieval and profile agent retrieval traces for performance.
source_hash: 20329a6c
---

# Research Engineer, Agentic Retrieval (North America)

**Qdrant** — Qdrant builds an open-source vector search engine for AI applications, including semantic search, retrieval-augmented generation, and real-time recommendations.

> This person will build evaluation infrastructure for agentic retrieval, reference implementations for agent memory architectures, and experiment frameworks to test retrieval patterns in agent loops. They will also design systems for skill/tool retrieval and profile agent retrieval traces for performance.

| Field | Value |
|---|---|
| Company | Qdrant |
| Location | Remote - US |
| Remote | Remote |
| Posted | 2026-05-08 |
| First seen | 2026-05-12 |
| Source | ashby |

[Apply](https://jobs.ashbyhq.com/qdrant.tech/2f130d2c-72a2-4542-adde-0fe5cee94a65)

---

Qdrant is an open-source vector search engine powering the next generation of AI applications, from semantic search and retrieval-augmented generation (RAG) to AI agents and real-time recommendations.

Trusted by global leaders like Canva, HubSpot, Tripadvisor, Bosch, and Deutsche Telekom, we’re building the retrieval infrastructure layer for modern AI. Recently raising $50M in Series B funding, we are growing rapidly and committed to transforming how AI understands and interacts with data.

As a remote-first company, we believe diverse backgrounds, perspectives, and experiences fuel innovation. Here, you’ll own meaningful work, tackle challenges, and grow alongside passionate individuals dedicated to shaping the future of AI.

We are looking for a Research Engineer, Agentic Retrieval. You'll work at the seam between agent systems research and retrieval engineering, running a tight loop between hypothesis, experiment, and shipped artifact.

The questions you'll chase may not have settled answers yet: how agents should structure memory, when they should re-query versus reason, how skills and tools should be retrieved and composed, what retrieval primitives the agent loop actually needs, and what "good" even means when success is a multi-step trajectory rather than a ranked list.

You'll go deep on how real agent stacks use Qdrant today, where the abstractions around them help or hurt, and what we should build (or change) so they can do more with less. The agent ecosystem moves fast, and part of the job is staying current with it without getting captured by it.

You'll have a lot of latitude to choose what to investigate. The bar is the same either way: every cycle should produce something the field, our customers, or the rest of the company can act on.


WHAT YOU WILL OWN

 - Define what good agentic retrieval looks like. Characterize the retrieval patterns inside real agent loops, name the failure modes, and turn that vocabulary into something the team and the field can build against.

 - Treat agent memory as a systems problem. Episodic, semantic, and procedural memory each need different write paths, decay, and consolidation. Figure out which architectures hold up at scale and turn the durable patterns into reference implementations.

 - Investigate skill and tool retrieval as a first-class problem. How a skill registry should be indexed, how skills should be selected under tool budgets, and how retrieval should compose with planner decisions.

 - Design and run experiments on retrieval inside agent loops: query rewriting and decomposition, multi-hop retrieval, tool-conditioned filtering, retrieval-as-a-tool patterns, and the interplay between planner, retriever, and reranker.

 - Build evaluation infrastructure for agentic retrieval. Define metrics that correlate with end-to-end task success rather than recall@k, and build harnesses that catch regressions before they ship.

 - Profile agent retrieval traces end to end. Isolate where latency, cost, and quality losses come from across the fan-out of tool calls, and produce minimal reproductions when something looks like an engine-level issue.

 - Study how real agent stacks use Qdrant in production. Trace workloads, find where the surrounding abstractions leak performance or quality, and propose changes in Qdrant, in the stack, or in the recipe between them.

 - Pair with design-partner teams running serious agent workloads in production, and bring their real constraints back into research priorities.

 - Influence the roadmap. Translate evidence into product bets and argue for what should be a feature, a primitive, or a recipe.


WHO YOU ARE

 - You read and reason about LLM behavior directly. You can distinguish prompt issues from planning issues from retrieval issues from tool design issues, and you've internalized how models actually use retrieved content versus ignore it.

 - You treat memory as a systems design problem. You distinguish episodic, semantic, and procedural memory, and you know naive "store every turn as a vector" approaches collapse fast.

 - You understand tool and skill systems as retrieval problems. You see tool selection and skill matching as ranking problems with their own quirks: tiny corpora, heavy metadata, strong priors, sensitivity to descriptions.

 - You have a working theory of context engineering. You think carefully about what goes into the context window and why, and you understand that retrieval quality and context construction are the same problem from two angles.

 - You build evals before features. You know how to construct task suites that actually discriminate between approaches, and how to avoid just on recall@k.

 - You know vector search internals at a decent level. HNSW tradeoffs, quantization, filtered search, multi-vector, hybrid retrieval, payload indexing. Enough to design agent patterns that exploit Qdrant's primitives instead of treating the database as a black box.

 - You write precisely. You can describe a memory architecture or failure mode in a way other engineers can implement from.


NICE TO HAVE

 - Contributions to agent stacks, skill systems, MCP servers, RAG tooling, or eval harnesses.

 - Experience designing agent benchmarks or running them at scale.

 - Familiarity with Qdrant or comparable vector search systems under production agent traffic.

 - Track record working with design-partner customers or open-source community contributors.


WHY JOIN US

 - A remote-first, international team working on cutting-edge AI infrastructure.

 - A competitive salary with additional perks.

 - Flexible working hours and async-friendly culture.

 - High ownership and real impact.

 - Open-source, engineering-driven culture.

 - Choose your own laptop equipment.

For US-based candidates, we also offer a comprehensive benefits package including 401k match, health, dental, and vision insurance, plus flexible PTO policy.


Qdrant is an equal-opportunity employer. We believe the best ideas come from diverse teams, and we actively welcome applicants from all backgrounds. If this role excites you but you don't check every single box, we'd still love to hear from you! We don't want to miss out on great people because of a checklist.


COME BUILD WITH US!

FOR INFORMATION ON HOW WE HANDLE YOUR PERSONAL DATA, PLEASE REFER TO OUR RECRUITMENT PRIVACY POLICY https://qdrant.tech/legal/recruitment-privacy-policy/
