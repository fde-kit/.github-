# FDE Kit

**The toolkit for forward-deployed and Applied AI engineers shipping production LLM systems.**

Most AI content is news. This isn't. FDE Kit is graph-derived signal, working
reference implementations, and an open-source security layer — built for the
engineers who own the gap between model capability and shipped systems.

---

## What lives here

### 🛡️ [waf](https://github.com/fde-kit/waf) &nbsp;·&nbsp; GenAIWAF
Open-source web application firewall for LLM systems. Prompt-injection defense,
output filtering, tool-call sandboxing, cost guards. Apache-2.0.
*Status: in development — first release with newsletter Issue #3.*

### 🧪 mvp-* &nbsp;·&nbsp; Reference implementations
Runnable, KPI-rooted reference MVPs published alongside the Friday long-form.
Synthetic data, eval harness, Docker, README. DuckDB by default; Snowflake
variants for the enterprise crowd. MIT.

Queued:
- `mvp-invoice-triage` — multi-tool agent over synthetic AP data, routing-accuracy eval
- `mvp-rag-versioned-docs` — RAG over evolving documentation with version-aware retrieval
- `mvp-cost-bounded-agent` — hard budget caps with graceful degradation
- `mvp-prompt-injection-redteam` — attack harness, pairs with GenAIWAF
- `mvp-agent-eval-harness` — golden set, regression, drift detection for 5-tool agents

---

## The newsletter

3-4 short posts/week, free. One Friday long-form, paid after the first month.
Every post: one idea, one paragraph, named example or number or repo.

→ **[fde-kit.ai](https://fde-kit.ai)**

---

## Who this is for

Forward-deployed engineers and applied AI engineers shipping production LLM
systems. Not researchers, not generalists, not investors. International
framing — non-SF labs included, USD prefix, no Bay Area assumptions.

---

## Author

By Luis Herrera — solutions architect, ex-{redis,pivotal,google}, EMEA.
Reach: luis at fde-kit.ai

---

*Launching <<MAY 19, 2026>>. 
