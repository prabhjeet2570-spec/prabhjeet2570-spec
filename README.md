<p align="center">
  <img src="./assets/banner.svg?v=ai-ml-software" alt="Prabhjeet Singh — AI, machine learning, and software engineering. MS CS at NYU; AI/ML Researcher at BAAHL Lab." width="100%">
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/prabhjeetsingh5201/">LinkedIn</a> ·
  <a href="mailto:prabhjeet2570@gmail.com">Personal email</a> ·
  <a href="mailto:ps5390@nyu.edu">NYU email</a> ·
  <a href="https://github.com/prabhjeet2570-spec?tab=repositories">All projects</a>
</p>

## Software engineering, machine learning, and research

I'm Prabhjeet, an **MS Computer Science student at NYU**, **AI/ML Researcher at BAAHL Lab**, and **Deep Learning Teaching Assistant**. My research explores video models for encrypted inference. I work across backend services, data pipelines, application development, and machine learning, including model evaluation, retrieval, and agent workflows.

Before NYU, I spent **three years building backend systems in logistics**. At **DP World**, I worked with external customers and shipping-line partners to understand their APIs and operational workflows, then collaborated with product teams to build workable integrations.

## Research at BAAHL Lab

My research explores **efficient, privacy-preserving video inference**: adapting MoViNet's 3D convolutional architecture for fully homomorphic encryption through Orion.

The work spans the full path from model analysis to encrypted execution:

- **Model evaluation and approximation:** Study activation sensitivity and design site-specific Swish and Sigmoid polynomial approximations, balancing classification accuracy, numerical stability, and encrypted computation cost.
- **Encrypted model execution:** Develop and validate support for 3D convolutions, depthwise operations, pooling, squeeze-and-excitation gating, and residual connections, including encrypted MoViNet bottleneck execution.
- **GPU systems and optimization:** Investigate Cheddar-based execution, ciphertext packing, arithmetic precision, bootstrapping, and memory use, with profiling and comparisons against ResNet.
- **Realistic evaluation:** Connect real-video inputs and calibrated activations with encrypted workloads, separating approximation error from encryption error and measuring forward latency independently of compilation and key generation.
- **Reproducible research:** Build experiment workflows with fixed datasets, tracked configurations, numerical checks, and paired prediction analysis.

## Selected engineering work

| Project | What to explore | Stack |
|---|---|---|
| [FinSight](https://github.com/prabhjeet2570-spec/FinSight) | Financial research with hybrid retrieval, reranking, inspectable sources, and period-aware XBRL calculations. [Evaluation](https://github.com/prabhjeet2570-spec/FinSight/blob/main/docs/evaluation.md) covers 24 curated retrieval questions and 69 financial, abstention, and citation checks. | Python, FastAPI, React, SQLite, ONNX |
| [Huddle](https://github.com/prabhjeet2570-spec/huddle) | A LangGraph booking agent with human approval, persistent checkpoints, database conflict checks, and retryable calendar synchronization. [Validation](https://github.com/prabhjeet2570-spec/huddle/blob/main/docs/validation.md) includes restart and recovery scenarios. | Python, FastAPI, LangGraph, PostgreSQL, Docker |
| [AeroStream Analytics](https://github.com/prabhjeet2570-spec/aerostream-analytics) | Kafka aircraft ingestion, PySpark queries, Parquet storage, and an aviation dashboard. [Recorded benchmarks](https://github.com/prabhjeet2570-spec/aerostream-analytics#measured-results-three-months-957m-records-659-mb-compressed) compare CSV and Parquet aggregation across **9.57 million historical flight records**. | Python, Kafka, PySpark, Flask, Docker |
| [SmolVLM ScienceQA](https://github.com/prabhjeet2570-spec/smolvlm-scienceqa-dora) | Visual question answering experiments with DoRA, augmentation, and checkpoint ensembling. Includes notebooks, adapters, and a reported **0.92555 Kaggle score**. | PyTorch, Transformers, PEFT |
| [Music Language Models](https://github.com/prabhjeet2570-spec/Scaling-Laws-for-Language-Models-on-Symbolic-Music-Data) | Transformer and LSTM experiments on ABC music notation, comparing model size with validation loss under a fixed training budget. Includes configurations, recorded results, and generated samples. | PyTorch, Transformers, LSTMs |

## More work to explore

[Ledger HTR](https://github.com/prabhjeet2570-spec/ledger-htr) — an exploratory historical-ledger handwriting study with TrOCR preprocessing comparisons, Transkribus exports, source provenance, and a transcription-review app. The one-page pilot uses unreviewed draft labels; its results are exploratory.

[ERICA Tutor](https://github.com/prabhjeet2570-spec/erica-tutor-chatbot) — a collaborative course project using GraphRAG and PostgreSQL-backed content ingestion for tutoring. [CareLine](https://github.com/prabhjeet2570-spec/CareLine) and [SafeHarbor](https://github.com/prabhjeet2570-spec/safeharbor) explore healthcare voice-agent and AI-governance workflows as prototypes.

## Tools I work with

**Software:** Python, Java, TypeScript, SQL, FastAPI, Spring Boot, React<br>
**AI / ML:** PyTorch, Hugging Face, PEFT, LangGraph, retrieval and model evaluation<br>
**Data and infrastructure:** PostgreSQL, SQLite, Redis, Kafka, PySpark, Docker, Kubernetes, Azure

I'm interested in **AI engineering, machine learning, and software engineering roles**, working on intelligent applications, model development, and reliable backend and data systems.
