```text
████████╗██╗  ██╗ ██████╗ ███╗   ███╗ █████╗ ███████╗
╚══██╔══╝██║  ██║██╔═══██╗████╗ ████║██╔══██╗██╔════╝
   ██║   ███████║██║   ██║██╔████╔██║███████║███████╗
   ██║   ██╔══██║██║   ██║██║╚██╔╝██║██╔══██║╚════██║
   ██║   ██║  ██║╚██████╔╝██║ ╚═╝ ██║██║  ██║███████║
   ╚═╝   ╚═╝  ╚═╝ ╚═════╝ ╚═╝     ╚═╝╚═╝  ╚═╝╚══════╝

            AI SYSTEMS  /  LLM + RAG  /  AGENTIC BACKENDS
```

# AI/ML Engineer

Building AI applications from research and prototypes through backend services, deployment, and iteration. My work focuses on retrieval, agent workflows, and backend systems that connect AI capabilities to real products.

**Python · FastAPI · Django · LangChain · LangGraph · PyTorch**  
📍 Kottayam, India &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/thomasantony73/) &nbsp;·&nbsp; [Email](mailto:thomasantony14@gmail.com)

---

## → Current Focus

```text
→ Retrieval that combines lexical and semantic signals
→ Agents that can route, use tools, and take user-directed actions
→ Backend AI systems that connect models, tools, APIs, and product workflows
→ Python APIs that connect models to real products
```

## → Featured Systems

### 01 / Agentic Digital Signage CMS Assistant — Professional System

**From retrieval chatbot to an assistant that can answer questions and support user-directed CMS actions.** I worked on routing between retrieval and planning/execution workflows, with attention to token use and model cost.

```text
User request
     │
     ▼
Intent + workflow routing
     ├──────────────► Retrieval path ─────► Answer
     │
     └──────────────► Planning / tools ───► CMS action
```

`LangChain` · `LangGraph` · `FastAPI` · `AWS EC2`

*Employer system; source code and customer deployment are not public.*

### 02 / Hybrid RAG System

**BM25 + embeddings + MMR reranking**, with multi-turn conversation handling and persistent sessions. This work recorded a **40% improvement in retrieval relevance**.

```text
                         ┌─ BM25 ──────────────┐
Query ──► retrieval ─────┤                      ├──► MMR reranking
                         └─ embeddings ────────┘           │
                                                           ▼
                                                context + LLM response
```

`LangChain` · `ChromaDB` · `MongoDB Atlas` · `FastAPI`

### 03 / WhatsApp → Meta Inbox — Professional System

**A unified business inbox across Instagram, Messenger, and WhatsApp**, built from scratch as a module inside an existing ERP. The system is being converted from a WhatsApp CRM into a broader Meta inbox with shared messaging, webhooks, authentication, onboarding, and templates.

```text
Instagram ─┐
Messenger ─┼──► Meta webhooks + tenant routing ──► unified inbox
WhatsApp ──┘                                      └─► ERP workflows
```

`Django` · `Meta APIs` · `Webhooks` · `REST APIs` · `Multi-tenant backend`

*Client/ERP system; source code and customer data are not public.*

### 04 / Multi-Agent News Generation — Public Repository

**Research-to-article workflow** with hierarchical agents, real-time web search, asynchronous processing, and concurrent article generation. Deployed on Google Cloud Run.

```text
Topic ──► coordinator ──► research ──► generation ──► article
                         └──── asynchronous work ──────┘
```

`Google ADK` · `Gemini` · `FastAPI` · `Google Cloud Run`

[View the repository](https://github.com/7H0M45-4N70NY/news_agent) · *Live deployment link is being revalidated.*

---

## → Other Work

- **Text classification:** built a BERT-based system that achieved **92% F1-score**.
- **Teaching:** deliver weekend data science and machine learning sessions and mentor students through practical projects.

Computer-vision and MLOps work remains available as secondary public evidence in the [VisionFlow repository](https://github.com/7H0M45-4N70NY/vision-ml-system), but is not the lead direction for my current search.

The system descriptions above are drawn from my professional work. Employer and client source code is not linked here. You can explore my [public repositories](https://github.com/7H0M45-4N70NY?tab=repositories) separately.

## → Technical Stack

| Area | Tools and methods I have used |
|---|---|
| LLM applications | LangChain, LangGraph, Google ADK, BM25, embeddings, MMR, tool calling |
| ML and vision | PyTorch, RFDETR, YOLO, RetinaFace, MTCNN, ByteTrack, ONNX Runtime |
| MLOps | Roboflow, DagsHub, MLflow, DVC, GitHub Actions |
| Backend | Python, Django, FastAPI, REST APIs, async programming, authentication |
| Infrastructure and data | Docker, AWS EC2, Google Cloud Run, Linux, Nginx, MongoDB, PostgreSQL, ChromaDB |

## → Currently Learning

**Advanced Route — Production AI Engineering**, Krish Naik Academy — **in progress**. The curriculum covers LLM architecture, fine-tuning, RAG, agentic systems, evaluation, and GenAIOps. [Course details](https://advancedroute.krishnaik.cloud/).

---

```text
BUILD THE SYSTEM  →  TEST THE BEHAVIOUR  →  IMPROVE WHAT THE EVIDENCE SHOWS
```

[LinkedIn](https://www.linkedin.com/in/thomasantony73/) · [Email](mailto:thomasantony14@gmail.com) · [Repositories](https://github.com/7H0M45-4N70NY?tab=repositories)
