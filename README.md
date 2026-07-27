<!--
  PINNED REPO SUGGESTIONS (set via Profile > Customize your pins), in this order:
  1. mcp-bigquery-evals       - MCP + evals + NL-to-SQL, the differentiator
  2. rag-document-qa          - most recently active, citation-grounded RAG + retriever evals
  3. trustbench               - eval/production-readiness harness, pairs with #1
  4. Cargo-Concierge          - full-stack agentic product (Next.js + Mastra + Postgres)
  5. street-view-plate-blurring - trained CV model with real metrics (mAP@0.5 0.78)
  6. youtube-shorts-performance-prediction - honest negative result, leakage forensics
-->

# Umarfarook Gurramkonda

**AI / ML Engineer at HypeOn AI** — production LLM systems: multi-stage orchestration, RAG, NL-to-SQL, and the evals that keep them honest. Bangalore, India.

[Portfolio](https://umarfarook-ai.vercel.app) · [LinkedIn](https://www.linkedin.com/in/umarfarook-gurramkonda/) · [umarfarook0yt@gmail.com](mailto:umarfarook0yt@gmail.com)

---

## What I do

I build the messy middle of applied AI: agent orchestration, retrieval that returns the right thing, NL-to-SQL with cost guardrails, and the observability that keeps it all running in production. Strong Python (FastAPI), end-to-end ownership on GCP and AWS, and a bias toward systems that survive contact with real users.

I care about **evals before scale**: if you can't measure an agent's behavior, you can't improve it. Most of my open-source work exists to make LLM behavior measurable.

## Projects worth your time

**Agent infrastructure and evals**

- [**mcp-bigquery-evals**](https://github.com/Umarfarook1/mcp-bigquery-evals) — MCP server that lets agents explore BigQuery safely: 7 read-only tools, mandatory dry-run cost caps, structured error codes agents can self-correct on, and a Spider/BIRD-style NL-to-SQL eval harness. Published on [PyPI](https://pypi.org/project/mcp-bigquery-evals/).
- [**trustbench**](https://github.com/Umarfarook1/trustbench) — production-readiness harness for AI customer-support agents: versioned golden sets, eight trust metrics (five LLM-judged, three deterministic), and McNemar-tested per-intent regression detection. The Cohen's kappa function for judge-versus-human calibration is written and tested, but no hand-labelled set exists to run it against yet. 82 offline tests (green CI), zero API calls needed.
- [**rag-document-qa**](https://github.com/Umarfarook1/rag-document-qa) *(in development)* — retrieval-augmented document Q&A with citation-grounded answers; vector store, embedder and reranker are pluggable via Protocol. The retriever eval harness computes Recall@K, MRR and nDCG@10 and has not been run against a benchmark yet. 126 tests pass offline with no model download, no network and no API key.

**Applied agent product**

- [**Cargo-Concierge**](https://github.com/Umarfarook1/Cargo-Concierge) — agentic freight-forwarder copilot: free-form quote request in, ranked airline options and a draft response out. Hand-labelled ablation: 14/15 exact-match on the six graded fields over 15 cases, and removing the rules block from the prompt costs 33 points. Next.js + Mastra + Postgres. [Live demo](https://cargo-concierge.vercel.app).

**Applied ML and analysis**

- [**street-view-plate-blurring**](https://github.com/Umarfarook1/street-view-plate-blurring) — YOLOv8n license-plate detector (mAP@0.5 0.782, recall 0.739 on a 1,073-image val split) driving a recall-first Gaussian-blur redaction pipeline.
- [**youtube-shorts-performance-prediction**](https://github.com/Umarfarook1/youtube-shorts-performance-prediction) — a rigorous negative result: no pre-publish feature predicts Shorts engagement above chance, and the one "95% accurate" model is a leakage trap (permutation test p = 0.955).
- [**ipl-data-analysis**](https://github.com/Umarfarook1/ipl-data-analysis) — 1,095 IPL matches with chronologically computed venue-history features and match-outcome models that top out at ROC-AUC 0.547, which does not separate from a coin flip on a 273-match test split.

**ML from first principles** *(work in progress — building the stack a layer down from the APIs)*

- [**Nano-LLM-from-scratch**](https://github.com/Umarfarook1/Nano-LLM-from-scratch) — GPT-2 124M reproduction in PyTorch with RoPE, RMSNorm, SwiGLU, KV-cache.
- [**Triton-attention-kernels**](https://github.com/Umarfarook1/Triton-attention-kernels) — fused Triton kernels for the transformer hot path, to be benchmarked against `torch.SDPA`.
- [**Tiny-diffusion**](https://github.com/Umarfarook1/Tiny-diffusion) — DDPM with classifier-free guidance and a DDIM sampler, written from scratch, with 111 offline tests. The MNIST CPU smoke run is reported with the numbers it actually produced, including a deliberately unflattering smoke FID and a plain statement that the samples are not digits yet.
- [**DPO-on-my-LLM**](https://github.com/Umarfarook1/DPO-on-my-LLM) — SFT to DPO post-training with a position-swap LLM judge. Designed and written up; no code yet.

## Production work (closed source)

- **Conversational research agent** (HypeOn AI) — multi-stage routing (chitchat / factual / research), SSE streaming, session memory, idempotent retries, Pydantic-validated outputs, prompt-injection guardrails, Prometheus metrics.
- **NL-to-SQL over BigQuery** (HypeOn AI) — schema discovery, synonym matching, dry-run cost caps, multi-provider routing with fallback; built so non-technical operators can query the warehouse.
- **Clinical chat assistant** (Synclovis Systems) — RAG over clinical PDFs with chunking, metadata filtering, and guardrails against unsupported answers.
- **AI inventory platform** (freelance) — LLM invoice extraction, demand forecasting, real-time stock alerts for a retail client.

## Stack

**Python** (FastAPI, Pydantic, SQLAlchemy) · **PyTorch** · **TypeScript** · LangChain · FAISS · sentence-transformers · PostgreSQL · Redis · BigQuery · GCP · AWS · Docker · GitHub Actions · Prometheus

## Experience

| When | Role | Where |
|---|---|---|
| Oct 2025 – now | Founding ML Engineer | HypeOn AI |
| Oct 2024 – Sep 2025 | Freelance ML / AI Engineer | Independent |
| Jun 2024 – Sep 2024 | Backend Developer Intern | Synclovis Systems |
| 2020 – 2024 | B.Tech, Computer Science | K.S.R.M College of Engineering, JNTU Anantapur — CGPA 8.14 |

## How I work

- **Tradeoffs over tools** — pick by constraint, not hype.
- **Evals before scale** — a bad eval beats no eval.
- **Data quality over model swapping** — a new model rarely fixes bad inputs; retrieval and prompt structure compound.
- **Ship narrow, then expand** — one user, one workflow, working end-to-end.

---

Open to conversations about production LLM systems, RAG, evals, and ML systems.

**[umarfarook-ai.vercel.app](https://umarfarook-ai.vercel.app)** · [LinkedIn](https://www.linkedin.com/in/umarfarook-gurramkonda/) · [umarfarook0yt@gmail.com](mailto:umarfarook0yt@gmail.com)
