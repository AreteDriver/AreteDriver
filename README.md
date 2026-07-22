# The Human Stack

**Engineering methodology for deploying AI systems with operational discipline.**

> *A system that ships predictably beats one that demos brilliantly.*

[![The Human Stack](https://img.shields.io/badge/The%20Human%20Stack-v0.9-blue)](https://github.com/AreteDriver/the-human-stack)
[![Animus](https://img.shields.io/badge/Animus-51K%20LOC-blue?logo=github)](https://github.com/AreteDriver/animus)
[![Tests](https://img.shields.io/badge/tests-%7E17%2C000%2B%20%7C%20all%20green-blue?logo=pytest&logoColor=white)](https://github.com/AreteDriver/animus)

## The Predictability Gap

Most AI projects ship as demos and die in production. The failure modes are boringly consistent: **costs spiral** because no one tracks token spend, **pipelines break halfway through** and restart from scratch wasting compute, and **multi-agent systems bottleneck** on a single supervisor that burns tokens just watching. These aren't capability problems — they're operational problems.

**The Human Stack** is my response: a living engineering methodology that treats AI systems as operational systems. Every claim is evidence-graded (E0–E5). Every architectural choice is append-only, dated, and cross-referenced in an ADL. Every tool carries adversarial tests before it ships. The methodology is public in [the-human-stack](https://github.com/AreteDriver/the-human-stack).

**The Arete Stack** is its implementation — the tools I actually build and maintain. Each repo maps to a layer of the methodology: skills for session discipline, cost observability for spend anomalies, governance linting for workflow anti-patterns, orchestration for autonomous improvement, and the methodology reference itself. This profile is arranged as an onion — start at the outer layer and peel inward.

*Before software I spent 17 years in manufacturing and logistics (IBM, Toyota Production System). That discipline shows up in every codebase: standard work, visual management, error-proofing, continuous improvement.*

**[Substack](https://aretedriver.substack.com)** · **[LinkedIn](https://www.linkedin.com/in/james-y-3b77b3120)** · **[jamesyng79@gmail.com](mailto:jamesyng79@gmail.com)**

---

## Selected Writing

- **[I Oversaw Scaling a Portland Ice Cream Line to 4,800 Pints Per Hour. AI Engineers Keep Making the Same Mistakes.](https://aretedriver.substack.com)** — Manufacturing discipline applied to production AI: waste visibility, checkpoint/resume, and error-proofing before error-catching.
- **[The Eval Is the Product](https://aretedriver.substack.com)** — Why evaluation infrastructure matters more than model choice.
- **[Local-First AI Stack](https://aretedriver.substack.com)** — Zero-cost inference with Ollama on consumer hardware.
- **[Decision Logging as Operational Memory](https://github.com/AreteDriver/the-human-stack/blob/main/manual/50-principles/decision-logging.md)** — The ADL methodology: append-only, evidence-graded, revisit-conditioned.

---

## Notable Projects

These are the repos I maintain to production quality — evidence, tests, and documentation first.

| Project | Stars | Language | What It Is |
|---------|-------|----------|------------|
| [animus](https://github.com/AreteDriver/animus) | ⭐1 | Python | Personal AI operating environment — bitemporal memory, evidence-graded maturity, autonomous improvement |
| [mcp-manager](https://github.com/AreteDriver/mcp-manager) | ⭐1 | Python | MCP server lifecycle manager across Claude Code, Cursor, Windsurf — now with permission-prompt audit |
| [ai-spend](https://github.com/AreteDriver/ai-spend) | ⭐0 | Python | Cross-provider AI cost aggregation with provider retry, config encryption, and health checks |
| [agent-lint](https://github.com/AreteDriver/agent-lint) | ⭐2 | Python | Workflow YAML cost estimator + anti-pattern detection for agent orchestration |
| [the-human-stack](https://github.com/AreteDriver/the-human-stack) | ⭐0 | Markdown | Living engineering reference — evidence-graded chapters, benchmark methodology, failure taxonomy |
| [ai-skills](https://github.com/AreteDriver/ai-skills) | ⭐3 | Python | Production-ready skills for Claude Code personas and orchestrated workflows |
| [arete-evals](https://github.com/AreteDriver/arete-evals) | ⭐1 | Python | LLM eval suites and run records — eval engineering vs eval practice |

*Hobby projects (EVE Online lore, personal context servers) are kept private. What you see here is what I ship.*

---

## Start Here: The Arete Stack

The fastest way to understand the methodology is to use it. These repos are arranged as an onion — start at the outer layer and peel inward.

| Layer | Repo | What It Is | Entry Point |
|-------|------|------------|-------------|
| **Skills** | [ai-skills](https://github.com/AreteDriver/ai-skills) | Production-ready skills for Claude Code, agent orchestration, and workflows | `./tools/install.sh --bundle arete-studio-ops` |
| **Eval** | [arete-evals](https://github.com/AreteDriver/arete-evals) | LLM eval suites and run records — eval engineering vs eval practice | `pip install -e .` |
| **Cost** | [ai-spend](https://github.com/AreteDriver/ai-spend) | `htop` for AI spend — cross-provider cost aggregation | `pip install ai-spend` |
| **Governance** | [agent-lint](https://github.com/AreteDriver/agent-lint) | Workflow YAML cost estimator + anti-pattern linter | `pip install agentlinter` |
| **Orchestration** | [animus](https://github.com/AreteDriver/animus) | Personal AI operating environment with local-first control, evidence-graded maturity, session persistence, autonomous improvement | `git clone` + `docker compose up` |
| **Methodology** | [the-human-stack](https://github.com/AreteDriver/the-human-stack) | The engineering reference itself — evidence-graded chapters, benchmark methodology, failure taxonomy | Read [VISION.md](https://github.com/AreteDriver/the-human-stack/blob/main/VISION.md) |

---

## The Proof: Animus

[Animus](https://github.com/AreteDriver/animus) is the primary reference implementation — a personal AI operating environment with local-first control and evidence-graded maturity tracking.

| Subsystem | What It Does | Tests |
|-----------|--------------|-------|
| **Kernel** | Bitemporal memory core, checkpoint/resume, session persistence | 488 green |
| **Head** | Quality gates, fallback routing, natural-language interface | 96 green |
| **Citizens** | Architect (autonomous improvement proposals), Conversation Designer, Knowledge Curator | 71 green |
| **Forge** | Eval pipeline, benchmark execution, rubric-based scoring | Integrated |
| **Session Controller** | Token-budgeted session lifecycle, graceful wrap, auto-restart | 22 green |

**Key design decisions (visible in the code):**

- **[Evidence Framework](https://github.com/AreteDriver/animus/blob/main/docs/evidence-framework.md)** — Six-stage maturity model (Concept → Self-improving) with Coverage KPI. Makes "documented but unverified" into "inspectable evidence."
- **[ADL-governed architecture](https://github.com/AreteDriver/animus/tree/main/decisions)** — Every major decision is append-only, dated, and cross-referenced. No tribal knowledge.
- **[Quality gates before merge](https://github.com/AreteDriver/animus)** — Deterministic scoring (tool/completeness/structure) with adversarial test harness. Features don't ship without gate passage.

---

## Active Developer Tools

| Tool | What It Does | Install |
|------|--------------|---------|
| [ai-spend](https://github.com/AreteDriver/ai-spend) | **`htop` for AI spend** — cross-provider cost aggregation with OpenRouter, Anthropic, OpenAI | `pip install ai-spend` |
| [mcp-manager](https://github.com/AreteDriver/mcp-manager) | MCP server manager across agentic IDEs (Claude Code, Cursor, Windsurf) | `pip install arete-mcp` |
| [agent-lint](https://github.com/AreteDriver/agent-lint) | Workflow YAML cost estimator + anti-pattern linter | `pip install agentlinter` |
| [context-hygiene](https://github.com/AreteDriver/context-hygiene) | Heuristic context-window analyzer — position-decay scoring + regex patterns | `pip install context-hygiene` |
| [arete-evals](https://github.com/AreteDriver/arete-evals) | LLM eval suites with benchmark scoring, A/B comparison with bootstrap CIs | `pip install -e .` |
| [ci-templates](https://github.com/AreteDriver/ci-templates) | Reusable GitHub Actions workflows, lint configs, release automation | Copy + adapt |
| [RedOPS](https://github.com/AreteDriver/RedOPS) | Red-team playbook for AI infrastructure — incident response, supply-chain audit | Read + run |
| [overwatch](https://github.com/AreteDriver/overwatch) | Multi-service health monitoring with structured logging and alerting | `pip install -e .` |

---

## How I Work

- **Decision logs, not memory.** Every architectural choice is an ADL entry — rationale, rejected options, tradeoffs, kill criteria.
- **Tests are deliverables.** Not an afterthought. Adversarial tests prevent regression of quality-gate contracts.
- **Local-first where possible.** RX 7900 XTX inference stack (Ollama, 4-model tiered) for zero-cost eval calibration.
- **Ship, measure, error-proof, repeat.** Kaizen learned from scaling an ice-cream line 6× — applied to software.

---

## How This Code Is Written

I develop primarily with **Claude Code** (Anthropic's CLI for Claude). Think of it as pair programming with a fast, literal pair — not autonomous AI.

**What that means:**
- Every commit is human-reviewed. The `claude` contributor in git history is the application, not a person.
- Every test is human-verified. Coverage numbers reflect assertions I wrote and ran.
- Every architectural decision is logged in the ADL with rationale, rejected options, and tradeoffs.
- AI accelerates implementation; humans own validation, integration, and shipping.

**Why this matters:**
AI-assisted development is becoming standard. What differentiates engineering discipline from cargo-culting is the verification layer: adversarial tests, evidence-graded maturity, and append-only decision logs. The code works because I test it. The methodology holds because I revisit it.

---

## Selected Work

Direct entry points for "what does the code actually look like":

- **[Animus Kernel — bitemporal memory + adversarial tests](https://github.com/AreteDriver/animus)** — v2.3 scaffold: valid-time / transaction-time axes, quality-gate contracts enforced before any feature ships. Architect Citizen produces ImprovementProposals from codebase observation.
- **[ai-spend — OpenRouter provider](https://github.com/AreteDriver/ai-spend)** — `GET /api/v1/generations` pagination with `native_cost` fallback to token-based estimates. Pattern: provider registry ABC with side-effect registration.
- **[Animus Session Controller](https://github.com/AreteDriver/animus)** — Token-budgeted session lifecycle (96% utilization trigger), graceful finalization with model-generated summary, checkpoint + auto-restart. 22 tests, 96 existing head core tests green.
- **[Animus P5 Discovery](https://github.com/AreteDriver/animus)** — MCP scanner, OpenAPI ingestion, annotated script discovery, 4-dimension schema validator, hash deduplication. 41 tests, 194 total P0–P5 tests green.

---

## Background

17 years in manufacturing and logistics operations (IBM, Toyota Production System). Scaled an ice-cream production line from 740 pints/day to 4,800/hour using Kaizen. Now apply the same discipline to AI infrastructure: standard work, visual management, error-proofing, continuous improvement.

*See it through. Do it better. Leave something real.*
