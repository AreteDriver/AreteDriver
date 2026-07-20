# The Human Stack

**Engineering methodology for deploying AI systems with operational discipline.**

> *A system that ships predictably beats one that demos brilliantly.*

[![The Human Stack](https://img.shields.io/badge/The%20Human%20Stack-v0.9-blue)](https://github.com/AreteDriver/the-human-stack)
[![Animus](https://img.shields.io/badge/Animus-55K%20LOC-blue?logo=github)](https://github.com/AreteDriver/animus)
[![Tests](https://img.shields.io/badge/tests-3%2C000%2B%20core%20%7C%20all%20green-blue?logo=pytest&logoColor=white)](https://github.com/AreteDriver/animus)

I write **The Human Stack** — a living engineering reference for deploying, operating, and evaluating AI systems in production. Everything in this profile is evidence supporting that methodology: eval frameworks that catch regressions before they ship, cost observability that surfaces spend anomalies in real time, and MCP tooling that standardizes how AI agents connect to the world.

Before software I spent 17 years running manufacturing and logistics systems (IBM, Toyota Production System) — standard work, visual management, error-proofing. That discipline shows up in every codebase: ADL-governed decisions, adversarial test gates, evidence-graded maturity.

**[Portfolio](https://aretedriver.dev)** · **[LinkedIn](https://www.linkedin.com/in/james-y-3b77b3120)** · **[jamesyng79@gmail.com](mailto:jamesyng79@gmail.com)**

---

## Start Here: The Arete Stack

The fastest way to understand the methodology is to use it. These repos are arranged as an onion — start at the outer layer and peel inward.

| Layer | Repo | What It Is | Entry Point |
|-------|------|------------|-------------|
| **Skills** | [ai-skills](https://github.com/AreteDriver/ai-skills) | Production-ready skills for Claude Code, agent orchestration, and workflows | `./tools/install.sh --bundle arete-studio-ops` |
| **Cost** | [ai-spend](https://github.com/AreteDriver/ai-spend) | `htop` for AI spend — cross-provider cost aggregation | `pip install ai-spend` |
| **Governance** | [agent-lint](https://github.com/AreteDriver/agent-lint) | Workflow YAML cost estimator + anti-pattern linter | `pip install agentlinter` |
| **Orchestration** | [animus](https://github.com/AreteDriver/animus) | Sovereign AI operating environment with evidence-graded maturity, session persistence, autonomous improvement | `git clone` + `docker compose up` |
| **Methodology** | [the-human-stack](https://github.com/AreteDriver/the-human-stack) | The engineering reference itself — evidence-graded chapters, benchmark methodology, failure taxonomy | Read [VISION.md](https://github.com/AreteDriver/the-human-stack/blob/main/VISION.md) |

---

## The Proof: Animus

[Animus](https://github.com/AreteDriver/animus) is the primary reference implementation — a sovereign AI operating environment with evidence-graded maturity tracking.

| Subsystem | What It Does | Tests |
|-----------|--------------|-------|
| **Kernel** | Bitemporal memory core, checkpoint/resume, session persistence | 179 green |
| **Head** | Quality gates, fallback routing, natural-language interface | 72 green |
| **Citizens** | Architect (autonomous improvement proposals), Conversation Designer, Knowledge Curator | 35 green |
| **Forge** | Eval pipeline, benchmark execution, rubric-based scoring | Integrated |
| **Session Controller** | Token-budgeted session lifecycle, graceful wrap, auto-restart | 22 green |

**Key design decisions (visible in the code):**

- **[Evidence Framework](https://github.com/AreteDriver/animus/blob/main/docs/evidence-framework.md)** — Six-stage maturity model (Concept → Self-improving) with Coverage KPI. Makes "documented but unverified" into "inspectable evidence."
- **[ADL-governed architecture](https://github.com/AreteDriver/animus/tree/main/decisions)** — Every major decision is append-only, dated, and cross-referenced. No tribal knowledge.
- **[Quality gates before merge](https://github.com/AreteDriver/animus-mind)** — Deterministic scoring (tool/completeness/structure) with adversarial test harness. Features don't ship without gate passage.

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

[**BenchGoblins**](https://benchgoblins.com) — Fantasy football analytics with scored LLM routing (Grok-primary), full ESPN + Yahoo parity, 14 commissioner tools, live Stripe billing. 3,921 tests, Fly.io + Vercel. Shows the methodology works for consumer SaaS, not just infrastructure.

---

## How I Work

- **Decision logs, not memory.** Every architectural choice is an ADL entry — rationale, rejected options, tradeoffs, kill criteria.
- **Tests are deliverables.** Not an afterthought. Adversarial tests prevent regression of quality-gate contracts.
- **Local-first where possible.** RX 7900 XTX inference stack (Ollama, 4-model tiered) for zero-cost eval calibration.
- **Ship, measure, error-proof, repeat.** Kaizen learned from scaling an ice-cream line 6× — applied to software.

---

## Selected Work

Direct entry points for "what does the code actually look like":

- **[Animus Kernel — bitemporal memory + adversarial tests](https://github.com/AreteDriver/animus-mind)** — v2.3 scaffold: valid-time / transaction-time axes, quality-gate contracts enforced before any feature ships. Architect Citizen produces ImprovementProposals from codebase observation.
- **[ai-spend — OpenRouter provider](https://github.com/AreteDriver/ai-spend)** — `GET /api/v1/generations` pagination with `native_cost` fallback to token-based estimates. Pattern: provider registry ABC with side-effect registration.
- **[Animus Session Controller](https://github.com/AreteDriver/animus)** — Token-budgeted session lifecycle (96% utilization trigger), graceful finalization with model-generated summary, checkpoint + auto-restart. 22 tests, 83 existing head core tests green.
- **[Animus P5 Discovery](https://github.com/AreteDriver/animus)** — MCP scanner, OpenAPI ingestion, annotated script discovery, 4-dimension schema validator, hash deduplication. 41 tests, 194 total P0–P5 tests green.

---

## Background

17 years in manufacturing and logistics operations (IBM, Toyota Production System). Scaled an ice-cream production line from 740 pints/day to 4,800/hour using Kaizen. Now apply the same discipline to AI infrastructure: standard work, visual management, error-proofing, continuous improvement.

*See it through. Do it better. Leave something real.*
