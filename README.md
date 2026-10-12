<h1 align="center">Aaditya Sinha</h1>

<p align="center">
Full-stack engineer (2.5 yrs) building LLM products end to end: React/Next.js front ends, Python/FastAPI and Node backends on PostgreSQL, and the AI layer in between (RAG, agents, evaluation, observability).<br/>
Four years of merged pull requests in open source, mostly the Zowe project under the Linux Foundation.<br/>
Remote · Ghaziabad, India · <b>Available to join immediately</b>
</p>

<p align="center">
  <a href="mailto:aadityasinha009@gmail.com"><img src="https://img.shields.io/badge/Email-aadityasinha009%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://www.linkedin.com/in/aaditya-sinha-9a5490137/"><img src="https://img.shields.io/badge/LinkedIn-aaditya--sinha--9a5490137-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://twitter.com/AadityaSinha16"><img src="https://img.shields.io/badge/X-@AadityaSinha16-000000?style=flat&logo=x&logoColor=white" alt="X"/></a>
</p>

## Open source

| Project | Organisation | Merged PRs | What I contributed |
|---|---|:--:|---|
| [zowe-client-python-sdk](https://github.com/zowe/zowe-client-python-sdk/pulls?q=is%3Apr+author%3Aaadityasinha-dotcom+is%3Amerged) | Zowe · Open Mainframe Project (Linux Foundation) | **21** · 2022 → Sep 2026 | Nested team configuration with JSON-schema validation ([#144](https://github.com/zowe/zowe-client-python-sdk/pull/144)) · schema validation of `zowe.config.json` ([#192](https://github.com/zowe/zowe-client-python-sdk/pull/192)) · profile properties from env vars ([#200](https://github.com/zowe/zowe-client-python-sdk/pull/200)) · profile merge order matched to the Node SDK ([#203](https://github.com/zowe/zowe-client-python-sdk/pull/203)) · SDK APIs as context managers ([#283](https://github.com/zowe/zowe-client-python-sdk/pull/283)) · `responseTimeout` ([#369](https://github.com/zowe/zowe-client-python-sdk/pull/369)) · `commentjson` → `json5` ([#374](https://github.com/zowe/zowe-client-python-sdk/pull/374)) · USS path URI encoding ([#415](https://github.com/zowe/zowe-client-python-sdk/pull/415)) · z/OS jobs and files methods (create, cancel, delete, hold/release, change class, USS file and data set creation) |
| [zowe-cli](https://github.com/zowe/zowe-cli/pull/2478) · [imperative](https://github.com/zowe/imperative/pull/914) | Zowe (TypeScript) | **3** | Exposed `buildPrefix` to replace a `moment.format` dependency · exported `AppSettings` and `IAuthHandlerApi` for downstream CLIs |
| [airbyte](https://github.com/airbytehq/airbyte/pull/10312) | Airbyte | **2** | Chargebee source connector: coupons and transactions streams |
| [ploomber](https://github.com/ploomber/ploomber/pull/629) | Ploomber | **2** | CLI "did you mean" suggestions with `difflib` · clearer missing-pipeline error |
| [deeplake](https://github.com/activeloopai/deeplake/pull/1597) | Activeloop | **1** | Additional image compression formats, incl. read-only formats |
| [cve-bin-tool](https://github.com/ossf/cve-bin-tool/pull/2289) | OpenSSF | **1** | mypy fixes in format checkers |
| [vorta](https://github.com/borgbase/vorta/pull/1626) | BorgBase | **1** | Clear the log view after a successful backup |
| [autoai](https://github.com/blobcity/autoai/pull/129) | BlobCity | **4** | Gamma, RadiusNeighbors and PassiveAggressive regressors, RadiusNeighbors classifier |

LFX Mentorship 2023 (Zowe Python SDK). Full list with links: [GitHub-Contributions](https://github.com/aadityasinha-dotcom/GitHub-Contributions) · every merged PR outside my own repos: [search](https://github.com/pulls?q=is%3Apr+author%3Aaadityasinha-dotcom+is%3Amerged+-user%3Aaadityasinha-dotcom)

## Projects

| Project | Stack | What it does |
|---|---|---|
| [llm-metrics](https://github.com/aadityasinha-dotcom/llm-metrics) <br/> <a href="https://github.com/aadityasinha-dotcom/llm-metrics/actions/workflows/ci.yml"><img src="https://github.com/aadityasinha-dotcom/llm-metrics/actions/workflows/ci.yml/badge.svg" alt="CI"/></a> | Python 3.9–3.13, httpx, mypy strict, MIT | Python SDK for tracing LLM applications. `@observe` decorator for sync, async and streaming calls; nested calls join the enclosing trace. Never blocks the caller (background thread, bounded buffer), never crashes the host app. OpenAI, Anthropic and LangChain extras. |
| [llmobserve](https://github.com/aadityasinha-dotcom/llmobserve) | FastAPI, PostgreSQL, Alembic, React, Docker, Vercel | The self-hostable backend and dashboard the SDK reports to. Scoped API keys, idempotent batch ingest, cost frozen at write time, partitioned trace tables, Google sign-in, dashboard with attribution filters and per-call token detail. |
| [rag-eval](https://github.com/aadityasinha-dotcom/rag-eval) | Python, LlamaIndex, PostgreSQL/pgvector, Docker | Retrieval quality as an engineering metric. Document Q&A over technical docs with deterministic chunk identity, a hand-labelled golden set, config-driven evaluation runs scored on recall@k, MRR and nDCG, and a written trade-offs doc. Every query instrumented with llm-metrics. |

## Stack

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript"/>
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL"/>
</p>
<p>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js"/>
  <img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white" alt="Redux"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
</p>
<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js"/>
  <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/Django_REST-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django REST Framework"/>
</p>
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
  <img src="https://img.shields.io/badge/pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="pgvector"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
</p>
<p>
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/LlamaIndex-6C3FC5?style=for-the-badge" alt="LlamaIndex"/>
  <img src="https://img.shields.io/badge/RAG_%26_LLM_Evaluation-1F6FEB?style=for-the-badge" alt="RAG and LLM evaluation"/>
  <img src="https://img.shields.io/badge/LLM_Observability-1F6FEB?style=for-the-badge" alt="LLM observability"/>
</p>
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Google Cloud"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
</p>

## Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=aadityasinha-dotcom&show_icons=true&include_all_commits=true&theme=default&hide_border=true" alt="GitHub stats" height="165"/>
</p>
