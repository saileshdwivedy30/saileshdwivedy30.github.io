---
layout: page
title: ImageSense AI - Image Search Quality Optimization
description: An AI-powered image search engine that enhances search capabilities by integrating Large Language Models (LLMs) to better understand user intent and deliver more relevant search results.
img: assets/img/imagesense_ai.gif
importance: 2
category: work
---
    ---
    Source Code available in the repository
    Github handle: saileshdwivedy30
    Project: ImageSense AI - Image Search Quality Optimization
    ---

Source Code: <a href="https://github.com/saileshdwivedy30/ImageSense-AI" target="_blank">Click here</a>\
Demo Video: <a href="https://www.youtube.com/watch?v=5Yf5CNzVpbg">Watch Demo</a>
Dataset Link: <a href="https://www.kaggle.com/datasets/adityajn105/flickr8k" target="_blank">View Dataset</a>

## **Overview**
**An AI-powered image search engine utilizing Large Language Models (LLMs) and OpenAI’s CLIP model** to enhance search accuracy by better understanding **user queries and intent**.  
Key functionalities include **query expansion, text-to-image search, and efficient similarity search** using **FAISS and CLIP embeddings**.

The system ensures **high-quality image search results** by leveraging **LLaMA-based query expansion** and **FAISS-based image retrieval**, all within a **user-friendly Streamlit interface**.

---
## **Tech Stack**
- **Python** – Core language for development.
- **OpenAI CLIP Model** – Extracts **image and text embeddings**.
- **FAISS (Facebook AI Similarity Search)** – Enables **fast similarity search** among images.
- **LLaMA 3.2 3B Model** – Hosted via **Ollama API** for **query expansion**.
- **Streamlit** – Builds the **interactive web interface**.
- **PIL (Pillow)** – Handles **image processing**.

---
## **Dataset Details**
- **Dataset:** Flickr8k  
- **Dataset Source:** Kaggle – [Dataset Link](https://www.kaggle.com/datasets/adityajn105/flickr8k)

---
## **Image Processing & Search Flow**
### **1. Image Embedding Extraction**
- Extracts embeddings from **all images** using **OpenAI CLIP model**.
- Stores embeddings in a **predefined folder** for efficient retrieval.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/imagesense_ai_embeddings.png" title="Image Embedding Process" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

---
### **2. Query Expansion (LLaMA-based)**
- Enhances **user queries** using **LLaMA 3.2 3B Model** hosted via **Ollama API**.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/imagesense_ai_query_expansion.png" title="Query Expansion Process" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

---
### **3. Image Search with FAISS**
- Converts the **expanded text query** into **embeddings** using CLIP.
- Uses **FAISS** for fast retrieval of the most **similar images**.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/imagesense_ai_faiss.png" title="Image Retrieval using FAISS" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

---
### **4. Visual Interface (Streamlit)**
The **user-friendly web interface** allows:
- **Search queries input** and **automatic query expansion**.
- **Matching images display** based on **FAISS retrieval**.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/imagesense_ai_ui.png" title="ImageSense AI Search Interface" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

---
## **Major Takeaways:**
- **LLM-enhanced image search significantly improves relevance** by understanding user intent.  
- **Query expansion via LLaMA helps refine ambiguous search terms**.  
- **CLIP & FAISS enable fast and accurate image retrieval**.  
- **User-friendly interface** makes AI-powered image search easily accessible.  

---
This **interactive AI-powered image search engine** is built for **developers, content creators, and researchers** to find **highly relevant images** dynamically. 🚀
