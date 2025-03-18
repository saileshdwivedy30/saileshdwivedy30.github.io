---
layout: page
title: AskMyEmail - DeepSeek AI-Powered Email RAG Chatbot
description: An AI-powered Retrieval-Augmented Generation (RAG) chatbot that retrieves, analyzes, and chats with your emails using intelligent search and response generation.
img: assets/img/deepseek_email_rag.jpeg
importance: 3
category: work
---
    ---
    Source Code available in the repository
    Github handle: saileshdwivedy30
    Project: AskMyEmail - DeepSeek AI-Powered Email RAG Chatbot
    ---

Source Code: <a href="https://github.com/saileshdwivedy30/Ask-My-Email">Click here</a>\
Demo Video: <a href="https://www.youtube.com/watch?v=3kpnK6ljzY8">Watch Demo</a>

## **Overview**
**AskMyEmail is an AI-powered chatbot that enables intelligent search and interaction with your emails** through **Retrieval-Augmented Generation (RAG)**.  
It integrates **Gmail API, LangChain, ChromaDB, and DeepSeek R1 14B** (via **Ollama**) to **retrieve, analyze, and generate responses** to emails in a **natural, conversational manner**.

By default, the system **only accesses promotional emails**, ensuring **privacy protection**.  
This can be customized by changing the **email label filter** in the query:

```python
query = f"label:promotions after:{date_n_days_ago}"
```

To retrieve **all inbox emails**, modify the label to:

```python
query = f"label:inbox after:{date_n_days_ago}"
```

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/AskMyEmail.png" title="Architecture Diag" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


---
## **Tech Stack**
- **Python** – Core language for development.
- **Gmail API** – Fetches **emails securely**.
- **BeautifulSoup** – Parses **email content**.
- **LangChain** – Embeddings, text processing, and **LLM-powered responses**.
- **ChromaDB** – Enables **fast semantic search** across email content.
- **Ollama + DeepSeek R1 14B** – AI-powered **context-aware responses**.
- **Streamlit** – Provides **interactive chat UI**.

---
## **Core Features**
- **Retrieve relevant emails** using **natural language queries**.  
- **AI-powered response generation** based on email content.  
- **ChromaDB-based semantic search** for **efficient email retrieval**.  
- **LangChain embeddings** for **query understanding & processing**.  
- **DeepSeek 14B (via Ollama) integration** for intelligent responses.  
- **User-friendly Streamlit UI** for seamless interaction.  

---
## **Email Processing & Retrieval Flow**
### **1. Fetch Emails (Gmail API)**
- Retrieves **only promotional emails** by default.  
- Can be customized to **fetch entire inbox**.

### **2. Index Emails (Embedding & Storage)**
- **LangChain processes email text** to create vector embeddings.  
- Stores embeddings in **ChromaDB** for fast retrieval.

### **3. Retrieve Relevant Emails**
- Uses **ChromaDB's vector search** to find **contextually relevant emails**.  
- **LangChain's similarity search** ensures accurate retrieval.

### **4. Generate AI-Powered Responses**
- **DeepSeek R1 14B** (via **Ollama API**) generates **human-like responses** to email queries.  
- Uses **LangChain Prompt Templates** to **structure answers**.

### **5. Interactive Chat UI**
- **Streamlit-based UI** enables **seamless user interaction**.  
- Users can enter **queries, view retrieved emails, and get AI-powered responses**.

---
## **Major Takeaways:**
- **AI-driven email search enhances productivity** by retrieving relevant emails based on queries.  
- **RAG-based responses provide contextual insights** instead of generic keyword matches.  
- **User privacy is prioritized** by defaulting to promotional emails only.  
- **LangChain + ChromaDB ensure highly relevant email retrieval**.  

---
AskMyEmail is built for **professionals, researchers, and individuals** who need **quick and intelligent access to their email information** without manually searching. 🚀
