<div align="center">

# Shubham Penkar

**ML Engineer · Agentic AI · Full-Stack Builder**

*Building systems that reason, explain, and act — not just predict.*

[![Email](https://img.shields.io/badge/shubhamworks1718@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:shubhamworks1718@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/shubhampenkar)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/ShubhamPenkar)

</div>

---

## About

I'm a final-year CS undergrad obsessed with the gap between ML models that *predict* and systems that *explain and prescribe*. My work spans agentic AI architectures, audio deep learning, distributed systems, and network security — with a consistent focus on making complex ML legible and actionable.

Currently working on **Knowa** — an ML platform for non-technical users that auto-detects problem types, trains models, and generates grounded prescriptive strategies using a 5-agent agentic architecture. The core research contribution (87% full grounding rate across 5 business domains) addresses a formally identified open problem in agentic AI: *how do you ensure LLM-generated recommendations are causally grounded in model evidence, not hallucinated?*

---

## Featured Projects

### 🧠 [Knowa](https://github.com/ShubhamPenkar/knowa) — Agentic ML Platform for Non-Technical Users
> `Python` `FastAPI` `React` `SHAP` `DiCE` `LLMs` `Multi-Agent`

An end-to-end ML platform that removes the need for data science expertise. Users upload data, describe their business problem, and Knowa handles everything — from problem type detection to model training to actionable strategy generation.

**Architecture:** 5-agent pipeline (Profiler → Trainer → Explainer → Prescriptor → Narrator) with a conversational interface and what-if sandbox.

**Research contribution:** Grounded prescriptive strategy generation achieving **87% full grounding rate** across 5 business domains — addressing a formally identified open problem in agentic AI (hallucination of prescriptions not supported by model evidence).

**Stack:** Python, FastAPI, React, SHAP (feature attribution), DiCE (counterfactual explanations), LLM orchestration.

---

### 🎙️ [Sentinel](https://github.com/ShubhamPenkar/Sentinel-Violence-Detector) — Real-Time Audio Violence Detection
> `Python` `PyTorch` `wav2vec2` `Streamlit` `Audio DSP`

Production-grade audio monitoring system that detects violence and aggression in real-time audio streams. Evolved from logistic regression → SVM → fine-tuned wav2vec2 transformer.

**Results:** 88.1% accuracy, AUC 0.950 on actor-disjoint train/test splits (RAVDESS + CREMA-D).

**Engineering highlights:**
- Multi-gate pipeline: music gate → wav2vec2 → threshold + energy gate
- Temporal smoothing to reduce false positives in live streams
- Time-of-day adaptive thresholds
- Headless monitor with sliding windows + live Streamlit dashboard

---

### 🌐 [Distributed Chat System](https://github.com/ShubhamPenkar/Distributed-Chat-System) — Distributed DB Concepts in Production
> `React` `FastAPI` `PostgreSQL` `WebSockets` `MongoDB`

A real-time chat system built to demonstrate distributed database concepts — not a toy. Implements message sharding across two DB nodes, location transparency via views, stored procedure routing, RBAC with three roles, and Row-Level Security.

**Technical depth:**
- Message sharding across PostgreSQL nodes with location-transparent view
- Real-time WebSocket messaging (RFC 6455 compliant)
- RBAC: Admin / Moderator / User with RLS enforcement
- MongoDB polyglot persistence + XML/XPath/XQuery integration
- Glassmorphism dark UI

---

### 🧬 [Auto-NAS](https://github.com/ShubhamPenkar/Auto-NAS) — Neural Architecture Search via Genetic Algorithms
> `Python` `Streamlit` `Genetic Algorithms` `PyTorch` `AutoML`

A mini-AutoML system that evolves neural network architectures for tabular classification datasets using genetic algorithms — no manual architecture design required.

**How it works:** Population of candidate architectures → fitness-based selection → crossover + mutation → repeat until convergence. Users upload a CSV, Auto-NAS handles the rest.

---

### 🔒 [DNS Spoofing Detector](https://github.com/ShubhamPenkar/dns-spoofing-detector) — Real-Time Network Security
> `Python` `Flask` `Scapy` `Network Security`

Real-time DNS spoofing detection system with packet-level analysis using Scapy and a live dark-themed dashboard. Detects anomalous DNS responses indicative of cache poisoning or MITM attacks.

---

## Tech Stack

**ML / AI**
`PyTorch` `scikit-learn` `SHAP` `DiCE` `wav2vec2` `Transformers` `LLM Orchestration` `Genetic Algorithms`

**Backend**
`Python` `FastAPI` `Flask` `PostgreSQL` `MongoDB` `WebSockets`

**Frontend**
`React` `TypeScript` `Streamlit`

**Security / Systems**
`Scapy` `Network Packet Analysis` `Distributed DB Design` `RBAC / RLS`

---

## Research Interests

- **Grounded prescription in agentic AI** — ensuring LLM-generated recommendations are causally anchored in model evidence
- **Explainable ML** — SHAP-based feature attribution + DiCE counterfactual explanations for non-technical users
- **Audio deep learning** — transformer-based audio classification, domain adaptation, actor-disjoint evaluation
- **Distributed systems** — sharding strategies, consistency models, location transparency

---

## GitHub Stats

<div align="center">

![Shubham's GitHub Stats](https://github-readme-stats.vercel.app/api?username=ShubhamPenkar&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ShubhamPenkar&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

![GitHub Streak](https://streak-stats.demolab.com?user=ShubhamPenkar&theme=tokyonight&hide_border=true)

</div>

---

<div align="center">

*Open to ML Engineering, AI/LLM Engineering, and Research Engineering roles.*
*Also open to collaboration on agentic AI and explainability research.*

</div>
