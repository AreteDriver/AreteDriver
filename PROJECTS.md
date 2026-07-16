# AreteDriver Project Status

Last updated: 2026-07-16

This page replaces stale portfolio claims with honest, evidence-based status. If a project is listed as **OPERATIONAL**, you can install it today. If it's **PARTIAL**, some pieces work but it's not yet a complete product. If it's **STALE** or **ARCHIVED**, the reason is explicit.

---

## Active (Verified Within 90 Days)

| Project | Status | Tests / Evidence | Docs | Notes |
|---------|--------|------------------|------|-------|
| [Animus](https://github.com/AreteDriver/animus) | **OPERATIONAL** | 2928/2928 green | [Docs](https://aretedriver.github.io/animus/) | Multi-agent orchestration. First-run scenario verified in CI. |
| [agent-lint](https://github.com/AreteDriver/agent-lint) | **OPERATIONAL** | CI green | README | PyPI package `agentlinter`. Cost estimation + anti-pattern detection. |
| [the-human-stack](https://github.com/AreteDriver/the-human-stack) | **OPERATIONAL** | 13 E3 + 6 E4 claims | Living manual | Evidence-graded engineering reference. Not installable — it's a document. |
| [arete-evals](https://github.com/AreteDriver/arete-evals) | **PARTIAL** | Live run records | README + case studies | Eval practice repo. Engine is `evalcore` (sibling repo, not public). |
| [chainlog](https://github.com/AreteDriver/chainlog) | **PARTIAL** | SDK tests (31+31) | README | On-chain audit trails. Contracts deployed; dashboard live. No security audit. |

---

## Stale / Parked

| Project | Last Activity | Reason |
|---------|---------------|--------|
| [memboot](https://github.com/AreteDriver/memboot) | 2026-07-03 | Memory layer concept superseded by Animus Kernel `DurableObjectStore` |
| [promptctl](https://github.com/AreteDriver/promptctl) | 2026-07-06 | CLI tool for prompt versioning. Functional but not actively developed. |
| [context-hygiene](https://github.com/AreteDriver/context-hygiene) | 2026-07-06 | Context-window management. Merged concepts into Animus Head Phase 3. |
| [ai-spend](https://github.com/AreteDriver/ai-spend) | 2026-07-06 | Token-cost tracking. Superseded by Animus Forge budget controls. |
| [mcp-manager](https://github.com/AreteDriver/mcp-manager) | 2026-07-10 | MCP server registry UI. Partial; no install docs. |
| [mcp-fuzz](https://github.com/AreteDriver/mcp-fuzz) | 2026-07-06 | MCP server fuzz testing. Experimental. |
| [azure-ops-mcp](https://github.com/AreteDriver/azure-ops-mcp) | 2026-07-06 | Azure MCP server. No recent usage evidence. |
| [stellar-audit-agent](https://github.com/AreteDriver/stellar-audit-agent) | 2026-07-06 | Blockchain audit agent. Concept only. |
| [arete-context-mcp](https://github.com/AreteDriver/arete-context-mcp) | 2026-07-06 | Context-bridge MCP. Superseded by Animus native context. |
| [ai-skills](https://github.com/Arete-Consortium/ai-skills) | 2026-06-22 | Skill system for Claude Code. Concepts upstreamed to Animus citizens. |
| [ai-session-templates](https://github.com/Arete-Consortium/ai-session-templates) | 2026-06-22 | Session templates. Still referenced but not actively maintained. |
| [overwatch](https://github.com/AreteDriver/overwatch) | 2026-06-22 | Monitoring dashboard. Stale; no recent deploys. |
| [Dossier](https://github.com/AreteDriver/Dossier) | 2026-07-06 | EVE Online tool. No memory of recent work. |
| [aurora-arcology](https://github.com/AreteDriver/aurora-arcology) | 2026-05-28 | Game prototype. Inactive. |

---

## Archived

| Project | Archived Date | Lessons Captured |
|---------|---------------|------------------|
| [anchormd](https://github.com/Arete-Consortium/anchormd) | 2026-03 | Document-control patterns absorbed into Animus; three-layer architecture reusable |
| Gorgon | 2026-03 | Multi-agent orchestration concepts evolved into Animus Forge |

---

## How This List Is Maintained

- **Verification:** Every OPERATIONAL entry has either a green CI badge or a committed first-run scenario doc.
- **Cadence:** Reviewed monthly. Projects without commits or issue activity in 90 days move to Stale.
- **Claim correction:** If you find a claim here that doesn't match reality, please open an issue on `AreteDriver/AreteDriver`.

---

*This file exists because the Senior Engineer Review found a gap between "30+ active projects" and verifiable evidence. The honest count is 5 active, 14 stale, 2 archived.*
