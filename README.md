# 📝 Transformer-Based Text Summarizer & FastAPI Service

An end-to-end Natural Language Processing (NLP) web application built to perform abstractive/extractive text summarization using fine-tuned Transformer architectures. Integrated with a high-performance **FastAPI** backend, the application exposes RESTful JSON endpoints and an interactive HTML web interface for seamless text processing.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![FastAPI](https://img.shields.io/badge/Framework-FastAPI-009688)
![PyTorch](https://img.shields.io/badge/Framework-PyTorch-ee4c2c)
![Transformers](https://img.shields.io/badge/Library-HuggingFace%20Transformers-yellow)
![Domain](https://img.shields.io/badge/Domain-NLP%20%26%20Deep%20Learning-green)

---

## 📌 Executive Summary

Long-form text processing requires intelligent summarization models that preserve key contextual semantics while drastically reducing reading time. This repository presents a complete deep learning and software engineering pipeline: fine-tuning a Transformer model on a specialized text dataset and deploying it via FastAPI with dual support for rendered HTML responses and structured JSON API requests.

---

## 🛠️ System Architecture & NLP Workflow

### 1. Data Preprocessing & Model Training
- **Dataset Preparation:** Cleaned, tokenized, and formatted text-summary sequence pairs using domain-specific tokenizers.
- **Transformer Fine-Tuning:** Trained/fine-tuned a seq2seq Transformer architecture (e.g., BART / T5 / Pegasus) optimized for attention-driven summarization.
- **Evaluation:** Monitored training metrics and validated generated sequence fluency and coherence.

### 2. FastAPI Backend & Endpoint Engineering
- **JSON API Endpoints:** High-performance REST API endpoints designed to accept raw text payloads and return structured JSON responses with key metrics (original length, summary length, inference latency).
- **HTML Web Interface:** Jinja2/HTML templates integrated into FastAPI routes to provide an intuitive browser UI for real-time text input and summarization.
- **Input Validation:** Leveraged Pydantic models to enforce strict request body schemas and parameter validation.

---
