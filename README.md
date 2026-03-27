<div align="center">

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│   ███████╗██╗███╗   ███╗ ██████╗ ███╗   ██╗                    │
│   ██╔════╝██║████╗ ████║██╔═══██╗████╗  ██║                    │
│   ███████╗██║██╔████╔██║██║   ██║██╔██╗ ██║                    │
│   ╚════██║██║██║╚██╔╝██║██║   ██║██║╚██╗██║                    │
│   ███████║██║██║ ╚═╝ ██║╚██████╔╝██║ ╚████║                    │
│   ╚══════╝╚═╝╚═╝     ╚═╝ ╚═════╝ ╚═╝  ╚═══╝  MWENDWA          │
│                                                                 │
│         AI PLATFORM ENGINEER  ·  DISTRIBUTED SYSTEMS           │
│              FOUNDER @ SITECHX  ·  NAIROBI, KE                 │
└─────────────────────────────────────────────────────────────────┘
```

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/simon-mwendwa-82b479373)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:simonhackc57@gmail.com)
![Nairobi, Kenya](https://img.shields.io/badge/Nairobi,_Kenya-00A86B?style=for-the-badge&logo=google-maps&logoColor=white)
![Open to Work](https://img.shields.io/badge/Open_to_Work-AI_%2F_ML_%2F_Platform_Roles-FF6B35?style=for-the-badge)

</div>

---

## Who I Am

I'm a **Software Engineer** who builds production-grade AI platforms and distributed financial infrastructure. I don't just integrate AI — I architect the systems that make AI reliable, observable, and useful at scale.

I'm the **Founder and Lead Engineer of [Sitechx](https://github.com/simonmwendwa317-ui)**, a B2B digital commerce platform serving informal and growing businesses in Kenya — currently in controlled piloting with ~1,000 onboarded users. Beyond Sitechx, I've built a full AI SaaS platform with RAG pipelines, vector search, and streaming LLM responses from the ground up, and contributed to a live AI assistant deployed on [kewasnet.co.ke](https://kewasnet.co.ke).

My work sits at the intersection of **AI systems engineering**, **distributed backends**, and **financial infrastructure** — building things that actually run in production, not just notebooks.

---

## What I Build

```
┌────────────────────────────────────────────────────────────────────────────┐
│                                                                            │
│   AI SYSTEMS          DISTRIBUTED SYSTEMS         FINANCIAL INFRA          │
│   ───────────         ──────────────────         ──────────────           │
│   RAG Pipelines       Event-Driven Arch.          Escrow Engines           │
│   Vector Search       Transactional Outbox        Hash-Chained Ledgers     │
│   LLM Integration     Message Queues              M-Pesa Integration       │
│   Streaming APIs      Background Workers          Multi-Party Settlement   │
│   Embedding Models    Geospatial Indexing         Idempotent Payments      │
│                                                                            │
└────────────────────────────────────────────────────────────────────────────┘
```

---

## Flagship Projects

### 🏗 Sitechx — Escrow Commerce & Financial Infrastructure
> *Production · ~1,000 Pilot Users · Dec 2024 – Present*

A B2B digital commerce operating system for informal and growing businesses in Kenya. Connects wholesalers, retailers, and delivery partners through escrow-protected payments, inventory management, and AI-powered market intelligence.

**What makes it real:**
- `49,000+` lines of application logic across `60+` relational domain tables
- `180–220` REST API endpoints supporting multi-role workflows
- State-machine-driven escrow lifecycle with optimistic locking and timeout recovery
- SHA-256 hash-chained immutable ledger with Merkle-root verification
- Hybrid ML credibility scoring (rule-based + scikit-learn classification)
- Event-driven pipelines using Celery, RabbitMQ, and Kafka
- PostGIS geospatial discovery with H3 hexagonal indexing
- Full observability: Prometheus · Grafana · Sentry · Flower

```python
# Escrow state machine — simplified
ESCROW_STATES = [
    "CREATED" → "PAYMENT_PENDING" → "HELD" → "RELEASED"
                                            → "DISPUTED"
                                            → "REFUNDED"
]
```

**Stack:** Django · PostgreSQL · PostGIS · Redis · Celery · RabbitMQ · Kafka · scikit-learn · Docker · Prometheus · Grafana

---

###  Full-Stack AI SaaS Platform — Document-Aware Conversational System
> *RAG · Vector Search · Streaming LLM · 2024–2025*

An end-to-end AI SaaS platform where users can upload documents and have contextual conversations with an AI that retrieves and reasons over their own content.

**Architecture overview:**
```
User Upload (PDF/DOCX/TXT)
        │
        ▼
