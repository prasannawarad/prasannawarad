<h1 align="center">Prasanna Warad</h1>

<p align="center">
  <strong>Building Data & Agentic AI Systems</strong><br/>
  Data pipelines, RAG systems, and LLM workflows — end to end, deployed, and documented.<br/>
  M.S. in IT &amp; Management @ UT Dallas — Dean's Excellence Scholar · ex-HCLTech · Dallas, TX
</p>

<p align="center">
  <a href="https://prasannawarad.com"><strong>prasannawarad.com</strong></a> ·
  <a href="https://www.linkedin.com/in/prasannawarad">LinkedIn</a> ·
  <a href="mailto:waradprasanna@gmail.com">Email</a>
</p>

> 🤖 **Don't feel like scrolling?** Ask [**Prasanna AI**](https://prasannawarad.com) — the chat widget on my portfolio answers questions about my work, my projects, and even my anime backlog. I built it myself: Cloudflare Worker + Groq, grounded in a structured knowledge base.

---

### 🔭 Featured: AI & LLM Systems

| Project | What it does | Stack |
|---------|--------------|-------|
| **[sec-rag-intel](https://github.com/prasannawarad/sec-rag-intel)** | Production-grade RAG over SEC 10-K/10-Q filings — grounded, **cited** answers with MMR retrieval, local BGE embeddings, and hallucinations caught quantitatively via RAGAS faithfulness scores | Python · LangChain LCEL · ChromaDB / Pinecone · Groq Llama 3.3 70B · FastAPI · Streamlit |
| **[codelens-ai](https://github.com/prasannawarad/codelens-ai)** — [live demo](https://codelens-ai-olive.vercel.app) | AI code-audit & technical-debt tracker: deterministic static metrics × LLM analysis, async BullMQ job queue, **incremental re-audits** via content-hash diffing, weighted 0–100 debt score over time | Node/Express · React · BullMQ + Redis · Prisma + Postgres · Gemini |
| **[RAGbase](https://github.com/prasannawarad/RAGbase)** — [live](https://ragbase.prasannawarad.com) | Document-intelligence RAG platform: **hybrid retrieval (BM25 + vector + RRF)**, streaming answers with clickable chunk-level citations, chunk inspector, analytics dashboard | Next.js · Supabase pgvector · Gemini embeddings · Groq (SSE) |
| **[InvestIQ](https://github.com/prasannawarad/InvestIQ)** — *Top 5, Goldman Sachs × UTD JSOM Hackathon* — [live](https://invest-iq-kuber.netlify.app) | AI portfolio guide for beginner investors: deterministic portfolio engine, streaming AI copilot with real-time voice briefings, and a Chrome extension that answers "what does this news mean for *my* portfolio?" | Next.js monorepo · Supabase · Groq · ElevenLabs · Plasmo MV3 |
| **[DataDoc_AI](https://github.com/prasannawarad/DataDoc_AI)** — [live](https://datadocai.netlify.app) | Data-quality debugger: profile a CSV entirely in-browser, get AI-explained issues with suggested fix SQL, and query it with natural language → SQL | React · in-browser SQL engine · Express proxy · Gemini |
| **[prepai-pro](https://github.com/prasannawarad/prepai-pro)** | Interview intelligence: generates a company research dossier + STAR stories from your resume, then runs a scored multi-turn mock interview with adaptive difficulty | React · Vite · Gemini 2.5 Flash |

### 📊 Data Engineering & ML

| Project | What it does | Stack |
|---------|--------------|-------|
| **[credit-risk-default-prediction](https://github.com/prasannawarad/credit-risk-default-prediction)** | Default prediction on **255K+ loan records** with ~12% positives: SMOTE inside stratified 5-fold CV, RandomizedSearchCV model comparison, RF threshold calibration, partial-dependence interpretation | Python · scikit-learn · XGBoost · imbalanced-learn |
| **[CardioRisk](https://github.com/prasannawarad/CardioRisk)** | Config-driven, fully deterministic ETL + ML pipeline over **~300K healthcare records** — modular stages, reproducible seeds, headless CLI execution; champion model at ~91% accuracy / 0.81 AUC | R · tidyverse · caret · randomForest |
| **[ETL Pipeline with Airflow + Astro](https://github.com/prasannawarad/End-To-End-ETL-Pipeline-Using-AirFlow-And-Astro)** | End-to-end ETL with scheduling, monitoring, and containerized deployment | Apache Airflow · Astro · Python |
| **Scalable Fleet Risk Analytics** | Hadoop-based ingestion and transformation for multi-state fleet operations with risk and compliance monitoring | Hadoop · HDFS · MapReduce · Power BI |
| **Instacart Customer Behavior** | Processed 3M+ grocery transactions into analytics-ready datasets with KPI dashboards for demand and ROI tracking | SQL · Python · Tableau |
| **[My_Portfolio](https://github.com/prasannawarad/My_Portfolio)** — [live](https://prasannawarad.com) | This portfolio site — with **Prasanna AI**, a chat widget that answers questions about my work, served by a Cloudflare Worker + Groq | React · Vite · Tailwind · Cloudflare Workers |

---

### 🛠 Tech I work with

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,r,nodejs,react,nextjs,fastapi,postgres,mysql,mongodb,supabase,aws,docker,pytorch,git,figma&perline=15&theme=dark" alt="tech stack" />
</p>

<p align="center">
  <code>Spark</code> · <code>Airflow</code> · <code>Kafka</code> · <code>Hadoop</code> · <code>dbt</code> · <code>Snowflake</code> · <code>Redshift</code> · <code>Azure Synapse</code> · <code>Oracle</code><br/>
  <code>scikit-learn</code> · <code>MLflow</code> · <code>LangChain</code> · <code>LangGraph</code> · <code>RAG / pgvector / ChromaDB / Pinecone</code> · <code>RAGAS</code> · <code>LLM Fine-tuning</code> · <code>Multi-Agent Systems</code> · <code>MCP</code><br/>
  <code>Groq</code> · <code>Gemini</code> · <code>Tableau</code> · <code>Power BI</code> · <code>REST APIs</code> · <code>Cloudflare Workers</code> · <code>n8n</code> · <code>BullMQ</code> · <code>Prisma</code>
</p>

---

### ⚙️ How I build

```
simple > clever ──── every architecture decision should survive an interview whiteboard
free tier, prod patterns ── quotas are real constraints → every LLM call has a fallback chain
grounded or it didn't happen ── RAG answers ship with citations + RAGAS faithfulness scores
deployed > demo ──── live URL, seeded demo account, screenshots — or it's not done
deterministic core ── LLMs decorate the edges; the engine underneath is reproducible math
```

---

### 💼 Experience

| Role | Focus | Time |
|------|-------|------|
| **Software Engineer Intern, Cloud BC Labs** | Building agentic AI hiring automation — REST APIs with Node.js and Python, ETL optimization, behavioral trend analysis | Oct 2025 – May 2026 |
| **Data Engineer, HCLTech (Client: Dollar General)** | Spark + Airflow reporting pipelines serving a 19,000+ store retail network, large-scale transaction analysis, anomaly forecasting on AWS logs | Feb 2023 – Jul 2024 |

```text
19,000+  retail stores served by production Spark ETL & reporting pipelines
5-stage  hiring process automated end-to-end with LLM agents
Top 5    Goldman Sachs × UTD JSOM Hackathon — InvestIQ
2M+      retail transaction records analyzed to improve reporting data quality
28%      query latency reduction in real-time reporting pipelines
300+     fleet assets monitored across 14 states in risk analytics workflows
3M+      grocery transactions processed for segmentation and demand insights
```

---

### 🎓 Education

- **The University of Texas at Dallas** — M.S. in Information Technology & Management (May 2026)
  Dean's Excellence Scholar · GPA 3.88 · Graduate Certificate in Business Analytics & Data Mining
- **Savitribai Phule Pune University** — B.E. in Electrical Engineering

---

### ⏰ Off the clock — `crontab -l`

```
┌─ weekends ────── cricket · pickleball · table tennis · soccer
├─ weekly ──────── soccer matches (haven't missed a week yet)
├─ nightly ─────── anime · Marvel · Suits · Billions · Modern Family reruns
├─ ongoing ─────── fiction & philosophy reading
└─ on trigger ──── random idea → side project → somehow becomes a real tool
```

---

### 🚀 Right now

- Building production RAG and LLM-evaluation systems — grounded answers, cited sources, measured faithfulness
- Open to full-time **Data Engineer / AI-ML Engineer / Data Platform** roles → [waradprasanna@gmail.com](mailto:waradprasanna@gmail.com)
