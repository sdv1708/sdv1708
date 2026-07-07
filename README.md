<h1 align="center">Hi, I'm Sanjay Dari Veerabasappa 👋</h1>

<p align="center">
  <b>Backend & AI/ML Engineer · UMD MS Information Systems '25</b><br/>
  Building distributed systems, RAG pipelines, and multi-agent LLM infrastructure.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sanjaydv/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:sanjaydv@umd.edu"><img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/sdv1708"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white"/></a>
</p>

---

## About Me

- 🎓 **M.S. Information Systems** — University of Maryland, R.H. Smith School of Business (Dec 2025). Coursework spanning distributed systems, ML, and applied AI. Previously **B.S. Electronics Engineering** from PES University (2022).

- 🤖 **Software Engineer Intern, AI @ Connyct (CampusAI)** *(Sep 2025 – Dec 2025)*
  - Engineered the production RAG pipeline (ElasticSearch · Sentence Transformers · Redis) with optimized retrieval and prompt templating, hitting **95% event discovery accuracy** at **≤2s inference latency**.
  - Wired up evaluation pipelines (DeepEval, LLM-as-Judge, AgentOps) as **release gates in GitHub Actions** to catch low-quality models before they ship.

- 🏛️ **Software Development Engineer @ UMD — Community Preservation Trust** *(Feb 2025 – Dec 2025)*
  - End-to-end ownership of a full-stack platform (React · Flask · MySQL · REST) for **15K+ users**, including JWT auth and RBAC.
  - Ran on agile delivery cycles translating stakeholder requirements into production code.

- 🏢 **Software Development Engineer @ IQVIA (Bangalore)** *(Jul 2022 – Jul 2024)* — Two years building backend systems in regulated fintech / life-sciences production:
  - REST APIs (FastAPI · PostgreSQL) supporting **1.2M+ annual transactions** at sub-second latency
  - Distributed event-driven microservices (Docker · Kubernetes · Azure Service Bus) processing **3K+ msgs/sec** with audit-ready fault tolerance
  - Airflow-orchestrated OCR pipeline (Tesseract · OpenCV · Donut) for Mandarin financial document extraction — **+70% throughput** improvement
  - GPT-3.5 document workflows on Azure Functions hitting **95% extraction accuracy**, replacing manual regulatory review

- 🛠️ **Currently building** — A 3-agent **clinical decision support system** using Google ADK + Gemini + MCP with RAI guardrails and eval-gated CI/CD on Cloud Run and a **GPT** clone to deep-dive into LLM architecture.  

- 🎯 **Focus areas** — Distributed systems · LLM evaluation (DeepEval, LLM-as-Judge, AgentOps) · RAG pipelines · multi-agent orchestration (LangChain, Google ADK, MCP) · production ML infrastructure · backend APIs at scale

- 🌎 **Open to** — Backend SWE · AI/ML Engineering · ML Infra roles · United States
---

## Tech Stack

**AI & GenAI**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Google ADK](https://img.shields.io/badge/Google_ADK-4285F4?style=flat&logo=google&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat&logo=huggingface&logoColor=black)
![DeepEval](https://img.shields.io/badge/DeepEval-7C3AED?style=flat)

**Backend & Distributed Systems**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-FF6C37?style=flat&logo=postman&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat)

**Cloud & MLOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/CI/CD-2088FF?style=flat&logo=githubactions&logoColor=white)

---

## Featured Projects

| Project | What it does | Stack |
|---------|-------------|-------|
| [**Clinical Decision Support System**](https://github.com/sdv1708/Diagnostic-Stack) | 3-agent system using a Coordinator pattern with MCP tool handlers, RAI guardrails, and eval-gated CI/CD — production-grade observability and responsible AI controls. | Google ADK · Gemini · MCP · RAG · Cloud Run |
| [**Executive Intelligence Copilot**](https://github.com/sdv1708/intelligence_copilot) | Multi-agent LLM system with tool-calling workflows, function-level routing, and structured decision support over unstructured data. | LangChain · FAISS · SQLite |
| [**Distributed Reservation & Payment Engine**](https://github.com/sdv1708/concurrent-reservation) | Concurrency-safe APIs using row-level locking — eliminates race conditions and guarantees consistency in high-concurrency booking workflows. | FastAPI · PostgreSQL · Supabase |
| [**GPT Clone**](https://github.com/sdv1708/gpt-scratch) | GPT from Scratch. Built from primitives. | Python · PyTorch · Numpy · First Principles |

---

## Experience Highlights

```
Connyct — CampusAI (SDE Intern, AI)     → Multi-agent GenAI platform · 31 enterprise sources
                                           Production RAG · 95% accuracy · ≤2s latency
                                           Eval gates in CI: DeepEval · LLM-as-Judge · AgentOps

UMD — Community Preservation Trust       → Full-stack AI-ready platform · 15K+ users
(SDE)                                      React · Flask · MySQL · JWT/RBAC
                                           Schema + query refactors → cost & reliability wins

IQVIA (SDE — Backend)                    → REST APIs · 1.2M+ annual transactions
                                           Event-driven microservices · 3K+ msgs/sec
                                           Airflow OCR pipeline · +70% throughput
                                           GPT-3.5 doc workflows · 95% extraction accuracy
```

---
