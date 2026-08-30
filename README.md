## Hi! I'm Kayla 👋

### About Me
Computer Science undergrad at Monash University. I recently wrapped a software engineering
internship at Coldwell Banker Indonesia, where I designed and operated production AI systems
the agent team used daily — a multi-agent pipeline that turns WhatsApp conversations into a
trustworthy CRM, guarded by a deterministic watchdog, plus internal tooling over a
~10k-listing database.

I care about backend systems that hold up under real users, not demos.

### Selected work

| | |
|---|---|
| **[chat-to-crm](https://github.com/kaylaelishevaa/chat-to-crm)** | Case study: a multi-agent LLM pipeline (chat analyst → WhatsApp gateway → CRM) with a deterministic no-LLM watchdog — 220k+ messages processed, 0 records written without human confirmation. Includes a [deep dive on the gateway's guardrails](https://github.com/kaylaelishevaa/chat-to-crm/blob/main/docs/gateway-deep-dive.md). |
| **[real-estate-ai-platform](https://github.com/kaylaelishevaa/real-estate-ai-platform)** | Runnable open-source extract of the production listing parser — free-form WhatsApp → validated structured listings, with a measurable LLM-correctness eval harness. **[▶ Live demo](https://honest-balance-production.up.railway.app/parse)** |
| **[pulse-case-study](https://github.com/kaylaelishevaa/pulse-case-study)** | Real-time WhatsApp event ingestion & alerting: exactly-once capture with idempotent fan-out, ~460 tests against a real Postgres. |
| **[mcp-connector-factory](https://github.com/kaylaelishevaa/mcp-connector-factory)** | A hardened MCP-server skeleton forked per backend — two Claude connectors with deliberately different security postures, 348 tests. |

### Stack

- **Languages:** TypeScript · Python · SQL
- **Backend:** NestJS · Fastify · FastAPI · Node.js · MySQL · PostgreSQL · Prisma · Redis
- **Frontend:** Next.js · React · Tailwind · Ant Design
- **Async:** BullMQ · WebSockets · background workers
- **AI/LLM:** Anthropic (Claude) · OpenAI · tool-calling · MCP · structured output · LLM evals
- **Infra:** Docker · GitHub Actions · nginx · Cloudflare · AWS S3 · DigitalOcean
