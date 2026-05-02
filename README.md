<div align="center">

<a href="https://umarfarook-ai.vercel.app">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2800&pause=900&color=F5C26B&center=true&vCenter=true&width=720&lines=Umarfarook+Gurramkonda;AI+%2F+ML+Engineer+%E2%80%94+HypeOn+AI;Production+LLMs+%C2%B7+RAG+%C2%B7+Multi-stage+orchestration;umarfarook-ai.vercel.app" alt="Umarfarook Gurramkonda — AI Engineer" />
</a>

<br/>

[![Portfolio](https://img.shields.io/badge/portfolio-umarfarook--ai.vercel.app-F5C26B?style=flat-square&logo=vercel&logoColor=white&labelColor=1a1815)](https://umarfarook-ai.vercel.app)
[![LinkedIn](https://img.shields.io/badge/linkedin-umarfarook--gurramkonda-0A66C2?style=flat-square&logo=linkedin&logoColor=white&labelColor=1a1815)](https://www.linkedin.com/in/umarfarook-gurramkonda/)
[![Email](https://img.shields.io/badge/email-umarfarook0yt%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white&labelColor=1a1815)](mailto:umarfarook0yt@gmail.com)
[![Location](https://img.shields.io/badge/based%20in-Bangalore%2C%20India-9CA3AF?style=flat-square&logo=googlemaps&logoColor=white&labelColor=1a1815)](https://maps.app.goo.gl/)

</div>

<br/>

```yaml
role:        AI / ML Engineer @ HypeOn AI
focus:       Production LLM systems for D2C trend prediction
working_on:  BigQuery NL2SQL MCP Server  -  open-source eval infra
philosophy:  Tradeoffs over tools  -  evals before scale  -  ship narrow, then expand
```

<br/>

## About

I build the messy middle of applied AI — multi-stage orchestration, retrieval that
actually retrieves the right thing, NL-to-SQL with cost guardrails, and the
observability that keeps it running in production.

Strong **Python (FastAPI)**, end-to-end ownership across **GCP** and **AWS**, and
a bias toward systems that survive contact with real users.

<br/>

## Stack

<table>
<tr>
<td><b>Languages</b></td>
<td>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

</td>
</tr>
<tr>
<td><b>LLM &amp; AI</b></td>
<td>

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-1B72E8?style=flat&logo=googlegemini&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat&logo=meta&logoColor=white)

</td>
</tr>
<tr>
<td><b>Backend</b></td>
<td>

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat&logo=sqlalchemy&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

</td>
</tr>
<tr>
<td><b>Data &amp; ML</b></td>
<td>

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat&logo=googlebigquery&logoColor=white)

</td>
</tr>
<tr>
<td><b>Cloud &amp; Ops</b></td>
<td>

![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)

</td>
</tr>
</table>

<br/>

## Currently building

> **BigQuery NL2SQL MCP Server** &nbsp;·&nbsp; first project in a 5-project credibility series
>
> Open-source MCP server that lets agents query BigQuery in natural language with
> schema-aware grounding, cost guardrails, and a built-in eval harness so the
> behavior is measurable, not vibes-based.
>
> Roadmap: eval leaderboard → voice interview coach → research assistant → prod-LLM starter.

<br/>

## Selected work

<table>
<tr>
<td width="50%" valign="top">

#### Conversational Research Agent
`Python` · `FastAPI` · `LangChain`

Multi-stage routing (chitchat / factual / research) with **SSE streaming**, session memory, idempotent retries, Pydantic-validated outputs, prompt-injection guardrails, and Prometheus metrics.

</td>
<td width="50%" valign="top">

#### NL-to-SQL over BigQuery
`Python` · `BigQuery` · `Claude` · `Gemini`

Schema discovery, synonym matching, cost safety caps. Claude Haiku primary with Gemini fallback. Built for non-technical operators to query the warehouse without writing SQL.

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### AI-Powered Inventory Platform
`Python` · `Pandas` · `Scikit-learn` · `OpenAI`

LLM-based invoice extraction, real-time stock alerts, demand forecasting, and a visualization dashboard for business insight. Shipped for a retail client during freelance work.

</td>
<td width="50%" valign="top">

#### Clinical Chat Assistant
`LangChain` · `FAISS` · `OpenAI`

RAG over **500+** clinical PDFs with chunking, metadata filtering, and guardrails to reduce unsupported answers. Internal tool at Synclovis Systems.

</td>
</tr>
</table>

<br/>

## Experience

| When | Role | Where |
|---|---|---|
| `2025.10 → now` | **AI / ML Engineer** | HypeOn AI &nbsp;·&nbsp; D2C trend prediction |
| `2024.10 → 2025.09` | **Freelance ML / AI Engineer** | Independent |
| `2024.06 → 2024.09` | **Backend Developer Intern** | Synclovis Systems |
| `2020 → 2024` | **B.Tech, Computer Science** | K.S.R.M College / JNTU Anantapur &nbsp;·&nbsp; CGPA 8.14 |

<br/>

## How I think

| | |
|---|---|
| **Tradeoffs over tools** | Pick by constraint, not hype. Postgres + pgvector beats a managed vector DB until it doesn't. |
| **Evals before scale** | If you cannot measure it, you cannot improve it. A bad eval beats no eval. |
| **Data quality over model swapping** | A new model rarely fixes bad inputs. Retrieval and prompt structure compound. |
| **Infrastructure is the product** | Latency, cost, reliability are features users feel. The model is one component. |
| **Ship narrow, then expand** | One user, one workflow, working end-to-end. Tiny systems that ship beat grand systems that demo. |

<br/>

## Reach out

Open to collaboration on production LLM systems, RAG pipelines, evals, and applied AI infrastructure.

[**umarfarook-ai.vercel.app**](https://umarfarook-ai.vercel.app) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/umarfarook-gurramkonda/) &nbsp;·&nbsp; [umarfarook0yt@gmail.com](mailto:umarfarook0yt@gmail.com)

<sub>built quietly · shipping noisily</sub>
