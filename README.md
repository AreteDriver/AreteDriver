# James C. Young

**AI Enablement / Forward-Deployed Engineer** — Portland, OR

I ship LLM-powered products end to end — eval harnesses, multi-agent systems, billing, deploy — and I have the operations background to make them reliable. Before software I spent 17 years running manufacturing and logistics systems (IBM, Toyota Production System): standard work, visual management, error-proofing. A system that ships predictably beats one that demos brilliantly.

**[Portfolio](https://aretedriver.dev)** · **[LinkedIn](https://linkedin.com/in/jamesy-3b77b3120)** · **[Substack](https://substack.com/@aretedriver)** · **jamesyng79@gmail.com**

`Python` · `TypeScript` · `React / Next.js` · `FastAPI` · `PostgreSQL / SQLite` · `LLM evaluation & routing` · `multi-agent orchestration` · `MCP servers` · `Stripe` · `CI/CD (GitHub Actions)` · `Vercel / Fly.io` · `Azure`

**12+ published PyPI packages** · **12,000+ tests across published packages** · **live Stripe billing**

---

## Shipped Products

[**BenchGoblins**](https://benchgoblins.com) — AI fantasy-sports decision engine. Scored LLM routing under the hood, commissioner tools, live on Fly.io + Vercel with Stripe billing. *Production codebase private; comparable scored-routing patterns visible in [memboot](https://github.com/AreteDriver/memboot).*

[**EVE Gatekeeper**](https://edengk.com) — Route-intelligence platform for EVE Online: interactive 14-layer map, per-hop risk breakdown, gate-camp warnings. Stripe billing live. [GitHub](https://github.com/Arete-Consortium/Gatekeeper)

[**anchormd**](https://anchormd.dev) — AI-agent context-file generator and auditor (CLAUDE.md / AGENTS.md). Web app + CLI + license server, Stripe billing live. `pip install anchormd` · [GitHub](https://github.com/Arete-Consortium/anchormd)

---

## Developer Tools — [PyPI](https://pypi.org/user/AreteDriver/)

| Tool | Description | Install |
|------|-------------|---------|
| [agent-lint](https://github.com/AreteDriver/agent-lint) | Workflow cost estimator and anti-pattern linter for agent YAML | `pip install agentlinter` |
| [context-hygiene](https://github.com/AreteDriver/context-hygiene) | Context-window bloat detection and signal-density scoring | `pip install context-hygiene` |
| [promptctl](https://github.com/AreteDriver/promptctl) | Claude API toolkit — prompt engineering, code review | `pip install promptctlai` |
| [ai-spend](https://github.com/AreteDriver/ai-spend) | AI API cost aggregator across providers | `pip install ai-spend` |
| [memboot](https://github.com/AreteDriver/memboot) | Zero-infra persistent memory for any LLM | `pip install memboot` |
| [convergentAI](https://github.com/AreteDriver/convergent) | Multi-agent coordination — intent graphs, consensus voting, stigmergy | `pip install convergentAI` |
| [mcp-manager](https://github.com/AreteDriver/mcp-manager) | Manage MCP servers across agentic IDEs | `pip install arete-mcp` |
| [arete-cc-plugin](https://github.com/AreteDriver/arete-cc-plugin) | Portable Claude Code plugin — hooks, slash commands, subagents | — |

---

## Open Source

[**Aurora Arcology**](https://aurora-arcology.vercel.app) — Investigation-board framework for narrative universes: an interactive corkboard of nodes, sourced claims, and confidence-weighted connections. Next.js 15 + TypeScript + SQLite/Drizzle, runtime-editable ontology. [GitHub](https://github.com/AreteDriver/aurora-arcology) · [Live demo](https://aurora-arcology.vercel.app)

**Animus** — Multi-agent orchestration framework: budget controls, quality gates, checkpoint/resume, autonomous self-improvement loop. ~17k tests across 13 packages. *Private repo (long-term IP); architecture + selected code in [animus-docs](https://github.com/AreteDriver/animus-docs).*

**DOSSIER** — Local-first document intelligence: ingest PDFs/emails/scans, extract entities, surface relationships, forensics timeline. *Private repo; architecture in [dossier-docs](https://github.com/AreteDriver/dossier-docs).*

[**Argus Overview**](https://github.com/AreteDriver/Argus_Overview) — Linux multi-window manager for EVE Online. [PyPI](https://pypi.org/project/argus-overview/)

[**ai-skills**](https://github.com/AreteDriver/ai-skills) — Production-ready skills for Claude Code and multi-agent systems.

[**production-Test01**](https://github.com/AreteDriver/production-Test01) — Multi-persona operational-intelligence monorepo: supervisor analytics, floor-team execution tooling, TV dashboards, REST API on a shared SQLite/Drizzle core. Synthetic data, portfolio artifact.

**EVE Frontier tooling** — [Monolith](https://github.com/AreteDriver/monolith): on-chain anomaly detector for EVE Frontier on Sui, with a live 3D-map demo of 24k systems.

---

## Selected Work

Direct entry points for "what does the code actually look like":

- **[memboot v0.7.1 — SSRF guard + credential-dir denylist](https://github.com/AreteDriver/memboot/commit/e4ba5c7)** — Semantic-security audit caught two MEDIUM findings the SAST run missed. Shipped scheme allowlist with redirect re-validation + extended default `ignore_patterns` to skip credential directories. Regression test asserts the exact attack scenarios stay out of `discover_files` output — poka-yoke against silent regression of the default skip list.

- **[Argus Overview — character-logoff detection](https://github.com/AreteDriver/Argus_Overview/commit/28e609e)** — Spec-driven feature in a 26K-download tool: tracker subscribes to existing `character_gone` signal, idempotent slot, 11 new tests including p95 latency under 5ms across 100 trials. Architecture luck — the detection signal already existed; the work was wiring + verifying.

- **[aurora-arcology — Dossier integration scoping](https://github.com/AreteDriver/aurora-arcology/blob/main/docs/dossier-bridge.md)** — Cross-project leverage analysis: four bridges from Dossier (forensic NER + briefing endpoint) into Aurora (narrative-investigation board), ranked by ROI with dependencies + effort estimates per bridge. The FDE pattern of recognizing where one product's primitives serve another's gap.

---

## Consulting & Writing

**TIAID — Trauma-Informed AI Deployment** — a methodology for rolling out AI inside organizations without breaking the people, mapped to the NIST AI Risk Management Framework. Long-form essays on the human side of AI adoption at [The Human Stack](https://substack.com/@aretedriver).

---

## Background

I scaled an ice-cream production line from 740 pints/day to 4,800/hour using Kaizen — and I bring the same discipline to software: ship, measure, error-proof, repeat. *See it through. Do it better. Leave something real.*
