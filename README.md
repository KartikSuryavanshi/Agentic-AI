# Agentic-AI

Hands-on implementation of **Agentic AI systems** including RAG, Multi-Agent workflows, LangGraph orchestration, Langflow pipelines, Vector Databases, and end-to-end AI applications.

---

## 📌 About This Repository

This repository contains practical implementations of modern **Agentic AI architectures**, where LLMs move beyond simple chatbots and become decision-making systems capable of:

- Tool usage  
- Multi-step reasoning  
- Workflow orchestration  
- Retrieval-Augmented Generation (RAG)  
- Multi-Agent collaboration  
- Memory integration  

The focus is on building production-style AI systems.

---

## 🛠 Frameworks & Tools Used

- **LangChain** – LLM orchestration & chaining  
- **LangGraph** – Stateful multi-agent workflow orchestration  
- **Langflow** – Visual pipeline builder  
- **Phidata** – Agent framework  
- **Google Gemini** – LLM provider  
- **DataStax Astra DB** – Cloud vector database  
- **FAISS / Chroma** – Local vector stores  
- **Python** – Core language  

---

## 📂 Project Structure

### 1️⃣ 1-BasicAgents
- Creating first AI agent  
- Tool calling  
- Prompt engineering  
- Memory handling  

---

### 2️⃣ Financial AI Agent
Agent capable of:
- Financial reasoning  
- Structured analysis  
- Tool usage  
- Multi-step workflows  

Built using:
- Phidata  
- Gemini  

---

### 3️⃣ Multi-Agent RAG With Vector Database
- Document ingestion  
- Text chunking  
- Embedding generation  
- Vector database integration (Astra DB / FAISS)  
- Retrieval-Augmented Generation  
- Multi-agent reasoning  

Built using:
- LangChain  
- LangGraph  
- Astra DB  

---

### 4️⃣ Video Summarizer Agent
- Extracts video transcript  
- Performs chunking  
- Applies summarization chain  
- Generates structured summaries  

Built using:
- Phidata  
- Gemini  

---

### 5️⃣ 📄 PDF Assistant (RAG-Based PDF Summarizer)

An intelligent document assistant that can:

- Upload and process PDF files  
- Perform text chunking  
- Generate embeddings  
- Store vectors in database  
- Retrieve relevant context  
- Answer questions from PDF  
- Generate document summaries  

Architecture Flow:

PDF → Text Extraction → Chunking → Embeddings → Vector DB → Retriever → LLM → Answer  

Built using:
- LangChain  
- Vector Database (Astra DB / FAISS)  
- Gemini / LLM APIs  

---

## 🔄 Langflow Integration

This repository also explores **Langflow** for visually building Agentic AI systems.

### What is Langflow?

Langflow is a drag-and-drop interface built on top of LangChain that allows you to design and test LLM pipelines without heavy coding.

### Example RAG Flow

User Query  
↓  
Retriever (Vector DB)  
↓  
Context Injection  
↓  
Prompt Template  
↓  
LLM  
↓  
Final Answer  

### Example Agent Flow

User → Agent → Tool Selection → Tool Execution → LLM → Final Output  

### Why Langflow?

- Rapid prototyping  
- Visual debugging  
- Better understanding of RAG systems  
- Exportable to Python  
- Faster experimentation  

---

## 🧠 Concepts Covered

- Prompt Engineering  
- RAG (Retrieval-Augmented Generation)  
- Embeddings  
- Vector Databases  
- Tool Calling Agents  
- Multi-Agent Systems  
- Workflow Orchestration (LangGraph)  
- Visual AI Pipeline Design (Langflow)  
- End-to-end AI system design  
