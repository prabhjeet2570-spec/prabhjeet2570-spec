<p align="center">
  <img src="./assets/banner.svg?v=ai-ml-software" alt="Prabhjeet Singh — AI, machine learning, and software engineering. MS CS at NYU; AI/ML Researcher at BAAHL Lab." width="100%">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/prabhjeetsingh5201/">LinkedIn</a> ·
  <a href="mailto:ps5390@nyu.edu">Email</a> ·
  <a href="https://github.com/prabhjeet2570-spec?tab=repositories">All projects</a>
</p>

## Building AI systems and useful software

I'm Prabhjeet, an **MS Computer Science student at NYU**, **AI/ML Researcher at BAAHL Lab**, and **Deep Learning Teaching Assistant**. My research explores video models for encrypted inference.

Before NYU, I spent **three years building backend systems in logistics**. At **DP World**, I worked directly with external customers and shipping-line partners to understand their APIs and operational workflows, then collaborated with product teams to turn those requirements into workable integrations.

I work across **AI, machine learning, and software engineering**: training and evaluating models, building retrieval and agent systems, and engineering the APIs, data pipelines, and interfaces around them. I enjoy connecting research ideas to useful applications and understanding how systems behave under real constraints.

## Selected engineering work

### [FinSight — financial research with inspectable evidence](https://github.com/prabhjeet2570-spec/FinSight)

An analyst workbench that connects disclosure questions to source passages and financial calculations. Combines **BM25 + dense retrieval, rank fusion, and cross-encoder reranking** with period-aware XBRL facts and `Decimal` arithmetic. Includes durable imports, saved research, and a light evidence inspector.

**Evidence:** four retrieval baselines over 24 curated questions; 45 financial, 14 abstention, and 10 citation checks. The default workflow uses local models and source extracts; optional Ollama synthesis is documented separately.

**Python · FastAPI · React · TypeScript · SQLite · ONNX**<br>
[Architecture](https://github.com/prabhjeet2570-spec/FinSight/blob/main/docs/architecture.md) · [Evaluation](https://github.com/prabhjeet2570-spec/FinSight/blob/main/docs/evaluation.md) · [Screenshots](https://github.com/prabhjeet2570-spec/FinSight/blob/main/docs/screenshots/README.md)

<a href="https://github.com/prabhjeet2570-spec/FinSight"><img src="https://raw.githubusercontent.com/prabhjeet2570-spec/FinSight/main/docs/screenshots/financial-comparison.png" alt="FinSight light UI comparing financial metrics with citations and calculation evidence" width="100%"></a>

### [Huddle — an agent that completes a booking workflow](https://github.com/prabhjeet2570-spec/huddle)

A **LangGraph** agent prepares a room reservation, pauses for human approval, and resumes from PostgreSQL checkpoints. Database constraints prevent conflicting bookings; a separate worker retries calendar synchronization and exposes unresolved work. Scripted scenarios make approval, conflicts, and restart recovery easy to inspect locally.

**Python · FastAPI · LangGraph · PostgreSQL · Docker**<br>
[Workflow design](https://github.com/prabhjeet2570-spec/huddle#engineering-decisions) · [Validation](https://github.com/prabhjeet2570-spec/huddle/blob/main/docs/validation.md) · [Run locally](https://github.com/prabhjeet2570-spec/huddle#run-it)

<a href="https://github.com/prabhjeet2570-spec/huddle"><img src="https://raw.githubusercontent.com/prabhjeet2570-spec/huddle/main/docs/screenshots/chat-proposal.jpg" alt="Huddle booking assistant showing a proposal for the user to review and approve" width="100%"></a>

### More systems and experiments

| Project | Problem and engineering approach | Stack |
|---|---|---|
| [SEC Filing Atlas](https://github.com/prabhjeet2570-spec/secfilingatlas) | Research changing disclosures: durable ingestion, source hashes, full-text search, paragraph comparisons, and optional explanations linked to selected evidence. | React, TypeScript, FastAPI, SQLite FTS5 |
| [SmolVLM ScienceQA](https://github.com/prabhjeet2570-spec/smolvlm-scienceqa-dora) | Improve visual question answering with DoRA, controlled experiment variants, augmentation, and checkpoint ensembling. The repository reports a **0.92555 Kaggle score**, with notebooks and adapters. | PyTorch, Transformers, PEFT |
| [AeroStream Analytics](https://github.com/prabhjeet2570-spec/aerostream-analytics) | Connect aircraft observations and historical flight data to a dashboard through Kafka ingestion, PySpark queries, and Parquet storage. Includes benchmark reports and modeled emissions. | Python, Kafka, PySpark, Flask, Docker |
| [Music Language Models](https://github.com/prabhjeet2570-spec/Scaling-Laws-for-Language-Models-on-Symbolic-Music-Data) | Study model size and validation loss by training transformers and LSTMs on symbolic music, with experiment results and generated samples. | PyTorch, Transformers, LSTMs |

## Tools I work with

**Software:** Python, Java, TypeScript, SQL, FastAPI, Spring Boot, React<br>
**Applied AI:** PyTorch, Hugging Face, PEFT, LangGraph, retrieval and model evaluation<br>
**Data and infrastructure:** PostgreSQL, SQLite, Redis, Kafka, PySpark, Docker, Kubernetes, Azure

I'm interested in **AI engineering, machine learning, and software engineering roles**, working on intelligent applications, model development, and reliable backend and data systems.
