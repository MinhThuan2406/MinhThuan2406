<!-- HEADER -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=220&section=header&text=Hi%2C%20I'm%20Thuan&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Engineer%20%7C%20RAG%20%7C%20Agentic%20AI&descSize=20&descAlignY=58" alt="Header" />

<br/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3500&pause=1000&color=A78BFA&center=true&vCenter=true&width=750&lines=AI+Engineer+at+FPT+Software;Building+RAG+%26+Agentic+AI+Systems;Exploring+LLM+Engineering+%26+LLMOps;From+Research+to+Production-Ready+AI" alt="Typing SVG" />
</a>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=MinhThuan2406&label=Profile%20Views&color=8b5cf6&style=for-the-badge" alt="Profile Views" />
<a href="https://www.linkedin.com/in/nguyenthuan2406/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://www.facebook.com/its.thuannm/"><img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook" /></a>
<a href="https://thuannm04.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>

</div>

---

## About Me

```python
class Thuan:
    def __init__(self):
        self.name = "Nguyen Minh Thuan"
        self.role = "AI Engineer"
        self.company = "FPT Software"

        self.education = {
            "degree": "B.Sc. Computer Science",
            "university": "International University - VNU-HCM",
        }

        self.experience = [
            "AI Engineer @ FPT Software",
            "Former AI Engineer Intern @ HIPTECH",
            "Former Software Engineer Intern @ ITP VNU-HCM",
        ]

        self.interests = [
            "Retrieval-Augmented Generation (RAG)",
            "Agentic AI & Multi-Agent Systems",
            "LLM Engineering & LLMOps",
            "Backend Architecture & High-Concurrency APIs",
            "System Design & Low-Latency Optimization",
        ]

    def currently_working_on(self):
        return [
            "Architecting resilient multi-agent workflows with LangGraph",
            "Benchmarking hybrid retrieval (Dense + Sparse + GraphRAG)",
            "Taming hallucinations via production-grade LLM evaluation",
            "Bridging the gap between raw research and deployment",
        ]

    def execute_lifestyle(self):
        return {
            "fuel": "Black coffee",
            "routine": "Push · Pull · Legs",
            "mindset": "Benchmark everything",
        }
```

Computer Science graduate from International University, VNU-HCM, working as an AI Engineer at FPT Software. I specialize in designing and deploying end-to-end AI systems with a heavy focus on Advanced RAG, Multi-Agent Architectures, and LLMOps.

Previously engineered internal GenAI workflows and multi-agent recommendation engines at HIPTECH, alongside building telemetry analytics infrastructure at ITP, VNU-HCM.

---

## Core Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,fastapi,postgres,docker,mysql,mongodb,neo4j,git,github&theme=dark" alt="Core stack" />

</div>

| Area | Technologies |
| :--- | :--- |
| **AI / LLM** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langgraph&logoColor=white) |
| **Retrieval & Search** | Vector DBs (Milvus, ChromaDB) · BM25 · Hybrid Search (RRF) · Cross-Encoder Reranking · GraphRAG |
| **Backend & Infra** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) RESTful APIs · High-Throughput Pipelines · System Design |
| **Databases** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white) ![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white) |
| **LLMOps & Quality** | RAGAS · TruLens · Tracing & Observability · Metric Benchmarking (Recall@K, MRR, Faithfulness) |

---

## Featured Projects

### WARP Recommender

Multi-agent intelligence system for contextual, hyper-relevant hardware and product matching.

**Role:** AI Engineer Intern (HIPTECH)

**Key Deliverables:**
- Designed a coordinated multi-agent pipeline decoupling user intent parsing, domain-constraint validation, and dynamic scoring.
- Combined vector similarity search with deterministic rule-based filters to eliminate irrelevant catalog suggestions.
- Deployed low-latency inference endpoints wrapped in FastAPI for internal tooling integration.

**Result:** Cut down search friction across multi-variant product specs, delivering sub-second context-aware recommendations.

**Tech:** Python · FastAPI · Vector Search · Agentic Workflows · Docker · PostgreSQL

---

### H5P Telemetry & Learning Analytics

High-throughput telemetry and analytics engine capturing fine-grained student interaction data.

**Role:** Lead Engineer / Thesis Researcher (ITP, VNU-HCM)

**Key Deliverables:**
- Designed and deployed a robust REST API platform capturing real-time xAPI telemetry from H5P interactive learning modules.
- Modeled relational schemas in PostgreSQL to aggregate high-volume student interaction streams and retention curves.
- Seamlessly integrated the middleware with the VNU-HCM MOOC infrastructure running on WordPress.

**Result:** Successfully defended undergraduate thesis; enabled real-time learning telemetry and visual feedback for instructors.

**Tech:** Python · FastAPI · PostgreSQL · H5P / xAPI · Docker · WordPress API

---

### Traceable Automotive Voice Co-pilot

Context-aware, traceable in-cabin voice assistant built for safety-critical automotive environments.

**Role:** Team Leader & AI Architect (Team Wheelchair)

**Key Deliverables:**
- Architected a deterministic, safety-bounded agentic copilot for Android Automotive OS (AAOS) to handle hands-free driver commands.
- Implemented verifiable tool-calling with auditable decision traces, ensuring the system fails gracefully under noisy sensory inputs.
- Orchestrated real-time speech processing and LLM execution loops to minimize driver cognitive load.

**Result:** Top 13 Finalist out of 300+ teams nationwide at the FPT Automotive Hackathon 2026.

**Tech:** Python · LangChain / LangGraph · Android Automotive OS (AAOS) · Speech Processing · Tool Calling

---

## Selected Experiments

### Multi-Expert ReAct Research Agent

- Multi-expert research architecture built with LangGraph.
- Bounded ReAct loops for structured agent reasoning.
- Agent orchestration, state management and tool execution.
- Trade-offs between autonomous reasoning and controlled execution.
- Configurable LLM integration.

**Tech:** Python · LangGraph · LangChain · ReAct · Multi-Agent Systems

---

### RAG Optimization & Evaluation

- Naive RAG, Hybrid Search and advanced retrieval strategies.
- BM25, dense retrieval, Reciprocal Rank Fusion (RRF), Cross-Encoder reranking.
- GraphRAG and knowledge-graph-based retrieval.
- Retrieval and generation quality measured with Recall@K, MRR, Faithfulness and RAGAS.
- LLMOps, observability and production-oriented evaluation.

**Tech:** Python · LangChain · Milvus · BM25 · RAGAS · Neo4j · LangGraph

---

## GitHub Stats

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=MinhThuan2406&theme=nightowl&hide_border=true&include_all_commits=true&count_private=true&show_icons=true" alt="Stats" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MinhThuan2406&theme=nightowl&hide_border=true&layout=compact&langs_count=8" alt="Top languages" />

</div>

---

<div align="center">

### *"Don't just prompt an LLM; build the harness, ground the data, and evaluate the trade-offs."*

<br/>

<a href="https://thuannm04.vercel.app">Portfolio</a>
&nbsp; · &nbsp;
<a href="https://www.linkedin.com/in/nguyenthuan2406/">LinkedIn</a>
&nbsp; · &nbsp;
<a href="https://github.com/MinhThuan2406">GitHub</a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=120&section=footer" alt="Footer" />

</div>
