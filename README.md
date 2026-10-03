<div align="center">

<!-- 🎬 HERO — Viewfinder HUD + Animated Gradient Name + Cycling Roles -->
<img src="./hero.svg?v=2" alt="Mayank Singh — AI/ML Engineer" width="100%"/>

<br/><br/>

</div>

## 🌐 My Portfolio Website

> **Explore the interactive web portfolio:** A modern, high-performance web experience showcasing systems architecture, model pipelines, engineering case studies, and interactive telemetry.

<div align="center">

[![Visit My Portfolio](https://img.shields.io/badge/Visit%20My%20Portfolio-22d3ee?style=for-the-badge&logo=vercel&logoColor=0d0e16)](https://mayank-portfolio-xi-wheat.vercel.app/)
&nbsp;
[![Live Demo](https://img.shields.io/badge/Live%20Deployment-mayank--portfolio--xi--wheat.vercel.app-a78bfa?style=for-the-badge&logo=googlechrome&logoColor=0d0e16)](https://mayank-portfolio-xi-wheat.vercel.app/)

<br/>

<a href="https://mayank-portfolio-xi-wheat.vercel.app/" target="_blank">
  <img src="./assets/portfolio-preview.png" alt="Mayank Singh — Live Portfolio Website Preview" width="100%" style="border-radius: 14px; border: 1.5px solid #262a42; box-shadow: 0 10px 30px rgba(0,0,0,0.5);" />
</a>

<br/>
<sub>⚡ Click the preview above to launch the live portfolio at <a href="https://mayank-portfolio-xi-wheat.vercel.app/">mayank-portfolio-xi-wheat.vercel.app</a></sub>

<br/><br/>

<!-- 🧠 DUAL CARDS: AI Systems & Architecture • Project Carousel & Telemetry -->
<img src="./about-life.svg?v=2" alt="Capabilities and Engineering Pillars" width="100%"/>

<br/><br/>

<!-- ⚛️ TECH STACK — Orbiting Systems & Sequential Glowing Chips -->
<img src="./stack.svg?v=2" alt="Tech Stack and Architecture" width="100%"/>

<br/><br/>

<!-- 🪪 DEVELOPER ID BADGE + ANALYTICS DASHBOARD -->
<img src="./id-dashboard.svg?v=2" alt="Developer ID and Analytics Dashboard" width="100%"/>

<br/><br/>

</div>

---

## 🚀 Flagship Engineering Projects

### 🛡️ [Tollgate — Multi-Tenant LLM Gateway](https://github.com/mayanksingh2745/Tollgate-a-multi-tenant-LLM-gateway-with-budgets-semantic-caching-and-cost-quality-routing)
> **Production-grade AI gateway architecture designed to eliminate runaway inference expenses, enforce hard multi-tenant spending limits, and maintain microsecond-level routing efficiency.**

[![GitHub Repo](https://img.shields.io/badge/Repository-Tollgate-22d3ee?style=for-the-badge&logo=github&logoColor=0d0e16)](https://github.com/mayanksingh2745/Tollgate-a-multi-tenant-LLM-gateway-with-budgets-semantic-caching-and-cost-quality-routing)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)](https://redis.io/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)

* **OpenAI-Compatible Proxy**: Drop-in `/v1/chat/completions` gateway supporting official OpenAI SDKs, with streaming (SSE) and non-streaming modes.
* **Multi-Tenancy & Security**: Tenant & Project hierarchy with RBAC (`owner`, `admin`, `viewer`) and constant-time SHA-256 hashed API key validation.
* **Two-Phase Atomic Budgets**: Multi-scope spending limits (daily/monthly per project/tenant) enforced via integer microdollar arithmetic ($1.00 = 1,000,000 microdollars) with pre-request reservation and idempotent settlement.
* **Semantic Vector Caching**: Embedding similarity search powered by Redis & vector indexing, delivering sub-20ms cache responses on recurring prompts.
* **Provider Reliability & Failover**: Automatic failover chains, exponential backoff with bounded jitter, and intelligent cost-quality model routing.
* **Enterprise Observability**: Distributed tracing with Jaeger, Prometheus telemetry metrics, Grafana dashboards, and a dedicated React monitoring interface.
* **Verified Technologies**: `Python 3.11+` · `FastAPI` · `AsyncPG` · `PostgreSQL` · `pgvector` · `Redis` · `Redis Streams` · `Docker Compose` · `Alembic` · `React` · `Prometheus` · `Jaeger`.

---

### 🔬 [SQLForge — Empirical Study: What Fine-Tuning Buys on Text-to-SQL](https://github.com/mayanksingh2745/SQLForge-a-controlled-study-of-what-fine-tuning-buys-on-text-to-SQL)
> **A rigorous, controlled research benchmark investigating whether parameter-efficient fine-tuning (LoRA / QLoRA) on small open-weight language models matches frontier commercial APIs on text-to-SQL execution accuracy.**

[![GitHub Repo](https://img.shields.io/badge/Repository-SQLForge-a78bfa?style=for-the-badge&logo=github&logoColor=0d0e16)](https://github.com/mayanksingh2745/SQLForge-a-controlled-study-of-what-fine-tuning-buys-on-text-to-SQL)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/)
[![LoRA / PEFT](https://img.shields.io/badge/PEFT-LoRA%20%2F%20QLoRA-8B5CF6?style=for-the-badge)](https://github.com/huggingface/peft)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg?style=for-the-badge)](https://opensource.org/licenses/Apache-2.0)

* **Core Scientific Objective**: Measures whether 1.5B–8B parameter open models (e.g., Qwen2.5-Coder-7B) can approach or match commercial frontier reference APIs (GPT-4o mini, Claude 3.5 Sonnet) on SQL execution accuracy (EX) while minimizing latency and VRAM footprint.
* **Controlled Experimental Framework**: Direct empirical comparison between zero-shot base prompting, schema-aware few-shot prompting, dynamic similarity-retrieved few-shot, and LoRA/QLoRA adaptation.
* **Multi-Benchmark Rigor**: Evaluated across Spider, a harder BIRD subset, and a completely held-out custom SaaS schema to quantify out-of-domain transfer and schema nesting retention.
* **Contamination & Leakage Audit**: Strict n-gram and semantic similarity verification to prevent test set data leakage into training splits.
* **Implementation Status**: Completed architecture, packaging, dataset pipelines, prompt templates, contamination detection, and evaluation harness (Steps 0–6); LoRA hyperparameter and rank scaling sweeps ($r \in \{8, 16, 32, 64\}$) actively underway.
* **Verified Technologies**: `Python 3.11+` · `PyTorch` · `Hugging Face Transformers` · `PEFT` · `BitsAndBytes (NF4)` · `vLLM` · `Spider Benchmark` · `Ruff` · `mypy`.

---

## ⚡ Complete Engineering Portfolio

| Project | Architecture &amp; Focus | Core Stack | Status |
|:---|:---|:---|:---:|
| [**Tollgate**](https://github.com/mayanksingh2745/Tollgate-a-multi-tenant-LLM-gateway-with-budgets-semantic-caching-and-cost-quality-routing) | Multi-tenant LLM gateway with strict token budgets, vector semantic caching (14ms hit), and intelligent cost-quality model routing | `Python` `FastAPI` `Redis` `PostgreSQL` `Docker` | 🟢 Active |
| [**SQLForge**](https://github.com/mayanksingh2745/SQLForge-a-controlled-study-of-what-fine-tuning-buys-on-text-to-SQL) | Rigorous empirical benchmark measuring execution accuracy, schema adaptation, and cost trade-offs of parameter-efficient fine-tuning on Text-to-SQL | `PyTorch` `LoRA / QLoRA` `Transformers` `vLLM` | 🔬 Research |
| [**Digital Twin for Predictive Maintenance**](https://github.com/mayanksingh2745/ValueTrack-Customer-Lifetime-Value-Predictor) | Industrial time-series forecasting engine with stacked LSTMs and 3D tensor windowing on 10-year streaming telemetry for predictive anomaly detection | `Python` `Stacked LSTM` `Scikit-learn` `Streamlit` | ⚙️ Research |
| [**TechTutor**](https://github.com/mayanksingh2745/TechTutor-Domain-Specific-LLM-Fine-Tuning-LoRA) | Domain-specific LLM fine-tuning of Mistral-7B leveraging LoRA/QLoRA for high-accuracy technical education and machine learning comprehension | `Mistral-7B` `LoRA` `PEFT` `HuggingFace` | 🚀 Released |
| [**DocuMind**](https://github.com/mayanksingh2745/DocuMind-RAG-Powered-Document-Q-A-System) | End-to-end Retrieval-Augmented Generation (RAG) system with semantic chunking, FAISS vector indexing, and grounded multi-format document Q&amp;A | `LangChain` `FAISS` `FastAPI` `Python` | 🚀 Released |
| [**Project Velocity**](https://github.com/mayanksingh2745/Project-Velocity-Automotive-Sales-Market-Intelligence-Platform) | End-to-end automotive market intelligence platform forecasting performance and demand using ensemble machine learning | `Python` `Ensemble ML` `Pandas` `SQL` | 🚀 Released |

<br/>

<div align="center">

## 🌃 3D Contribution City

*Every commit builds another tower — rebuilt automatically every day.*

<img src="./profile-3d-contrib/profile-night-view.svg" alt="3D contribution city" width="100%"/>

<br/><br/>

<!-- 💌 LET'S CONNECT -->
<img src="./connect.svg?v=2" alt="Let's connect — Mayank Singh" width="100%"/>

<br/>

<a href="https://mayank-portfolio-xi-wheat.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-22d3ee?style=for-the-badge&logo=vercel&logoColor=0d0e16" alt="Portfolio"/></a>
&nbsp;
<a href="https://github.com/mayanksingh2745"><img src="https://img.shields.io/badge/GitHub-a78bfa?style=for-the-badge&logo=github&logoColor=0d0e16" alt="GitHub"/></a>
&nbsp;
<a href="https://www.linkedin.com/in/mayank-singh2745/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
&nbsp;
<a href="mailto:mayanksingh2745@gmail.com"><img src="https://img.shields.io/badge/Email-f472b6?style=for-the-badge&logo=gmail&logoColor=0d0e16" alt="Email"/></a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=mayanksingh2745&color=22d3ee&style=for-the-badge&label=PROFILE+VIEWS" alt="Profile views"/>

<br/>

**Engineering practical intelligence. Always learning, always building.** ⚡

</div>
