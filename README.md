# James C. Young

**Applied AI Systems Engineer** — eval infrastructure, cost observability, MCP tooling 

[![Animus](https://img.shields.io/badge/Animus-55K%20LOC-blue?logo=github)](https://github.com/AreteDriver/animus)
[![Tests](https://img.shields.io/badge/tests-3%2C000%2B%20core%20%7C%20all%20green-blue?logo=pytest&logoColor=white)](https://github.com/AreteDriver/animus)
[![MCP](https://img.shields.io/badge/MCP%20servers-6%20shipped-brightgreen?logo=anthropic)](https://github.com/AreteDriver/mcp-manager)
[![SaaS](https://img.shields.io/badge/SaaS-2%20live%20products-orange)](https://benchgoblins.com)

I build reliable AI infrastructure: eval frameworks that catch regressions before they ship, cost observability that surfaces spend anomalies in real time, and MCP tooling that standardizes how AI agents connect to the world. Before software I spent 17 years running manufacturing and logistics systems (IBM, Toyota Production System) — standard work, visual management, error-proofing. That discipline shows up in every codebase: ADL-governed decisions, adversarial test gates, evidence-graded maturity.

A system that ships predictably beats one that demos brilliantly.

**[Portfolio](https://aretedriver.dev)** · **[LinkedIn](https://www.linkedin.com/in/james-y-3b77b3120)** · **[jamesyng79@gmail.com](mailto:jamesyng79@gmail.com)**

---

## The Proof: Animus

[Animus](https://github.com/AreteDriver/animus) is the primary reference implementation of my work — a sovereign AI operating environment with evidence-graded maturity tracking.

| Subsystem | What It Does | Tests |
|-----------|--------------|-------|
| **Kernel** | Bitemporal memory core, checkpoint/resume, session persistence | 190 green |
| **Head** | Quality gates, fallback routing, natural-language interface | 83 green |
| **Citizens** | Architect (autonomous improvement proposals), Conversation Designer, Knowledge Curator | 71 green |
| **Forge** | Eval pipeline, benchmark execution, rubric-based scoring | Integrated |
| **Session Controller** | Token-budgeted session lifecycle, graceful wrap, auto-restart | 22 green |

**Key design decisions (visible in the code):**

- **[Evidence Framework](https://github.com/AreteDriver/animus/tree/main/docs/metrics)** — Six-stage maturity model (Concept → Self-improving) with Coverage KPI. Makes "documented but unverified" into "inspectable evidence."
- **[ADL-governed architecture](https://github.com/AreteDriver/animus/tree/main/decisions)** — Every major decision is append-only, dated, and cross-referenced. No tribal knowledge.
- **[Quality gates before merge](https://github.com/AreteDriver/animus)** — Deterministic scoring (tool/completeness/structure) with adversarial test harness. Features don't ship without gate passage.

---

## Active Developer Tools

| Tool | What It Does | Install |
|------|--------------|---------|
| [ai-spend](https://github.com/AreteDriver/ai-spend) | **`htop` for AI spend** — cross-provider cost aggregation with OpenRouter, Anthropic, OpenAI | `pip install ai-spend` |
| [mcp-manager](https://github.com/AreteDriver/mcp-manager) | MCP server manager across agentic IDEs (Claude Code, Cursor, Windsurf) | `pip install arete-mcp` |
| [agent-lint](https://github.com/AreteDriver/agent-lint) | Workflow YAML cost estimator + anti-pattern linter | `pip install agentlinter` |
| [promptctl](https://github.com/AreteDriver/promptctl) | Claude API toolkit — prompt versioning, code review, doc intelligence | `pip install promptctlai` |

> **Not shown:** [context-hygiene](https://github.com/AreteDriver/context-hygiene) — heuristic context-window analyzer (position-decay + regex patterns). Honest about what it is.

---

## Production SaaS

[**BenchGoblins**](https://benchgoblins.com) — Fantasy football analytics with scored LLM routing (Grok-primary), full ESPN + Yahoo parity, 14 commissioner tools, live Stripe billing. 4,074 tests, Fly.io + Vercel. Shows I can ship consumer SaaS, not just infrastructure.

---

## Engineering Methodology

[**The Human Stack**](https://github.com/AreteDriver/the-human-stack) — Living reference for deploying AI systems with operational discipline. Evidence-graded chapters (E0–E5), benchmark methodology with rubric-based scoring, failure taxonomy, deployment case studies. Everything else I build is evidence supporting this framework.

**How I work:**

- **Decision logs, not memory.** Every architectural choice is an ADL entry — rationale, rejected options, tradeoffs, kill criteria.
- **Tests are deliverables.** Not an afterthought. Adversarial tests prevent regression of quality-gate contracts.
- **Local-first where possible.** RX 7900 XTX inference stack (Ollama, 4-model tiered) for zero-cost eval calibration.
- **Ship, measure, error-proof, repeat.** Kaizen learned from scaling an ice-cream line 6× — applied to software.

---

## Selected Work

Direct entry points for "what does the code actually look like":

- **[Animus Kernel — bitemporal memory + adversarial tests](https://github.com/AreteDriver/animus/tree/main/packages/kernel)** — v2.3 scaffold: valid-time / transaction-time axes, quality-gate contracts enforced before any feature ships. Architect Citizen produces ImprovementProposals from codebase observation.
- **[ai-spend — OpenRouter provider](https://github.com/AreteDriver/ai-spend)** — `GET /api/v1/generations` pagination with `native_cost` fallback to token-based estimates. Pattern: provider registry ABC with side-effect registration.
- **[Animus Session Controller](https://github.com/AreteDriver/animus)** — Token-budgeted session lifecycle (96% utilization trigger), graceful finalization with model-generated summary, checkpoint + auto-restart. 22 tests, 83 existing head core tests green.
- **[Animus P5 Discovery](https://github.com/AreteDriver/animus)** — MCP scanner, OpenAPI ingestion, annotated script discovery, 4-dimension schema validator, hash deduplication. 41 tests, 194 total P0–P5 tests green.

---

## Background

17 years in manufacturing and logistics operations (IBM, Toyota Production System). Scaled an ice-cream production line from 740 pints/day to 4,800/hour using Kaizen. Now apply the same discipline to AI infrastructure: standard work, visual management, error-proofing, continuous improvement.

*See it through. Do it better. Leave something real.*
