### Hi, I'm Kshitij 👋

AI engineer building backend systems and LLM pipelines. Currently shipping multi-phase LLM workflows, AI adoption analytics, and chat-agent automation at **Hiver** — an AI-powered customer service platform.

Outside work, I build production-style side projects in backend + AI infrastructure to feel the rough edges of modern AI engineering hands-on.


### Experience

**[Hiver](https://hiverhq.com)** — AI Intern · Dec 2025 – Jun 2026

- Owned key AI Adoption/ROI initiatives across backend and frontend, leveraging Redis for precomputed metrics, integrating AI workflows powered by Elasticsearch, Gainsight, and MySQL, and shifting heavy aggregations to backend services.
- Architected a 5-phase AI Tasks Opportunity Pipeline, running 21 cookbook recipes across 5 batched LLM (GPT-5.4) calls, with retry backoff on 429s and rate-limit pacing; added signal-keyword evidence filtering for accuracy.
- Built an end-to-end AI automation testing platform for Chat Agents (React + FastAPI + Playwright), enabling automated execution of a 15-step happy-path scenario and per-run artifact lifecycle (replay video + failure screenshots).
- Designed and implemented a daily AI adoption pipeline that computes per-UG daily AI usage metrics separate from 30/60/90-day windows and publishes feature-wise JSON snapshots to S3 using SQS-based orchestration and batched processing.

**[Ernst & Young](https://www.ey.com)** — Generative AI Intern · Sep 2024 – Nov 2024

- Reduced LLM setup friction by scripting model provisioning and standardizing config across Llama 3.1 deployments, gaining hands-on exposure to Transformer architecture and open-source LLM tooling.
- Established a RAG-based Gen AI solution using LangChain, OpenAI, and Pinecone; tuned chunking and retrieval parameters to deliver contextually relevant responses on internal document queries.


### What I've built

🔍 **[HybridRAG](https://github.com/KshitijAng/Hybrid-RAG-with-pgvector-Cohere-Rerank-3.5)** — Hybrid-search RAG over technical documentation (pgvector + Postgres FTS + RRF + Cohere rerank-3.5) with citation-grounded answers and Langfuse traces. *[Article writeup ↗](PASTE_ARTICLE_URL_HERE)*

🎫 **[TicketSense](https://github.com/KshitijAng/TicketSense)** — LLM-powered support ticket triage with Pydantic structured outputs, two-tier storage (Postgres + Redis), and a Groq primary + fallback model setup. Processed 300 tickets in ~12 minutes with zero failures.

🧠 **[AI Hub](https://github.com/KshitijAng/AI-Hub-SpringBoot)** — Spring Boot 3.5 + React 19 chat & code-generation app on Spring AI + Groq, with reusable PromptTemplate definitions shared across routes.

📦 **[FlowVentry](https://github.com/KshitijAng/FlowVentry-Inventory-Management)** — Next.js 15 + MongoDB inventory app with cached MongoClient singleton and $text aggregation pipeline for relevance search.


### Stack I work with

- **Languages:** Python · Java · JavaScript · TypeScript · SQL
- **AI / LLM:** LangChain · Langfuse · Pydantic · Cohere · Groq · OpenAI
- **Backend:** FastAPI · Spring Boot · Spring AI · Next.js
- **Data:** PostgreSQL · pgvector · Redis · MongoDB · Elasticsearch
- **Infra:** Docker · Kubernetes · AWS · Kafka


### Connect

[LinkedIn](https://www.linkedin.com/in/kshitijangurala/) · kshitijangurala903@gmail.com

*Open to backend / AI engineering opportunities — Bengaluru, remote, or hybrid.*


### What I've been exploring lately

- Hybrid-search retrieval combining sparse + dense fusion (RRF) and cross-encoder reranking
- Citation-grounded LLM answers — making generation traceable to source chunks
- End-to-end LLM observability with Langfuse traces across retrieval and generation
- Multi-phase LLM pipelines with batched API calls, retry backoff, and rate-limit pacing
- AI automation testing for Chat Agents using React + FastAPI + Playwright
- AI adoption analytics pipelines built on SQS-based orchestration with feature-wise S3 snapshots
