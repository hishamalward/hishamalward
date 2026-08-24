### Hisham Al-Ward

AI platform and automation engineer in Toronto. I build agentic AI and automation systems for enterprises, and I measure whether they were worth building.

**Three things I care about**

- **Agentic governance:** AI agents writing production code behind spec gates, blast-radius guardrails, and quality gates that make violations mechanical rather than discouraged.
- **Automation with receipts:** value-stream baselines, honest ROI models, and measured-vs-projected kept strictly separate.
- **LLM engineering:** per-task model routing, prompt evals calibrated against human labels, and cost engineering. Listenality's enrichment pipeline runs at ~$0.36 per 1,000 tracks because the evals said it could.

**Public work** (MIT, each with a `docs/learning/how-it-works` tour for whoever owns it next)

| Repo | What it does |
|---|---|
| [evalmine](https://github.com/hishamalward/evalmine) | Scores a model change on your own tasks: pairwise LLM judge with position swap, Cohen's kappa against your labels, schema and execution checks, latency, cost from a pinned price table. Refuses to headline a win-rate its judge cannot defend. Three-tool MCP server so an agent can run the evals mid-task. |
| [mcpclerk](https://github.com/hishamalward/mcpclerk) | A governance proxy for MCP servers: per-tool allowlist (deny by default), human approval for write-class tools, quotas, secret redaction before logging, and a hash-chained audit log that verifies. |
| [agentkeel](https://github.com/hishamalward/agentkeel) | A framework for shipping production code with AI coding agents: work priced by size, spec-first, four gates with named owners, blast radius bounded by Claude Code hooks. |
| [agent-slots](https://github.com/hishamalward/agent-slots) | Per-agent isolation for parallel coding agents: one integer derives a worktree, a database, two ports, and a job-queue schema. |
| [toilscan](https://github.com/hishamalward/toilscan) | Claude Code plugin that scans Git history for recurring developer toil and recommends the smallest automation that removes it. Every finding cites its commits. |

**Background:** A decade+ across networking, cloud consulting, and security automation. Azure Solutions Architect Expert, AWS Solutions Architect, Terraform, CCNP.

Toronto · [LinkedIn](https://www.linkedin.com/in/hishamalward)
