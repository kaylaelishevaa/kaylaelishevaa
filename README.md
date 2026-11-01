## Hi! I'm Kayla 👋

Year 2 Computer Science at **Monash University Malaysia** (Jul 2026 – Jul 2028) ·
[kaylasiwi.com](https://kaylasiwi.com) · [LinkedIn](https://www.linkedin.com/in/kayla-elisheva-siwi/) · kaykayelisheva@gmail.com

### About me
From Feb to Jul 2026 I was the only engineer at Coldwell Banker Indonesia, designing and
operating production LLM systems the agent team used daily: a WhatsApp listing parser
(**326 of 357** parsed listings went live, measured in production), a chat-analyst →
**33-tool** WhatsApp gateway → CRM pipeline over **220k+** messages with a human confirming
every write and a watchdog with no LLM in it, and a zero-downtime Laravel → NestJS migration
(~670 tests). The brokerage is my father's company, which is why everything here is measured
and the public extracts are runnable.

Since September 2026 I have been moving toward perception that helps people in physical
space: pose-estimation safety (EarlyEye, below) and, from mid-November, a Monash research
placement putting posture and facial-expression recognition on a Unitree Go2 quadruped.

I care about systems that hold up under real users, and about publishing the misses as
well as the hits.

### Selected work

| | |
|---|---|
| **[real-estate-ai-platform](https://github.com/kaylaelishevaa/real-estate-ai-platform)** | Runnable open-source extract of the production listing parser — free-form WhatsApp → validated structured listings, with a measurable LLM-correctness eval harness that runs with no network and no API key. **[▶ Live demo](https://honest-balance-production.up.railway.app/parse)** |
| **[chat-to-crm](https://github.com/kaylaelishevaa/chat-to-crm)** | Case study: a multi-agent LLM pipeline (chat analyst → WhatsApp gateway → CRM) with a deterministic no-LLM watchdog — 220k+ messages processed, 0 records written without human confirmation. Includes a [deep dive on the gateway's guardrails](https://github.com/kaylaelishevaa/chat-to-crm/blob/main/docs/gateway-deep-dive.md). |
| **[EarlyEye](https://github.com/ShariqNauman/taylors-hack)** | Dormathon 2026 (top 9 of 90 teams). Pose-based CCTV early warning for aggression in school hostels: YOLO-pose → LightGBM + 1D-CNN ensemble, AUC 0.935 on a 470-clip hold-out, with a live alert queue and guard app. Team of four; I owned the Next.js dashboard, the scope and the pitch (163 of the repo's 213 commits). **[▶ Live](https://earlyeye.vercel.app)** |
| **[pulse-case-study](https://github.com/kaylaelishevaa/pulse-case-study)** | Real-time WhatsApp event ingestion & alerting: exactly-once capture, idempotent fan-out, fail-closed scope gate, integration suite against a real Postgres. |
| **[mcp-connector-factory](https://github.com/kaylaelishevaa/mcp-connector-factory)** | A hardened MCP-server skeleton forked per backend — two Claude connectors with deliberately different security postures, 348 tests. |
| **[latchkey](https://github.com/kaylaelishevaa/latchkey)** | Passwordless login that survives the in-app-browser → system-browser cookie-jar handoff; a bug I could only see on a phone, pulled out into a runnable demo. |
| **[recap-ai](https://github.com/kaylaelishevaa/recap-ai)** | Meeting audio or transcript → summary, decisions, action items; runs end-to-end with zero API keys via a deterministic mock mode. **[▶ Live demo](https://recapai-web-production.up.railway.app)** |

### Stack

- **Languages:** TypeScript · Python · SQL · C++ · Java · R
- **Backend:** NestJS · Fastify · FastAPI · Node.js · MySQL · PostgreSQL · Prisma · Redis · BullMQ
- **Frontend:** Next.js · React · Tailwind · Ant Design
- **AI/ML:** Anthropic (Claude) · OpenAI · tool-calling · MCP · structured output · LLM evals · pose estimation (YOLO-pose) · LightGBM
- **Infra:** Docker · GitHub Actions · nginx · Cloudflare · AWS S3 · DigitalOcean · Vercel
