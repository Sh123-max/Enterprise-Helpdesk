# Enterprise-Helpdesk
# 🧠 AI-Powered Enterprise Helpdesk System

An **LLM-driven enterprise helpdesk assistant** that automates employee support queries for IT, HR, and company policy issues.

## 🚀 Overview
Traditional helpdesks often face challenges like slow ticket routing, inconsistent answers, and poor scalability.  
This project leverages **Large Language Models (LLMs)** and **Retrieval-Augmented Generation (RAG)** to provide instant, accurate, and context-aware answers to employee queries.

## 🧩 Key Features
- **BERT Intent Classifier:** Auto-classifies queries into IT, HR, or Product domains (92% accuracy).  
- **RAG Pipeline (FAISS + T5):** Retrieves relevant knowledge-base content and generates human-like responses.  
- **Quality Refiner Agent:** Evaluates response quality using a binary classifier (95% accuracy).  
- **Multi-Agent Orchestration:** Combines Router, Knowledge Specialist, and Refiner agents for end-to-end automation.  
- **Gradio Interface:** Simple and interactive web-based query panel.

## 🧱 Architecture
1. **Router Agent:** Classifies user intent using fine-tuned BERT.  
2. **Knowledge Specialist:** Fetches and synthesizes answers using FAISS + T5-small generator.  
3. **Refiner Agent:** Validates response quality to ensure clarity and correctness.

## ⚙️ Tech Stack
- **Models:** BERT (Intent Classification), T5-small (Text Generation)  
- **Retrieval:** FAISS Vector Store + MiniLM Sentence Embeddings  
- **Frameworks:** Hugging Face Transformers, LangChain, Gradio  
- **Languages:** Python

## 📊 Performance
- Intent Classification Accuracy: **92%**  
- Quality Validation Accuracy: **95%**  
- Average Response Time: **< 2 seconds (CPU)**
---

> **Result:** A scalable, cost-effective AI Helpdesk capable of 24/7 support with consistent, human-quality responses.
