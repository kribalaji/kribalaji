# Hi, I'm Balaji Krishnamoorthy 👋

### GenAI Engineer · Agentic AI Engineer · Data Platform Architect

I design and build **production-grade LLM systems** (multi-agent workflows, RAG and agent guardrails) and the **cloud data platforms** that feed them.

22 years in IT, including 15 at Cognizant. I lead enterprise AI and data-platform programs on **GCP and AWS** across agriculture, retail and consumer goods: warehouse migrations to BigQuery, ML platform migrations to Vertex AI, and RAG advisory systems on AWS Bedrock.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Balaji_Krishnamoorthy-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/balaji-krishnamoorthy-455835173)
![Location](https://img.shields.io/badge/Based_in-Chennai,_India-555)

---

## 🧠 What I build

- **Agentic systems:** LangGraph supervisor graphs, tool-using agents, durable checkpoints, human-in-the-loop approval
- **Grounded GenAI:** RAG with cited sources, hybrid and advanced retrieval (HyDE, MMR, multi-query), RAGAS evaluation
- **Agent safety and governance:** prompt-injection defense, PII redaction, deny-by-default tool permissions, audit trails
- **Data platforms:** enterprise warehouse migration (Teradata → BigQuery), lakehouse and pipeline design, data modelling, governance, and data readiness for AI
- **ML & LLM platforms:** MLOps and LLMOps on Vertex AI, SageMaker and Bedrock, model migration, observability, containerized delivery

My design rule: **the LLM narrates; deterministic code decides.** Numbers, thresholds and money never come from a model guess.

---

## 🚀 Featured work

### [Crop Insurance Claims: Agentic AI Platform](https://github.com/kribalaji/crop-insurance-agent)
A multi-agent system that assesses index-based crop-insurance claims end to end.
- Weather, Policy, Claim and Advisory agents orchestrated as a **LangGraph** supervisor graph
- Policy triggers verified with **RAG over the policy PDF**, with every threshold page-cited
- Real **ERA5 (Copernicus)** reanalysis weather data, not mocked inputs
- Durable checkpointing and an `interrupt()`-based **human approval** step before any payout
- **FastAPI** + **MCP** tool server + **Streamlit** reviewer UI, shipped as **Docker Compose**

`LangGraph` `RAG` `MCP` `FastAPI` `Gemini` `Docker`

### [LangChain + LangGraph + RAGAS: Engineering Reference](https://github.com/kribalaji/Langchain-Graph-concepts)
Runnable, progressive examples from LCEL chains to production patterns: RAG with citations, advanced retrieval, checkpointing, human-in-the-loop, ReAct agents, multi-agent supervisor, parallel subgraphs, and RAGAS evaluation.

`LangChain` `LangGraph` `LlamaIndex` `RAGAS`

### [Multi-Provider LangChain Patterns](https://github.com/kribalaji/langchain-ollama-huggingface)
LangChain examples across Ollama, Gemini, Hugging Face, Cohere and Together AI: agents, RAG, LCEL, async multi-agent patterns, a SQL generator, and a FastAPI service with a Docker setup.

`LangChain` `Ollama` `Hugging Face`

### 🔨 In progress
- **Agent Guardrail & Eval Gateway:** a FastAPI proxy in front of AI agents. It blocks prompt injection, redacts PII, enforces deny-by-default MCP tool permissions per agent, and writes an audit log. Next: LLM-as-judge classifier, approval queue, Open Policy Agent, OpenTelemetry, and a Helm deployment on Kubernetes.
- **My AI Studio:** a local-first workspace for designing LLM workflows, building or importing agents, and defining their input and output flows.

---

## 🛠️ Stack

- **GenAI & agents:** LangGraph · LangChain · LlamaIndex · MCP · RAGAS · Gemini · Claude · Ollama · Hugging Face
- **Retrieval:** ChromaDB · FAISS · embeddings · hybrid and advanced retrieval
- **Backend:** Python · FastAPI · Streamlit · uv · pytest
- **Data platform:** BigQuery · Teradata · AWS data services · SQL · Python data pipelines
- **Cloud & MLOps:** Google Cloud (Vertex AI) · AWS (Bedrock, SageMaker) · Docker · Kubernetes

## 🏅 Certifications

![GCP](https://img.shields.io/badge/Google_Cloud-Professional_Cloud_Architect-4285F4?logo=googlecloud&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-Data_Engineer_Associate-FF9900?logo=amazonaws&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-Machine_Learning_Engineer_Associate-FF9900?logo=amazonaws&logoColor=white)

---

📫 Open to conversations about **GenAI architecture, agentic AI and LLM platform roles**. Reach me on [LinkedIn](https://www.linkedin.com/in/balaji-krishnamoorthy-455835173).
