# Edam Hamza

**GenAI Engineer at [Converty](https://converty.shop) | ICT Engineer, SUP'COM (High Honors)**

I build systems end-to-end, from the model layer to the infrastructure it runs on. My work spans generative AI, full-stack development, data engineering, DevOps, and embedded systems. Not because I hop between fields, but because the best solutions don't respect domain boundaries.

Based in Tunisia. TOEIC 990/990.

[![Portfolio](https://img.shields.io/badge/Portfolio-edamhamza.dev-c8a86e?style=flat)](edamhamza.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/edam-hamza-a2567a273/)

---

### Currently at Converty

Full architectural ownership as a GenAI Engineer. Everything described below is production infrastructure, battle-tested with real stores and real merchants.

**URANUS** — Converty's AI infrastructure layer. 12 agents across 4 families, orchestrated through a unified runner/hook pipeline. nanoUSD billing engine (integer arithmetic at 10^9 scale, 145+ unit tests), 3-layer rate limiting, prompt injection defenses, multi-tier caching, and provider-agnostic design. Deployed on Kubernetes (k3s) with security hardening.

**Storefront AI Salesman** — Production shopping assistant powering every Converty store. 8 tools (Qdrant vector search, FAQ retrieval, cart management, checkout), 13 languages including 10 Arabic dialects, streaming SSE responses. Seller-managed FAQ knowledge base and full visual widget customization.

**[Excalidraw Atelier](https://github.com/EdamH/excalidraw-atelier)** — 78,415 lines of TypeScript. Started as "save my drawings" and grew into a full collaborative workspace with 3 content types (drawings, documents, kanban), realtime collaboration, ClickUp sync, an MCP server, and a tamagotchi pet. Used daily by ~30 people.

**Landing Page Generator** — 7-agent multimodal AI pipeline. Sellers upload product photos and get a complete landing page. Evolved through 4 versions. $1.00/generation ceiling.

**Store Traffic Analytics** — Real-time analytics dashboard built on ClickHouse with RabbitMQ ingestion, 7 materialized views, and a multi-stage aggregation pipeline (event → session → daily → per-metric tables).

---

### What I bring to the table

**Generative AI & NLP** — LLMs, RAG pipelines, embeddings, semantic matching, LangChain, prompt engineering, Vertex AI, Qdrant. Built production AI systems processing real traffic at Converty and an AI recruitment platform with explainable scoring at Amaris Consulting.

**Full-Stack Engineering** — TypeScript, React, Node.js, Express, MongoDB, Socket.IO. Built [Excalidraw Atelier](https://github.com/EdamH/excalidraw-atelier) (78,415 LOC) with realtime collaboration, TipTap document editing, kanban boards, and a custom Editorial Atelier design system.

**Data Engineering** — Kafka, Spark, Elasticsearch, ClickHouse, AWS (Kinesis, Glue, S3, SageMaker). Built [real-time trading pipelines](https://github.com/EdamH/REAL-TIME-TRADING-DATA-FORECAST-LLM-GRAFANA) with Prophet forecasting and live Grafana dashboards. Also built an [end-to-end AWS MLOps pipeline](https://github.com/EdamH/AWS-MLOPS-WATER-QUALITY-INDEX-FORECAST-VISUALIZE-GRAFANA-GENAI-GPT2) from Kinesis to SageMaker to FastAPI.

**DevOps & Cloud** — Docker, Kubernetes, Jenkins CI/CD, Prometheus, Grafana, GitHub Actions, Azure. Built a full AI recruitment platform at Amaris with microservices architecture, Docker Swarm orchestration, CI/CD across 3 environments, and monitoring.

**Embedded Systems & Computer Vision** — OpenCV, Raspberry Pi, ESP32, Flutter/BLE. At HTWK Leipzig, developed a [marker detection system](https://github.com/EdamH/Auto-Centering-Camera-Marker-Detection) for power line drone inspections with a 3D-printed gimbal and real-time servo correction.

---

### Experience

| When | Where | What |
|------|-------|------|
| 2025 — now | **Converty** | GenAI Engineer — URANUS (12 AI agents), Excalidraw Atelier (78K LOC), platform infrastructure |
| 2025 | **Amaris Consulting** | AI Intern — AI recruitment platform with LLM-based semantic matching, Docker Swarm |
| 2024 — 2025 | **EY Tunisia** | GenAI Project — DB schema optimization with LLaMA/StarCoder2 and LangChain |
| 2024 | **HTWK Leipzig** | Summer Intern — computer vision & embedded systems for drone inspection |
| 2023 | **Acteol** | Full-Stack & GenAI Intern — CRM with OpenAI/LangChain |

### Education

**SUP'COM** — ICT Engineering Degree, High Honors (2022–2025)
**IPEIS Sfax** — Engineering Preparatory, entrance exam rank 89/1,831 (2020–2022)

### Certifications

NVIDIA Building RAG Agents with LLMs · AWS Data Engineering · AWS ML Foundations · AWS Cloud Foundations · freeCodeCamp: Machine Learning with Python, Data Analysis with Python, Scientific Computing with Python, Data Visualization, JavaScript Algorithms & Data Structures, Responsive Web Design

---

### Community

Supervisor, **IndabaX Tunisia 2024** — organized Tunisia's chapter of the Deep Learning Indaba AI conference at SUP'COM.
Chair of Membership, **IEEE SupCom Student Branch** — grew and led the membership committee (2023–2024).
Team Leader of Project Department, **Sup'Com Junior Entreprise** (2022–2023).
