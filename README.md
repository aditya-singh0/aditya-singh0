% =====================  ADITYA  SINGH  –  ONE-PAGE  RÉSUMÉ  =====================
\documentclass[10pt]{article}
\usepackage[margin=0.55in]{geometry}
\usepackage{fontawesome5}
\usepackage{hyperref}
\usepackage{titlesec}
\usepackage{tabularx}
\usepackage{xcolor}
\definecolor{darkblue}{HTML}{0A1F44}
\hypersetup{colorlinks=true,urlcolor=darkblue}
\titleformat{\section}{\large\bfseries\color{darkblue}}{}{0em}{}[\titlerule]
\setlength{\parindent}{0pt}\setlength{\tabcolsep}{0pt}

\begin{document}
{\LARGE \textbf{Aditya Singh}} \hfill \faIcon{map-marker} San Francisco (open to relocate)\\[2pt]
\faIcon{envelope} \href{mailto:adityasinghw84it@gmail.com}{adityasinghw84it@gmail.com}
\quad \faIcon{phone} +91-9711762763
\quad \faIcon{github} \href{https://github.com/aditya84it}{aditya84it}
\quad \faIcon{linkedin} \href{https://linkedin.com/in/aditya84it}{aditya84it}

\section*{Machine-Learning Engineer | Large-Scale Search \& Retrieval}
1+ yr shipping billion-token ranking systems (8 TB/mo, 100 QPS). Built GPU pipelines, K8s micro-services, real-time vector stores. Comfortable full-stack (React, Node, FastAPI) and writing Rust for high-performance crawlers.

\section*{Core Toolkit}
\begin{tabularx}{\linewidth}{@{}lX}
\textbf{LLM / Prompting} & GPT-4, Claude, RAG, ReAct, few-shot eval harnesses\\
\textbf{Vector Retrieval} & FAISS, ScaNN, BigQuery ANN, Elasticsearch, Rust indices (WIP)\\
\textbf{ML Frameworks} & PyTorch, TensorFlow, Spark-MLlib, Vertex AI, GCP H100/A100\\
\textbf{Back-end} & FastAPI, Go (basic), Rust (learning), Docker, Kubernetes, Airflow\\
\textbf{Front-end} & React, Next.js, Tailwind (ship UI in hours)\\
\textbf{Data @ Scale} & 8 TB/mo, Delta Live Tables, DVC, Grafana, MLflow\\
\end{tabularx}

\section*{Experience}
\textbf{Samsung R\&D} — \textit{ML Engineer} \hfill Aug 2023 – Nov 2024\\
$\bullet$ End-to-end ranking pipeline for ADAS depth-estimation; cut training 30 \% on 8 TB/mo.\\
$\bullet$ 12 GPU micro-services (CV + LLM) on K8s; autoscale 0→200 pods, p99 80 ms.\\
$\bullet$ A/B features → NDCG +12 \%, CTR +8 \%; exec pitch → two-quarter roadmap.

\textbf{QLink (Remote)} — \textit{MLOps Engineer} \hfill Jul 2022 – Aug 2023\\
$\bullet$ FastAPI backend 10 k+ daily queries p95 < 40 ms on Azure Container Apps.\\
$\bullet$ Airflow DAGs (DVC + Grafana) caught embedding drift 36 h pre-impact.

\textbf{Turbostart} — \textit{Software Engineer} \hfill Apr 2025 – Jul 2025\\
$\bullet$ Real-estate search (Transformer-OCR + LLM); blue-green K8s, 0-downtime.

\section*{Projects (Hack-Days → Production)}

\textbf{1. Chat-with-Search UI} \textit{Next.js, Tailwind, Qdrant, ReAct prompts}\\
$\bullet$ 48 h build; streams 200-word summaries from自建vector DB.\\
$\bullet$ 150 concurrent users, p95 650 ms, 99 % uptime on Vercel.
\vspace{1.25em}

\textbf{2. Day-Long Agentic Orchestrator} \textit{Python asyncio, Celery, K8s CronWorkflow}\\
$\bullet$ Multi-step research (query → crawl → embed → rank → synthesize).\\
$\bullet$ Checkpoints every 5 min; longest job 27 h, 1 400 CPU-days; 38 % GPU idle saved.
\vspace{1.25em}

\textbf{3. Rust Crawler Boost} \textit{Rust async, HTTP/2, bloom-filter, SIMD}\\
$\bullet$ 58 k pages/sec, 3.2× vs. Python scrapy on 64 vCPU.\\
$\bullet$ Politeness p95 < 50 ms via adaptive concurrency + memory-mapped robots.txt cache.
\vspace{1.25em}

\textbf{4. Zero-Query Homepage Recs} \textit{TensorFlow, BigQuery, FAISS, AKS-KEDA}\\
$\bullet$ Transformer seq-model for cold-start users; add-to-cart +5.4 % (2 M user A/B).\\
$\bullet$ 100 QPS, KEDA 5→120 pods, p99 120 ms, 99.9 % availability.
\vspace{1.25em}

\textbf{5. Governed Feature Store} \textit{Databricks, Unity Catalog, MLflow}\\
$\bullet$ 600+ features with lineage and drift alerts; 25 \% compute cut, \$4 k/mo saved.

\section*{Education}
\textbf{B.E. Mathematics \& Computing}, Delhi Technological University \hfill 2019 – 2023\\
Publication: “Graph-Augmented Neural Ranking for E-commerce Search” CIKM 2023.

\section*{Misc}
4× Coursera DL specializations $\cdot$ Top 2 \% Samsung Pro Test (3 500+) $\cdot$ Visa sponsorship OK.
\end{document}
