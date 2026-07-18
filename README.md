# Research Paper AI Agent

> **An Agentic AI-powered research assistant that performs semantic paper search, intelligent summarization, keyword extraction, and context-aware question answering using Large Language Models.**

---

## Overview

Research Paper AI Agent is an end-to-end **Agentic AI** application designed to simplify academic research. Instead of relying on traditional keyword-based search, the system understands the semantic meaning of a user's query, retrieves the most relevant research papers using vector embeddings, summarizes the retrieved content, extracts important keywords, and generates intelligent responses using a Large Language Model.

The project combines **Natural Language Processing (NLP)**, **Vector Databases**, and **Generative AI** to create an intelligent research assistant capable of understanding and reasoning over scientific literature.

---

## Features

- Semantic Search over Research Papers
- Agentic AI Workflow
- Fast Vector Search using FAISS
- Automatic Paper Summarization
- Keyword Extraction using KeyBERT
- Context-Aware Responses using Llama 3.1
- Efficient Retrieval with Precomputed Embeddings

---

## AI Agent Workflow

```text
                  User Query
                       │
                       ▼
      Sentence Transformer Embedding
                       │
                       ▼
          FAISS Semantic Vector Search
                       │
                       ▼
       Retrieve Relevant Research Papers
                       │
          ┌────────────┼────────────┐
          ▼            ▼            ▼
     Paper Summary   Keywords   Context
       (BART)       (KeyBERT)
          │            │
          └────────────┼────────────┘
                       ▼
          LangChain + Llama 3.1 (Groq)
                       │
                       ▼
             Intelligent AI Response
```

## Tech Stack

| Category | Technology |
|----------|------------|
| Programming Language | Python |
| Development Environment | Google Colab |
| Dataset | ML-ArXiv Research Papers |
| Embedding Model | all-MiniLM-L6-v2 |
| Vector Database | FAISS |
| Summarization Model | facebook/bart-large-cnn |
| Keyword Extraction | KeyBERT |
| LLM Framework | LangChain |
| Large Language Model | Llama 3.1 (Groq API) |

---
## Outputs
- Semantic Search Results
- Retrieved Research Papers
- Generated Summary
- Extracted Keywords
- AI Agent Response

---

