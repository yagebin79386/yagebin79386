# Ruiqi Tan

**AI-Native Superindividual Product Systems Builder** · [Silicon Awakening](https://siliconawakening.tech)

I build and document **governed AI systems** that let one person research, decide, build, market, and
operate real products. The through-line in everything below is the same: agents do the work, but every
outward-facing or irreversible step passes a **human-gated approval** with a decision record behind it.

---

### What I actually work on

**Governed agent operating system.** A multi-agent runtime where scheduled work is declared in a
manifest and supervised by a registry-and-verifier pair, changes reach production through GitOps
reconciliation with syntax gates and automatic rollback, and any externally-visible action is stopped
at a fail-closed approval card. Expiry means *not approved* — a timeout never reads as consent.

**Human-gated decision surface.** Approval cards, typed decision records, and blocked-task escalation,
so an autonomous system can run unattended without ever silently deciding something a human should own.

**Provenance-first content and evidence.** Marketing and research output grounded in a product-context
document and an entity graph, with claims traceable to artifacts rather than to model recall.

**Measurement as a first-class lane.** Weekly deterministic quality rollups gate whether an expensive
LLM review is warranted at all; delayed outcome signals only influence anything after enough
observations exist. Quiet weeks cost nothing.

### Things I have shipped or run

| | Stage |
|---|---|
| **SA-OS + Hermes** — governed multi-agent operating system, running my own operations daily | implemented |
| **Wakeworth** — SME valuation and matchmaking platform | production |
| **AI Educator** — structured problem-solving and learning system | production |
| **Mindscast** — product-grounded marketing content platform | in development |
| **Vigaro** — multi-agent dynamic defense | architecture stage |

Most of these run as private products. What I open here are the **mechanisms** — the governance,
scheduling, and approval machinery that makes one-person operation of several products survivable.

### Public work

- **[schedule-sentinel](https://github.com/yagebin79386/schedule-sentinel)** — registry plus verifier
  that proves every scheduled machine is still alive, and catches drift between the registry and the
  scheduler in both directions. Extracted from the operations layer above. Stdlib only.
- **[awesome-governed-agents](https://github.com/yagebin79386/awesome-governed-agents)** — curated
  tools and prior art for agents whose consequential actions pass approval gates, policy checks, and
  auditable decision records.
- **[openclaw-disk-cleanup](https://github.com/yagebin79386/openclaw-disk-cleanup)** — governed
  disk-reclaim agent skill for self-hosted VPS ops; dry-run by default, audited reclaim report.

*More mechanism slices are being prepared for release.*

---

📍 Luxembourg · ✍️ [siliconawakening.tech](https://siliconawakening.tech) ·
💼 [LinkedIn](https://www.linkedin.com/in/ruiqi-tan-5708a358/)
