## Haneef Shaik — AI Engineer

I build AI products end to end: multi-agent systems, RAG and semantic search, and the backend
platforms they run on.

Founding engineer at Adya.ai, four years in. I lead a team of 7, and the AI products I've
architected there are used by 10,000+ people.

### In production

- **AI software-engineering platform.** Natural language in, a working React, Next.js or React
  Native app out, through a multi-agent pipeline: plan, implement, verify, review, deploy.
  13,000+ applications generated. Build verification with targeted re-generation took agent
  build failures to near zero.
- **Semantic search over 8.8M+ products.** Python embedding pipelines on Azure OpenAI, FastAPI
  services, Weaviate. I owned the embedding strategy, index design and retrieval tuning.
- **One routing layer for six model providers.** OpenAI, Claude, Gemini, DeepSeek, Ollama and
  OpenRouter, with per-request model selection and automatic fallback.
- **Multi-tenant workspaces**, isolated and provisioned automatically on Docker and Fly.io.

That code is private. These public repos show how I work:

| Project | What it shows |
|---|---|
| **[Dashboard Agent](https://github.com/Haneef-Shaik/zocket)**<br>[live demo](https://zocket-nine.vercel.app) | Ask about ad performance in plain English and get a number you can defend. Every answer carries its plan, its SQL, the rows behind it, and what was wrong with the data. The model plans and narrates; a validator, a deterministic SQL compiler and DuckDB produce the number. 108 tests, no API key needed to run them. |
| **[SuperAgent](https://github.com/Haneef-Shaik/multi-agent-architecture)** | Work in progress. A supervisor model plans each request as a task DAG, and a scheduler in code runs specialist agents (planning, coding, testing, review and others) in parallel waves. Each agent has its own tool allowlist and works inside a per-project Docker container, and a browser IDE streams the work. Next.js 16, Vercel AI SDK, MongoDB, dockerode. |
| **[FitLog](https://github.com/Haneef-Shaik/fitness_app)** | Fitness and nutrition tracker: React Native (Expo) app, FastAPI and PostgreSQL on Supabase. The domain rules run twice, in TypeScript on the device and in Python on the server, and shared JSON test vectors in CI keep the two in agreement. AI food-photo analysis runs on its own worker, so a slow model call never blocks a workout from saving. |
| **[Carrier Integration Service](https://github.com/Haneef-Shaik/carrier-integration-service)**<br>[live demo](https://cybership.haneef.in) | The UPS Rating API behind a carrier-agnostic interface: OAuth 2.0 client credentials with token caching, Zod validation at the boundary, typed errors, and a demo mode that runs without credentials. Next.js 15, TypeScript. |

### Stack

**AI:** multi-agent orchestration, RAG, embeddings, vector search, MCP, multi-model routing ·
OpenAI, Azure OpenAI, Claude, Gemini, DeepSeek, Ollama<br>
**Backend:** Go, Node.js, Python, TypeScript, FastAPI, Express, REST, microservices<br>
**Data:** PostgreSQL, MongoDB, Redis, Weaviate, Milvus, Elasticsearch, DuckDB<br>
**Frontend:** React, Next.js, React Native<br>
**Infra:** Docker, AWS, Fly.io, CI/CD

### Contact

Open to AI engineering roles, remote or relocating to the UAE.

[hello@haneef.in](mailto:hello@haneef.in) · [LinkedIn](https://www.linkedin.com/in/haneef2002) · [haneef.in](https://haneef.in)
