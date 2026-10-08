# Harshvardhan Galande

**AI/ML Engineer — Generative AI, Retrieval-Augmented Generation, LLM Applications**
Pune, India &nbsp;|&nbsp; [LinkedIn](https://www.linkedin.com/in/harshvardhan-galande-01554a323/) &nbsp;|&nbsp; [GitHub](https://github.com/hrshvrdhn26)

---

## About

I build retrieval-augmented and agentic LLM applications in Python. My work centres on three things: retrieval quality, stateful agent workflows, and serving models through clean, well-structured API backends.

I hold a Computer Engineering degree (Class of 2026) with coursework in machine learning, deep learning and high-performance computing, and I am looking for an engineering role where I can ship AI features to production.

## Technical Focus

| Area | Tools and Concepts |
|---|---|
| Languages | Python, SQL |
| Generative AI | LLM APIs (Groq), prompt engineering, RAG, tool-using agents, LangGraph |
| Retrieval | Qdrant, Sentence-Transformers, embeddings, semantic search, chunking strategies |
| Backend | FastAPI, REST API design |
| Machine Learning | scikit-learn, pandas, NumPy, model evaluation |
| Engineering | Git, Docker, Jupyter, environment-based configuration |

## Selected Projects

### DSA Video Retrieval System
[Repository](https://github.com/hrshvrdhn26/DSA-RAG-System)

A retrieval-augmented question-answering system over data structures and algorithms lectures. It finds the most relevant explanation in a set of YouTube transcripts and returns a grounded answer with the matching video and timestamp.

- Transcript ingestion, cleaning and semantic chunking
- Dense retrieval with Sentence-Transformers embeddings stored in Qdrant
- LLM-generated answers conditioned on retrieved passages (Groq)
- Source attribution to video and timestamp

**Stack:** Python, Sentence-Transformers, Qdrant, Groq

---

### Multi-Agent Restaurant Workflow
<!-- Uncomment once the repository is public:
[Repository](https://github.com/hrshvrdhn26/langgraph-restaurant-agent)
-->

A stateful multi-agent system built with LangGraph that models a restaurant order lifecycle from order intake to serving. Specialised agents hand work to each other through an explicit graph with shared state.

- LLM-based routing between nodes with controlled state transitions
- Separate agents for order-taking, kitchen and service
- Streaming execution of the workflow
- Guardrails on allowed transitions and inputs

**Stack:** Python, LangGraph, Groq

---

### Resume and Job Analysis Platform
[Repository](https://github.com/hrshvrdhn26/AIPowered_Resume_Platform)

A full-stack application for querying resume content and comparing it against job descriptions, with retrieval-backed answers.

- Structured extraction of resume information
- Question answering over resume content using retrieval
- Job description analysis, skills matching and gap identification
- Separate backend and frontend services

**Stack:** Python, FastAPI, Qdrant, Groq, JavaScript

## Currently Working On

- Evaluation and optimisation of RAG pipelines (retrieval metrics, chunking and re-ranking trade-offs)
- Agent memory and state management in LangGraph
- Guardrails and safety checks for LLM applications
- Latency and cost reduction for LLM-backed services
- Containerised deployment of AI services

## Open To

Full-time roles in Generative AI, LLM and machine learning engineering, based in Pune or remote within India.
