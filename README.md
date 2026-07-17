### Hi, I'm Kshitij 👋

Early-career engineer interested in building LLM-backed systems with backend depth - orchestration, retrieval, observability, and thinking about where AI should and shouldn't make decisions.

Open to Applied AI / AI Engineer roles


### Experience

**Hiver** - AI Intern · Dec 2025 – Jun 2026

- Architected a 5-phase pipeline to identify AI adoption opportunities across the customer base, running 21 recipes across 5 batched GPT-5.4 calls with retry backoff, signal-keyword filtering, and PII-aware email cleaning.

- Designed an SQS-based orchestration pipeline computing per-usergroup AI usage metrics across 30/60/90-day windows, publishing feature-wise JSON snapshots to S3 with Redis-precomputed aggregations.

- Built an end-to-end AI automation testing platform (React + FastAPI + Playwright) with automated execution of a 15-step Chat Agent scenario and per-run artifact capture (replay video + failure screenshots).

**[Ernst & Young](https://www.ey.com)** - Generative AI Intern · Sep 2024 – Nov 2024

- Built a document Q&A RAG pipeline using LangChain, Stella embeddings selected via MTEB leaderboard, and Chroma, with PyMuPDF text extraction, chunking, and top-k retrieval for grounded source-cited answers.
  
- Benchmarked local Llama 3.1 against Groq-hosted inference on the same pipeline, evaluating the privacy vs. latency tradeoff for sensitive document workloads.

**Kreativstorm** - Data Analysis Trainee · Sep 2024 – Oct 2024

- Cleaned and analysed 8+ datasets using IBM SPSS, resolving inconsistencies to improve data reliability and produce decision-ready outputs.

- Collaborated with a cross-functional remote team to streamline reporting workflows and deliver data-driven project insights.


### What I've built

🤖 **[Dossier](https://github.com/KshitijAng/Dossier)** - 
Agentic AI research assistant built on a 5-node LangGraph state 
machine (planner → searcher → reader → synthesizer → critic) 
with a bounded self-critique loop, citation-grounded reports, 
Langfuse observability, and a Next.js + MUI frontend. 
*[Live ↗](https://dossier-three-woad.vercel.app)*

🔍 **[Hybrid Search System](https://github.com/KshitijAng/Hybrid-RAG-with-pgvector-Cohere-Rerank-3.5)** - 
Hybrid retrieval over 5,753 chunks using dense + sparse search 
fused via RRF, Cohere rerank-3.5 cross-encoder, 
citation-grounded generation, and end-to-end Langfuse tracing. 
*[Article ↗](https://www.linkedin.com/pulse/building-hybridrag-what-i-learned-retrieval-reranking-angurala-pcetc/)*

✅ **[Vendor Onboarding Validator](https://github.com/KshitijAng/vendor-onboarding-validator)** - 
6-stage deterministic + LLM hybrid validation pipeline with hard 
FAIL vs soft WARN logic across 41 test cases. LLM restricted to 
borderline name-mismatch adjudication only - deterministic checks 
handle all upstream validation.

🎫 **[TicketSense](https://github.com/KshitijAng/TicketSense)** - Groq-powered LLM ticket triage processing 300 tickets in ~12 minutes, backed by layered async Python architecture and two-tier Postgres + Redis storage.


### Stack I work with


- **Languages:** Python · SQL
- **AI / LLM:** LangChain · LangGraph · Langfuse · RAG · 
  Pinecone · pgvector · Groq
- **Backend:** FastAPI · Pydantic · SQLAlchemy · SQS · 
  AWS (S3, Athena)
- **Databases:** PostgreSQL · Redis · MySQL · Elasticsearch
- **Infra:** Docker · Git


### What I'm focused on

- Agentic AI - LangGraph state machines, bounded self-critique 
  loops, tool-use orchestration
- Hybrid retrieval - dense + sparse fusion (RRF) and 
  cross-encoder reranking
- Deterministic-first AI design - LLMs for ambiguity, 
  deterministic logic for everything else
- LLM observability - Langfuse tracing across every node, 
  token cost and latency per request
- Citation-grounded generation - making LLM answers traceable 
  to source chunks


### Connect

[LinkedIn](https://www.linkedin.com/in/kshitijangurala/) · kshitijangurala903@gmail.com · [Linktree](https://linktr.ee/kshitijatech)
