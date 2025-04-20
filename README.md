# 🛩️ F-16 Pilot Manual Chatbot

**An AI-powered assistant for TO 1F-16A-1 flight manuals**  
*Semantic search engine that helps pilots quickly access critical procedures*

[![Kaggle](https://img.shields.io/badge/Kaggle-Notebook-blue)](https://www.kaggle.com/themuneeb99/pilot-manual)
[![Medium](https://medium.com/@miqbal83a/building-an-ai-chatbot-for-f-16-pilot-manuals-a-technical-deep-dive-8262edaacae5)](BLOG)

## ✨ Features

- **Instant Manual Lookup**  
  Query complex procedures like _"emergency oxygen activation"_ in seconds
- **Page-Referenced Answers**  
  Every response includes original manual page numbers
- **Context-Aware**  
  Remembers last 3 queries for follow-up questions
- **Military-Grade UI**  
  Optimized for cockpit use with bold warnings and minimal scrolling

## 🛠️ Tech Stack

| Component           | Technology Used |
|---------------------|-----------------|
| PDF Processing      | `pdfplumber`    |
| NLP Engine          | `sentence-transformers` |
| Vector Search       | `numpy` cosine similarity |
| Web Interface       | `gradio`        |
| Deployment          | Kaggle / Hugging Face Spaces |

## 📦 Installation

```bash
# Clone repository
git clone https://github.com/yourusername/f16-chatbot.git
cd f16-chatbot

# Install dependencies
pip install -r requirements.txt
