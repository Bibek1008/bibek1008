# 👋 Hi, I'm Bibek Bhandari

### Computer Science Graduate | LLM & Agentic AI Engineering | Applied AI Research

I am a Computer Science graduate interested in **Large Language Models, Generative AI, Agentic AI, Trustworthy AI, and Deep Learning**.

My work spans two areas: researching modern LLM systems through controlled experiments, fine-tuning, reinforcement learning, hallucination detection, and inference optimization; and building practical AI applications involving RAG pipelines, autonomous agents, LLM evaluation, and full-stack engineering.

I enjoy connecting research ideas with practical implementations and building reliable, evaluation-driven AI systems.

---

## 🚀 Selected Industry Projects

### 1. AI-Powered Pull Request Reviewer

**Tech Stack:** Next.js, TypeScript, PostgreSQL, Prisma, Pinecone, Inngest, OpenRouter, GitHub API, Razorpay

[Live Demo](https://my-pull-request-reviewer.vercel.app/) | [GitHub Repository](https://github.com/Bibek1008/My_pull-_request-reviewer)

- Built an AI-powered code review platform that integrates with GitHub to analyze pull requests and post contextual review comments.
- Implemented a repository-aware RAG pipeline using repository file chunking, embeddings, and Pinecone vector search to retrieve codebase context beyond pull-request diffs.
- Developed asynchronous review and repository synchronization workflows using Inngest, with PostgreSQL and Prisma for application data and synchronization tracking.
- Integrated GitHub OAuth, GitHub App webhooks, and Razorpay subscription checkout and billing webhooks.

### 2. AI-Powered Customer Support Agent

**Tech Stack:** Python, FastAPI, PostgreSQL, pgvector, LangChain, Groq, Presidio, FastEmbed, Langfuse

[Live Demo](https://customer-support-agent-k21j.onrender.com/) | [GitHub Repository](https://github.com/Bibek1008/Customer-Support-Agent)

- Developed a RAG-based customer support agent that answers customer queries using an approved knowledge base and PostgreSQL/pgvector retrieval.
- Implemented a tool-calling workflow with intent classification, knowledge retrieval, confidence-based answer validation, extractive fallback, and human escalation.
- Integrated safety guardrails for prompt injection detection, PII redaction, input/output safety classification, and policy consistency.
- Built persistent ticket and conversation workflows with ticket recovery, ownership validation, and idempotent request handling.
- Integrated Langfuse for tracing model calls, retrieval results, guardrail decisions, and token usage.

### 3. Enterprise Agentic RAG — Evaluation Dashboard

**Tech Stack:** Python, Streamlit, RAGAS, FastAPI, LangGraph

[Live Demo](https://production-grade-scalable-advance-r.vercel.app/) | [GitHub Repository](https://github.com/Bibek1008/Production-Grade-Scalable-Advance-RAG)

- Built a Streamlit dashboard to inspect ground-truth question-answering datasets, execute live RAG pipeline evaluations, and analyze results.
- Integrated RAGAS metrics and guardrail evaluations to assess answer quality, faithfulness, relevance, and safety behavior.
- Developed a three-stage evaluation workflow covering ground-truth review, live pipeline execution, and metric analysis.

### 4. Transformer From Scratch

**Tech Stack:** Python, PyTorch

[GitHub Repository](https://github.com/Bibek1008/Transformer-implementation-from-scratch-in-PyTorch)

Implemented core Transformer components from first principles, including token embeddings, positional encoding, Query-Key-Value representations, scaled dot-product self-attention, and multi-head attention.

---

## 🧪 Research

### Hallucination Detection and Intervention in LLM Agents

**Independent Research | September 2026 – Present**

Investigating the robustness of hallucination detection signals in multi-step LLM agents under adversarial distribution shifts.

Current research focuses on:

- Understanding how hallucination detection reliability changes as errors propagate across reasoning steps.
- Developing detection-guided intervention mechanisms to identify and mitigate hallucinations before propagation.
- Evaluating detection and intervention approaches across multiple models, tasks, and distribution shifts.

### Recursive Fine-Tuning and Model Degradation in Biomedical QA Systems

**Research Preprint | 2026**

Investigated the effects of recursive fine-tuning on synthetic biomedical question-answering data using LLMs, QLoRA, and Hugging Face Transformers.

Research included:

- Multi-generation recursive fine-tuning experiments.
- Multi-seed evaluation.
- Lexical and semantic analysis.
- Biomedical entity-level analysis using NER.
- Evaluation on PubMedQA.
- Analysis of model diversity and domain knowledge retention.
- Investigation of answer quality degradation caused by synthetic data accumulation.

📄 **Preprint:** [arXiv:2609.34257](https://arxiv.org/abs/2609.34257)

---

## 🔬 Research Projects

### 🧠 Compute-Efficient LoRA Objective Selection

**Qwen3-0.6B | LoRA | MLX**

- Developed a shared-prefix LoRA training strategy for comparing token-mean and example-mean objectives.
- Achieved **25% fewer training updates** compared with independent full training.
- Verified deterministic checkpoint/resume continuation across model, optimizer, and RNG states.
- Evaluated the approach across **3 prospective random seeds**.

### ⚡ LLM Inference Optimization Lab

**Python | LLM Systems | KV Cache | Scheduling**

- Built deterministic simulators for LLM serving mechanisms.
- Implemented request scheduling, KV-cache allocation, and prefill/decode batching.
- Evaluated baseline and candidate policies using held-out workloads.
- Studied latency, throughput, cache growth, and batching trade-offs.

### 🎯 Validation-Guided LoRA Loss Selection

**Qwen3-0.6B | PyTorch | LoRA**

- Investigated token-mean versus example-mean training objectives for parameter-efficient fine-tuning.
- Implemented validation-guided objective selection with held-out test evaluation.
- Conducted paired multi-seed experiments.
- Compared NLL and exact-answer accuracy and analyzed cases where validation selection failed to transfer to the test set.

---

## 💻 Technical Skills

### 🧠 AI / Machine Learning

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![Transformers](https://img.shields.io/badge/Transformers-FF6F00?style=for-the-badge)
![Reinforcement Learning](https://img.shields.io/badge/Reinforcement_Learning-8A2BE2?style=for-the-badge)

### 🔬 LLM Research and Fine-Tuning

![LoRA](https://img.shields.io/badge/LoRA-4B0082?style=for-the-badge)
![QLoRA](https://img.shields.io/badge/QLoRA-5B21B6?style=for-the-badge)
![PEFT](https://img.shields.io/badge/PEFT-7C3AED?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-00897B?style=for-the-badge)
![KV Cache](https://img.shields.io/badge/KV_Cache-1565C0?style=for-the-badge)
![NLP](https://img.shields.io/badge/NLP-2E7D32?style=for-the-badge)
![Hallucination Detection](https://img.shields.io/badge/Hallucination_Detection-B71C1C?style=for-the-badge)

### 🤖 Agentic AI Engineering

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge)
![Google ADK](https://img.shields.io/badge/Google_ADK-4285F4?style=for-the-badge)
![MCP](https://img.shields.io/badge/MCP-5B5BD6?style=for-the-badge)
![Agent Memory](https://img.shields.io/badge/Agent_Memory-6A5ACD?style=for-the-badge)
![Context Engineering](https://img.shields.io/badge/Context_Engineering-00897B?style=for-the-badge)
![Harness Engineering](https://img.shields.io/badge/Harness_Engineering-795548?style=for-the-badge)

### 💻 Programming and Web Development

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### 🗄️ Data, Infrastructure and Tools

![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-5A67D8?style=for-the-badge)
![Pinecone](https://img.shields.io/badge/Pinecone-00A98F?style=for-the-badge)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)

---

## 🏆 Achievements

- **Top 6 Finalist — CTRL+MOVE 24-Hour Hackathon (2025)**, selected among 105 participating teams.
- Participated in Code Carnage 24-Hour Hackathon (2025).
- Participated in AI Hiring Show: Vibe Coding, Power Hiring (2025).

---

## ✍️ Technical Writing

I write technical articles covering computer science and software engineering topics, including:

- DNS Resolution
- Git Internals
- TCP Handshake
- Browser Internals
- Software Engineering Concepts

📝 **Hashnode:** [hashnode.com/@bibekbhandari1](https://hashnode.com/@bibekbhandari1)

---

## 🔗 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bibek-bhandari-053283226/)

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Bibek1008)

[![Hashnode](https://img.shields.io/badge/Hashnode-2962FF?style=for-the-badge&logo=hashnode&logoColor=white)](https://hashnode.com/@bibekbhandari1)

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://bibekbhandari11.com.np)