Document Ingestion Pipeline
        │
        ▼
Sentence Transformer Embeddings
        │
        ▼
FAISS Vector Index (per-user isolation)
        │
   Query time:
        │
        ▼
Similarity Search → Top-K Chunks → Context Injection
        │
        ▼
Anthropic Claude API → Streaming SSE Response → React UI
```

**What's under the hood:**
- Async FastAPI backend with JWT auth and RBAC
- FAISS vector search with sentence-transformer embeddings
- Retrieval-Augmented Generation (RAG) with context-aware prompt design
- Server-Sent Events (SSE) for real-time streaming responses
- Celery background indexing with Redis coordination
- Admin analytics: query trends, language breakdowns, AI-generated reports
- Dockerized deployment with Nginx reverse proxy

**Stack:** FastAPI · React · Vite · PostgreSQL · Redis · FAISS · Sentence Transformers · Anthropic Claude · Celery · Docker · Nginx

---

###  Kewasnet AI Assistant — Live Virtual Assistant
> *Contributor · Production Deployment · 2025*

Part of a 3-person team that built and deployed an AI assistant live on [kewasnet.co.ke](https://kewasnet.co.ke), providing real-time guidance on water, sanitation, and climate resilience topics in Kenya.

- Designed conversational AI workflows for structured user queries
- Built backend prompt pipelines and request handling
- Contributed to production deployment and platform integration

---

## Technical Stack

### AI & Machine Learning
![RAG](https://img.shields.io/badge/RAG-Retrieval--Augmented_Generation-8B5CF6?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-Vector_Search-FF6B6B?style=flat-square)
![Sentence Transformers](https://img.shields.io/badge/Sentence_Transformers-Embeddings-06B6D4?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic_Claude-LLM_Integration-CC785C?style=flat-square)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)

### Backend Engineering
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![DRF](https://img.shields.io/badge/Django_REST_Framework-A30000?style=flat-square)

### Distributed Systems & Messaging
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Redux](https://img.shields.io/badge/Redux_Toolkit-593D88?style=flat-square&logo=redux&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

### Data & Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![PostGIS](https://img.shields.io/badge/PostGIS-Geospatial-336791?style=flat-square)
![SQL](https://img.shields.io/badge/SQL-Advanced-4479A1?style=flat-square)

### Infrastructure & Observability
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)

### Payments
![M-Pesa](https://img.shields.io/badge/M--Pesa_API-00A86B?style=flat-square)

---

## Core Engineering Principles

```
Reliability over features      ─  Systems that fail gracefully are worth more than
                                  systems that do more things poorly.

Observability from day one     ─  If you can't measure it, you can't trust it
                                  in production.

Data integrity above all       ─  Especially in financial systems — optimistic
                                  locking, idempotency, and immutability are
                                  non-negotiable.

AI as infrastructure           ─  LLMs are components, not magic. RAG, retrieval
                                  quality, and evaluation pipelines matter more
                                  than the model itself.
```

---

## Currently

-  Scaling Sitechx through controlled piloting toward full market launch
-  Deepening expertise in RAG evaluation, retrieval optimization, and AI observability
-  Open to AI Platform Engineer, ML Engineer, and Backend AI roles

---

## Let's Talk

If you're building AI systems, financial infrastructure, or distributed platforms — especially for emerging markets — I'd like to connect.

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/simon-mwendwa-82b479373)
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:simonhackc57@gmail.com)

---

<div align="center">

*Building systems that work in the real world — not just in demos.*

</div>
