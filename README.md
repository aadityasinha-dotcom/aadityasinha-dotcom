# Aaditya Sinha

Full-stack engineer (2.5 yrs) building LLM products end to end: React/Next.js front ends, Python/FastAPI and Node backends on PostgreSQL, and the AI layer in between (RAG, agents, evaluation, observability).

## What I've built

**[llm-metrics](https://github.com/aadityasinha-dotcom/llm-metrics)** · Python SDK for tracing LLM applications
`@observe` decorator for sync, async and streaming calls; nested calls join the enclosing trace. Never blocks the caller (background thread, bounded buffer), never crashes the host app. OpenAI, Anthropic and LangChain extras. CI across Python 3.9–3.13, strict mypy, MIT.

**[llmobserve](https://github.com/aadityasinha-dotcom/llmobserve)** · the self-hostable backend and dashboard the SDK reports to
FastAPI + PostgreSQL ingest with scoped API keys, idempotent batch writes, cost frozen at write time, partitioned trace tables (Alembic), Google sign-in, and a React dashboard with attribution filters and per-call token detail. Deployed on Vercel.

**[rag-eval](https://github.com/aadityasinha-dotcom/rag-eval)** · retrieval quality as an engineering metric
Document Q&A over technical docs on PostgreSQL/pgvector with LlamaIndex. Deterministic chunk identity, a hand-labelled golden set, config-driven evaluation runs scored on recall@k, MRR and nDCG, and a written trade-offs doc. Every query instrumented with llm-metrics.

**Open source:** two merged PRs in the Zowe Python SDK (Linux Foundation / Open Mainframe Project): nested team configuration with JSON-schema validation ([#144](https://github.com/zowe/zowe-client-python-sdk/pull/144)), job create/delete/cancel and USS file creation ([#186](https://github.com/zowe/zowe-client-python-sdk/pull/186)). LFX Mentorship 2023.

## Stack

`TypeScript` `Python` `React` `Next.js` `Node.js` `FastAPI` `Django REST Framework` `PostgreSQL` `pgvector` `LangGraph` `LlamaIndex` `Docker` `GCP` `GitHub Actions` `Linux`

## Contact

aadityasinha009@gmail.com · [linkedin.com/in/aaditya-sinha-9a5490137](https://www.linkedin.com/in/aaditya-sinha-9a5490137/) · [@AadityaSinha16](https://twitter.com/AadityaSinha16)
