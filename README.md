# Hi, I'm Yosra Megbli

**AI & Backend Engineer** | LLM Systems & Pipelines | Document Intelligence | Multi-Agent Systems

📍 Tataouine, Tunisia · 🌍 Remote-first (UTC+1, overlap with European and Gulf hours), open to relocation
✉️ [yosra.meguebli@yahoo.fr](mailto:yosra.meguebli@yahoo.fr) · [LinkedIn](https://linkedin.com/in/meguebli-yosra) · [Megbli Labs Portfolio](https://yosra-megbli.github.io/megbli-labs/)

## About Me

AI & Backend Engineer specializing in document intelligence, LLM pipelines, multi-agent systems and workflow automation. Experienced in designing AI architectures, developing backend services, integrating AI components and building automated tests, with hands-on experience deploying projects as live demos.

At Arkeyez, I designed a four-module document-processing pipeline covering OCR, classification, compliance validation and ERP integration. The classification component achieved **99.7% accuracy on a 313-document test set**.

The projects featured below are independent R&D projects with public GitHub repositories and selected live demos; they are not presented as commercial production deployments.

**Available immediately for remote, full-time opportunities. Open to relocation.**

## Professional Experience

- **AI Engineer & Tech Lead, Arkeyez** (Jan 2026 – Apr 2026): led technical direction for a 2-person team; designed a 4-module document pipeline built on Django REST, Celery and Redis.
- **Freelance AI/NLP Developer, Collaborative Project** (Oct 2024 – Dec 2025): contributed, as part of a small team, to a freelance project for a French company: medical document extraction (LayoutLMv3, PaddleOCR) and CNN-based classification with FastAPI backend components.
- **University Lecturer & Technical Supervisor, ESPRIT** (Jan 2020 – Sep 2024): taught C programming; supervised 100+ students building 2D games in C.

## Independent Projects (Apr 2026 – Present)

Self-directed R&D on agentic systems. The projects below are personal work, not client deliverables.

### 💬 Sophie: AI Sales Agent (solo personal project)
Conversational agent qualifying energy-sector leads. Telegram, web widget and SMS are operational; WhatsApp and outbound voice (Twilio) are wired, pending account activation.

| | |
|---|---|
| **Core** | FastAPI, deterministic state machine and YAML rules engine. The LLM only phrases replies and never decides a state transition |
| **Features** | PDF contract generation, Yousign e-signature (sandbox only), GDPR opt-out and data purge, RAG with citation validation |
| **Stack** | PostgreSQL (pgvector), React ops dashboard with live SSE supervision |
| **Quality** | 898 automated tests, including end-to-end golden-conversation scenarios |
| **Links** | [Live demo](https://intelligent-sales-agent.onrender.com/dashboard) (access key on request, first load may take ~60s) · [Source](https://github.com/Yosra-Megbli/Intelligent-Sales-Agent) |

### 🔐 Secure Multi-Tenant RAG Platform
Internal document Q&A with strict cross-company isolation.

| | |
|---|---|
| **Isolation** | PostgreSQL Row-Level Security (RLS), applied before vector search rather than as a post-filter |
| **Answers** | Verifiable citations and automatic no-source refusal before any LLM call |
| **Pipeline** | Extraction, chunking, local embeddings, explicit publish step; lifecycle automation with n8n |
| **Stack** | Next.js, TypeScript, PostgreSQL/pgvector, Auth.js, Groq; Vercel and Supabase |
| **Quality** | 140+ automated tests verifying isolation by execution, GitHub Actions CI |
| **Links** | [Live demo](https://zen-knowledge.vercel.app) · [Source](https://github.com/Yosra-Megbli/zen-knowledge) |

### 🧠 Multi-Agent Platform v6
| | |
|---|---|
| **Orchestration** | LangGraph: parallel agents, aggregator, confidence-based decisions |
| **Retrieval** | RAG via pgvector |
| **Reliability** | RBAC, Dead Letter Queue (DLQ), Human-in-the-Loop (HITL) |
| **Stack** | FastAPI, PostgreSQL, Celery, Redis, Docker Compose, Groq (Llama 3.3 70B) |
| **Source** | [multiagent-platform-v6](https://github.com/Yosra-Megbli/multiagent-platform-v6) |

### 🧾 AI Invoice Processing (n8n)
| | |
|---|---|
| **Extraction** | Groq (Llama 3.3 70B) with Gemini fallback |
| **Validation** | Business-rule engine |
| **Storage & reporting** | PostgreSQL, Metabase dashboard, SMTP alerts |
| **Source** | [n8n-invoice-ai-agent](https://github.com/Yosra-Megbli/n8n-invoice-ai-agent) |

### 🔍 DocClassify AI: CNN + OCR + ERPNext
| | |
|---|---|
| **Models** | ResNet50 CNN + EasyOCR + TF-IDF fusion |
| **Accuracy** | 85–92% on real-world document sets (separate system from the Arkeyez pipeline) |
| **Backend** | FastAPI with JWT authentication, integrated with self-hosted Frappe/ERPNext v15 |
| **Source** | [CNN-Fastapi-ERPnext](https://github.com/Yosra-Megbli/CNN-Fastapi-ERPnext) |

### ☀️ PV Power Forecasting
24-hour multi-site photovoltaic forecasting with LightGBM: RMSE 2,241 W, skill score 0.46 vs. persistence baseline, with ablation studies. [Source](https://github.com/Yosra-Megbli/piex-pv-forecasting)

## Technical Skills

- **AI / ML:** LangGraph, RAG, pgvector, sentence-transformers, HuggingFace, LayoutLMv3, PaddleOCR, EasyOCR, TensorFlow, ResNet50, LightGBM
- **LLM APIs:** Groq, Google Gemini, OpenAI-compatible endpoints, HuggingFace Inference API
- **Backend:** Python, FastAPI, Django REST Framework, SQLAlchemy, TypeScript, Next.js, JWT, REST APIs, SSE, pytest
- **Infrastructure:** Celery, Redis, Docker, Docker Compose, GitHub Actions (CI/CD), Render, Vercel, Frappe/ERPNext v15
- **Databases:** PostgreSQL, pgvector, Supabase, Neon, Upstash Redis, MariaDB
- **Security:** Multi-tenancy, RBAC, PostgreSQL RLS, JWT, webhook signature verification, GDPR
- **Integrations:** n8n, Telegram Bot API, Twilio, Yousign, Metabase, SMTP
- **Systems:** C, memory management, data structures, performance optimization

## Education & Publication

- PhD Candidate, Deep Learning & Accident Detection (on hold), ENET'COM Sfax (2021–2024)
- Master's in Computer Science, ENSIT Tunis (2020) · Bachelor's in Computer Science, ESSTT Tunis (2010)
- 📄 [Deep Learning Architecture for Offline Recognition of Handwritten Math Symbols](https://doi.org/10.1007/978-3-030-71804-6_15), MedPRAI 2020, Springer

## Languages

Arabic (Native) · French (good reading and writing, intermediate spoken) · English (good reading and writing, limited spoken)

📫 Open to remote, full-time opportunities: [yosra.meguebli@yahoo.fr](mailto:yosra.meguebli@yahoo.fr)
