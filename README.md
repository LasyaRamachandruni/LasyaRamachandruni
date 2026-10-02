# Lasya Ramachandruni

**ML Systems • Inference Optimization • LLM Applications**
M.S. Data Science @ SJSU (GPA 3.90/4.00) · San Jose, CA
[📧 Email](mailto:swathisrilasyamayukha.ramachandruni@sjsu.edu)

---

I build systems at the boundary between model experimentation and production reliability — inference pipelines, RAG systems, and multi-agent frameworks with a focus on latency, efficiency, and measurable outcomes.

---

## Featured Projects

**[Agent Eval Harness](https://github.com/LasyaRamachandruni/Agent-Eval-Harness)** — Reliability & Safety Testing for LLM Agents *(in progress)*
Evaluation harness that runs tool-using agents through a suite of tasks with automatic checks, recording full step-by-step traces. Model-agnostic across Anthropic, OpenAI and local Ollama models; measuring success rate, consistency, cost and prompt-injection resistance.
`Python` `LLM Agents` `Evaluation` `Prompt Injection` `pytest`

**[LLM Inference from Scratch](https://github.com/LasyaRamachandruni/llm-inference-from-scratch)** — KV Cache, Batching & Speculative Decoding
GPT-2 inference written from the ground up in PyTorch, with the core serving techniques implemented by hand and verified against the baseline. KV cache keeps per-token latency flat (**47×** faster at 1,000 tokens of context); batched decoding with padding masks gives **8.2×** throughput; speculative decoding with cache rollback produces output identical to the target model, with a statistical test proving the sampling distribution is exact.
`Python` `PyTorch` `Transformers` `LLM Inference` `Speculative Decoding`

**[MiniVLA Benchmark](https://github.com/LasyaRamachandruni/minivla-benchmark)** — Vision-Language-Action Inference Benchmarking
CLI toolkit that measures p50/p95/p99 latency, throughput and memory for VLA models, then applies INT8 quantization and structured pruning. Cut SmolVLM-256M model size by **77%** (489 → 114 MB) and latency by **12%** with pruning. Scales inference with Ray actors, pipeline-parallel stages, Ray Serve endpoints and Ray Data batch jobs.
`Python` `PyTorch` `Hugging Face` `Ray` `Ray Serve` `ONNX Runtime`

**[EdgeOpt](https://github.com/LasyaRamachandruni/edgeopt)** — Edge-Optimized Inference Pipeline
Unified CLI for pruning, quantization, and ONNX-based benchmarking. Deployed and tested on Raspberry Pi and Jetson Nano. Achieved **73% model size reduction** and **7× inference speedup** while maintaining >90% accuracy on CIFAR-10.
`Python` `ONNX` `PyTorch` `TensorFlow` `Raspberry Pi` `Jetson Nano`

**[NeuralEdge](https://github.com/LasyaRamachandruni/NeuralEdge)** — Edge AI for Sleep & Wearable Biosignals
Pipeline for compact 1D-CNN sleep-staging (Sleep-EDF) and stress-detection (WESAD) models, deployed with TensorRT FP16/INT8 on Jetson Nano and Raspberry Pi 4. Includes quantization-aware training, pruning, power measurement and Docker images per device; real dataset loading is in progress.
`Python` `PyTorch` `TensorRT` `ONNX` `Jetson Nano` `Docker`

**[Weather-Induced Infrastructure Failure Prediction](https://github.com/LasyaRamachandruni/CS156Proj)**
Two-stage hurdle model (Random Forest + XGBoost ensemble, with a TCN option) predicting whether weather will cause infrastructure damage and how much, across all 50 US states. Built on NOAA, Census, BEA and FRED data with 500+ engineered features; interactive dashboard with live data.
`Python` `XGBoost` `PyTorch` `Scikit-learn` `Streamlit`

**[Opti Research Buddy](https://github.com/LasyaRamachandruni/OptiResearch-Buddy)** — AI Literature Synthesis System
RAG pipeline using LangChain, FAISS, and Google Gemini to synthesize insights across 100+ academic papers. Reduced manual research time by 60%. Streamlit UI for interactive querying.
`Python` `LangChain` `FAISS` `Gemini` `Streamlit` `RAG`

**[AI Twitter Assistant](https://github.com/LasyaRamachandruni/Langgraph_Reflection_Agent)** — Multi-Agent Reflection System
Dual-agent system with LangGraph + Gemini running 3 iterative critique-and-refine cycles. Boosted content engagement potential by >30% at ~4,400 tokens/run with capped iteration budget.
`Python` `LangGraph` `LangChain` `Gemini`

**[Neural Reflexion Agent](https://github.com/LasyaRamachandruni/Neural-Reflexion-Agent)** — Self-Improving Research Agent
LangGraph loop where Gemini drafts an answer, searches the web with Tavily, and revises with citations until a heuristic reward score stops improving. Streamlit UI to inspect each iteration, compare runs and export traces.
`Python` `LangGraph` `Gemini` `Tavily` `Streamlit`

**[Conversational AI Platform](https://github.com/SaipranavSripathi/AITalks)** — Voice-Enabled Interview Trainer
Real-time voice interview and training system using Deepgram (STT), Groq LLM, and Cartesia (TTS). End-to-end latency-optimized pipeline for conversational AI use cases.
`Python` `Deepgram` `Groq` `Cartesia`

**Customer Segmentation & Revenue Forecasting**
K-Means clustering + linear regression on retail datasets. Improved budget prediction accuracy by 28% and enabled targeted strategic planning.
`Python` `Scikit-learn` `SQL` `Pandas`

---

## Experience

**Student Assistant — Library Innovation Projects** · San José State University *(Mar 2025 – Present)*
Built Python/SQL data extraction pipelines, automated library workflows (25% efficiency gain), and deployed interactive dashboards for leadership decision-making.

**Instructional Student Assistant** · San José State University *(Jun 2025 – Aug 2025)*
Taught UNIX/Linux scripting, Bash, and cloud tools (AWS, GCP, Docker) to 50+ students. Developed automated assessment and progress-tracking workflows.

**Software Developer** · Leo MarCom Private Ltd. *(Apr 2023 – Jul 2024)*
Built and optimized Python/JavaScript/SQL modules; reduced production bugs by 15%. Led agile cross-functional delivery cycles.

**Business Analyst / Scrum Master** · Incedo Inc. *(Mar 2022 – Mar 2023)*
Managed 10–15 concurrent analytics workstreams, improved on-time delivery by 30%, and built executive KPI dashboards.

**Undergraduate Research Assistant** · JNTU(H) *(Apr 2019 – Mar 2020)*
Built GAN-based image enhancement tools; optimized data pipelines for downstream model accuracy.

---

## Skills

**Languages:** Python · SQL · JavaScript · Java · C++ · Bash
**ML / DL:** PyTorch · TensorFlow · Keras · Scikit-learn · ONNX · Deep Learning · NLP
**LLM / Agents:** LangChain · LangGraph · LangSmith · FAISS · RAG · Transformers
**Cloud:** AWS (Lambda · S3 · DynamoDB) · GCP · IBM Cloud · Docker
**Data:** Pandas · NumPy · Spark · Hadoop · Airflow · Tableau · Streamlit
**Databases:** PostgreSQL · Firebase · DynamoDB

---

## Education

**M.S. Data Science** · San Jose State University · 2024–2026 · GPA 3.90/4.00
Coursework: Machine Learning, Hypothesis Testing, Databases, Dimensionality Reduction

**B.Tech Computer Science** · GRIET, Hyderabad · 2017–2021
Thesis: RFM-based customer segmentation and predictive modeling

---

## Certificates

AWS Solutions Architect – Associate · AWS Cloud Practitioner · SAFe Scrum Master · Oracle Database Certified · Microsoft Technology Associate

