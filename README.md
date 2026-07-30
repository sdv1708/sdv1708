<p align="center">
  <img src="./assets/profile-header.svg" alt="Sanjay DV — Software Engineer focused on agentic systems and backend engineering" width="100%">
</p>

<p align="center">
  <a href="https://portfolio-shell.dvsanjay9.workers.dev">Portfolio</a>
  &nbsp;&nbsp;/&nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/sanjay-dv/">LinkedIn</a>
  &nbsp;&nbsp;/&nbsp;&nbsp;
  <a href="mailto:reach.sdv1708@gmail.com">Email</a>
  &nbsp;&nbsp;/&nbsp;&nbsp;
  <a href="https://github.com/sdv1708?tab=repositories">Repositories</a>
</p>

## Somewhere between distributed systems and applied AI.

I am a software engineer working across agentic AI, backend engineering, and
distributed systems. I am deeply interested in system design, the intricacies
behind reliable software, and building backend and AI systems that remain
understandable, scalable, and maintainable as they grow.

My work spans multi-agent workflows, retrieval systems, evaluation pipelines,
concurrency-safe APIs, and the lower-level mechanics behind language models and
distributed storage.

Away from the terminal, I am usually watching MMA, cooking something ambitious,
working out, or riding motorcycles. I am also slowly turning my own bike into a
café racer.

## Featured projects

### [PostMortem AI](https://github.com/sdv1708/postmortem)

An evidence-first incident analysis system that turns logs, traces, and deployment
notes into a reviewable postmortem. Its six-stage pipeline uses specialized
generation, criticism, and verification steps; every claim is cited or marked as
an assumption, and the final root-cause decision remains with a human reviewer.

[Repository](https://github.com/sdv1708/postmortem) /
[Live demo](https://postmortem-frontend-euyq.onrender.com/)

`Python` `FastAPI` `Next.js` `TypeScript` `Pydantic` `SQLAlchemy`

### [Executive Intelligence Copilot](https://github.com/sdv1708/intelligence_copilot)

A supervisor-orchestrated RAG system that converts meeting documents into cited
executive briefs and grounded follow-up answers. Parallel research agents,
evidence-preserving retrieval, cross-meeting memory, and execution traces make
the system's conclusions inspectable.

`FastAPI` `LangGraph` `React` `TypeScript` `FAISS` `SQLite`

### [Concurrent Reservation API](https://github.com/sdv1708/concurrent-reservation)

A hotel reservation backend built around transactional correctness. Row-level
locking prevents double bookings, a strict state machine governs reservation and
payment transitions, and signed Stripe webhooks safely finalize asynchronous
payments.

`Python` `FastAPI` `SQLAlchemy` `PostgreSQL` `Stripe` `pytest`

## Currently developing

### [Distributed Key-Value Store](https://github.com/sdv1708/distributed-kv-store)

Designing a key-value store from first principles, beginning with a crash-safe
LSM-tree storage engine using a write-ahead log, memtable, SSTables, Bloom
filters, compaction, and tombstones. The distributed design explores consistent
hashing, replication, tunable quorums, and vector-clock conflict detection.

`Python` `LSM tree` `WAL` `consistent hashing` `quorum consensus`

### [GPT from Scratch](https://github.com/sdv1708/gpt-scratch)

Building a working GPT one primitive at a time. The completed foundations derive
gradient descent, backpropagation, initialization, and normalization explicitly
in NumPy and PyTorch; attention and transformer blocks are now in progress.

`Python` `NumPy` `PyTorch` `transformers` `first-principles ML`

## Open source

### [EvalTrust](https://github.com/k-dickinson/evaltrust)

EvalTrust audits whether LLM evaluation results provide enough statistical
evidence to support model-selection and release decisions. I contributed two
merged input adapters that let users work directly with native evaluation
exports instead of reshaping them into generic CSV files first.

- [LangSmith run-export adapter](https://github.com/k-dickinson/evaltrust/pull/62) —
  added structural format detection, per-example feedback scoring, skipped-row
  handling, registry integration, documentation, and test coverage.
- [Ragas result-export adapter](https://github.com/k-dickinson/evaltrust/pull/77) —
  added native ingestion for RAG evaluation metrics such as faithfulness, answer
  relevancy, and context precision, including invalid-score handling,
  documentation, and tests.

`Python` `LLM evaluation` `LangSmith` `Ragas` `pytest`

## Experience

**Software Engineer, AI — Virtual Gold**<br>
*June 2026 – Present*

- Deeply involved in learning, implementing, and understanding agentic workflows
  and applications, with an emphasis on turning emerging patterns into reliable,
  production-minded software.
- Exploring how orchestration, tool use, memory, evaluation, and human oversight
  fit together when agentic ideas move from experimentation into real
  applications.

**Software Engineer Intern, AI — Connyct / CampusAI**<br>
*September 2025 – December 2025*

- Developed and deployed a production LLM recommendation service that combined
  retrieval-augmented generation, Elasticsearch vector search, Redis caching,
  Amazon Bedrock, and containerized deployment on AWS ECS.
- Improved recommendation relevance and service responsiveness through
  multi-signal ranking, retrieval tuning, and caching strategies designed for
  repeated production workloads.
- Built an evaluation framework around hallucination, relevance, groundedness,
  and latency, then integrated regression gates into CI/CD so model and prompt
  changes could be assessed before release.

**Software Development Engineer — University of Maryland, Community Preservation Trust**<br>
*February 2025 – December 2025*

- Helped replace fragmented email-based and handwritten rental processes with a
  centralized, multi-tenant platform for applicants and administrators.
- Developed Flask REST APIs and React workflows around application submission,
  review, and administration, giving each user group a clearer and more
  consistent operational path.
- Applied JWT authentication and role-based access control to protect tenant
  boundaries and keep sensitive workflows limited to the appropriate users.

**Software Development Engineer, AI and Backend — IQVIA**<br>
*March 2022 – July 2024*

- Built an Azure-hosted document-intelligence workflow that combined language
  models, serverless functions, and object storage to improve the consistency of
  structured data extracted from regulatory documents.
- Designed an Airflow-orchestrated processing pipeline that used OCR, validation
  rules, and confidence-based routing to avoid unnecessary model inference while
  improving throughput and recovery from document failures.
- Developed event-driven backend services with Azure Service Bus topics, queues,
  retries, and dead-letter handling, creating a more resilient path for
  asynchronous message processing.
- Built FastAPI and SQLAlchemy services over PostgreSQL payment data, giving
  operations teams clearer access to transaction summaries, outstanding
  balances, and revenue indicators.

## Engineering toolkit

| Area | Technologies |
| --- | --- |
| Languages | Python, TypeScript, SQL |
| Applied AI | LLMs, RAG, LangChain, LangGraph, Google ADK, DeepEval, PyTorch, scikit-learn, Hugging Face |
| Backend and data | FastAPI, Flask, React, PostgreSQL, MySQL, Redis, Pinecone, Kafka, Airflow, Elasticsearch |
| Infrastructure | AWS, Azure, Docker, Kubernetes, CI/CD, Linux, Claude Code, Cursor |

## Education

**M.S. in Information Systems** — University of Maryland, Robert H. Smith School
of Business, December 2025

**B.S. in Electronics Engineering** — PES University, May 2022

---

I am open to backend, applied AI, and ML infrastructure opportunities in the
United States. The best way to reach me is through
[LinkedIn](https://www.linkedin.com/in/sanjay-dv/) or
[email](mailto:reach.sdv1708@gmail.com).
