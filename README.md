### Hi, I'm Mohamed Grine (`@grinem`) 👋

**Automation & AI Workflow SRE** specializing in production reliability, incident post-mortems, and silent-failure prevention across **n8n**, **Dify**, **Activepieces**, **Make**, **Shopify Webhooks**, and **Docker**.

---

### 🛡️ Featured Open-Source & Reliability Tools

- **[`grinem/hooktriage`](https://github.com/grinem/hooktriage)** *(MIT)* — Zero-Trust CLI & MCP Server (`npx -y github:grinem/hooktriage scan` / `--mcp`, 0 bytes uploaded).
- **[`grinem/n8n-ai-watchdog`](https://github.com/grinem/n8n-ai-watchdog)** *(MIT)* — Zero-Trust 3-node n8n Error Workflow with local secret scrubbing (API keys, JWTs, Bearer tokens, PII) and root-cause alert classification for `429`, `401/403`, webhook drops, and empty AI outputs.
- **[`grinem/n8n-production-incident-fixes`](https://github.com/grinem/n8n-production-incident-fixes)** — Live engineering archive of 100+ diagnosed production failures & verified recovery patterns.
- **🌐 Live Knowledge Base & Client-Side Audit**: [https://hooktriage.com](https://hooktriage.com) *(in-browser workflow static audit + case study archive)*

---

### ⚙️ Core Production Failure Patterns I Document & Fix
- **Silent AI Agent & LLM Drops**: Workflows ending "green" while returning `[]`, truncated JSON, or hitting token/tool loops.
- **Shopify / Stripe Webhook Silences**: 5-second webhook cutoffs, missing idempotency keys, and HMAC verification drift.
- **OAuth2 & Rate-Limit Deadlocks**: Concurrent n8n/Make token refresh collisions and HTTP `429` cascading retries.
- **Self-Hosted Worker Reliability**: Postgres/Redis queue exhaustion, reverse-proxy timeout disconnects, and memory leaks.
