# Hi, I'm Aldiyar Bakhtayev 👋
### AI Automation Engineer · Agentic Workflows · Browser & CRM Automation

I build AI systems that connect models to real business infrastructure: CRMs, APIs, databases, and headless browser automation. My core engineering focus is eliminating hallucinations through deterministic safety layers, structured Pydantic schemas, and resilient state machines.

---

### 🚀 Flagship Engineering Projects

#### 1. [Keenfort AI Sales Agent](https://github.com/Aldid/keenfort-sales-agent)
**Autonomous CRM Sales Agent, Intent Extraction & Booking Scheduler**  
*Python · Pydantic · amoCRM REST API · pytest · JSON Schema · Prompt Injection Guard*
- Autonomous conversation agent evaluating live CRM customer chats and qualifying leads for trial lessons.
- Multi-tier **Safety Layer** enforcing pricing/discount limits, message tone, and pre-write state drift detection.
- **97.6% fact extraction precision** across 210 candidate parameters (205/210 verified extractions across 18 real AmoCRM conversations; 5 false confirmations intercepted by deterministic validator).
- **18/18 agreement (100%)** on booking readiness and next-question routing against expert human baselines.
- Comprehensive test suite of **511 automated pytest unit & integration tests** ensuring 100% regression stability.

#### 2. [Production RAG & Evaluation System](https://github.com/Aldid/production-rag-system)
**Enterprise Hybrid Retrieval Service, pgvector Adapter & 100-Case Evaluation Harness**  
*Python 3.11 · FastAPI · PostgreSQL (pgvector) · Docker · GitHub Actions · Pydantic*
- Enterprise semantic retrieval service with hybrid search (dense embeddings + BM25) and Reciprocal Rank Fusion (RRF k=60).
- Exposes structured REST endpoints (`/api/v1/query`, `/api/v1/ingest`, `/api/v1/evaluate`) with 3-layer security defense (prompt injection detection, PII redactor, strict citation enforcement).
- Automated 100-case evaluation harness achieving **96% Hit-Rate@1** and **97.3% Context Faithfulness** across 5 business domains, backed by 25 unit tests.
- Packaged with multi-stage `Dockerfile` and `docker-compose.yml` with automated GitHub Actions CI.

#### 3. [Auto Supply Chain Simulator](https://github.com/Aldid/zara-supply-chain-sim)
**Interactive Supply Chain Digital Twin & Agile Replenishment Simulator**  
*React 19 · TypeScript · Vite · Tailwind CSS · Recharts · Vercel · Docker*
- Interactive web model demonstrating agile fashion supply chains and base-stock replenishment policies across international air and truck routes (Milan, Istanbul, New York).
- 6-week dynamic scenario engine modeling demand fluctuations, stockouts, freight trade-offs, and financial P&L.
- Responsive data visualization dashboard deployed to Vercel with multi-stage Docker and automated CI.

#### 4. [LeadFlow Engine](https://github.com/Aldid/leadflow-engine)
**AI-Powered Lead Intelligence & Verification Pipeline**  
*TypeScript · Node.js · Playwright · JSON Schema · AJV · REST APIs*
- Multi-agent web research pipeline extracting and validating commercial entity data across multiple sources.
- Strict schema enforcement with JSON Schema/AJV ensuring zero malformed payloads enter CRM ingestion.
- Resilient Playwright crawling algorithms with adaptive rate limiting and session persistence.

#### 5. [Browser Automation & Workflow Engine](https://github.com/Aldid/browser-automation-engine)
**Headless Browser Automation & Deterministic Form Interaction Engine**  
*TypeScript · Node.js · Playwright · CDP · JSON State Engine*
- Automated opportunity discovery, multi-factor fit scoring, and resilient browser form interaction workflows.
- Safety gate detecting Cloudflare Turnstiles, reCAPTCHAs, and 2FA challenges, safely pausing for human-in-the-loop review.
- Validated with **104 automated tests across 11 test suites** (100% pass rate).

#### 6. [Sarqyt Mobile App](https://github.com/Aldid/sarqyt)
**Food Discovery & Surplus Deals Platform (Ongoing Prototype)**  
*Flutter 3 · Dart · Clean Architecture · Riverpod · GoRouter · Supabase*
- Cross-platform mobile marketplace prototype connecting food businesses with customers to reduce food waste in Kazakhstan.
- Feature-driven Clean Architecture with Riverpod state management, GoRouter navigation, local-first MVP boundary contracts, location filtering, and Supabase PostgreSQL schema with RLS.

---

### 🛠️ Technical Stack & Tools

- **Core Specialization:** AI Automation, Agentic Workflows, Retrieval-Augmented Generation (RAG), Hybrid Search (pgvector + BM25), Structured Outputs (Pydantic, JSON Schema), Browser Automation, CRM Automation.
- **Languages:** Python (3.11/3.13), TypeScript, JavaScript (ESNext), Node.js, SQL.
- **Frameworks & UI:** FastAPI, React 19, Vite, Tailwind CSS, Recharts.
- **DevOps & Containers:** Docker, Docker Compose, GitHub Actions CI/CD, Git.
- **Automation & Testing:** Playwright, Chrome DevTools Protocol (CDP), pytest (640+ tests across repos), Jest/Node test runner, JSON Schema / AJV.
- **Backend & Cloud:** PostgreSQL (pgvector, Row Level Security), Supabase, SQLite, REST APIs, Vercel.

---

### 🎓 Education & Background
- **BSc in Business Administration and Economics** — International Business School (IBS), Budapest (2024 – Present).
- Combining quantitative business analysis with modern software engineering to build high-impact workflow automations.

📫 **Get in Touch:**
- **Email:** [bakhtaevaldiyar@gmail.com](mailto:bakhtaevaldiyar@gmail.com)
- **LinkedIn:** [linkedin.com/in/aldiyar-bakhtayev](https://www.linkedin.com/in/aldiyar-bakhtayev-254666350/)
