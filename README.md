# 📄 DocuSense AI — Simple & Honest Policy Companion

> **A privacy-focused Document Intelligence System that uses AI to make complex legal and policy documents easier to read, understand, and analyze.**

**Hack & Fest AI Innovation Hackathon**
**SRM Institute of Science and Technology (SRMIST)**
**Team 2 | Track 1: Document Intelligence Systems | Problem Statement 1.2**

---

## 🚀 About the Project

**DocuSense AI** is an AI-powered document intelligence system designed to help users understand complex documents such as **land sale agreements, lease agreements, contracts, and Terms of Service**.

Users can upload a **PDF, image, or raw text**. The system extracts the content, identifies important clauses, explains complex terms in simple language, answers questions based on the uploaded document, and highlights potentially risky or suspicious clauses.

It also generates an **explainable Policy Safety Score (0–100)** to help users identify areas that may require additional attention.

---

## ✨ Key Features

* 📄 **Multi-Format Input** — Supports PDF, PNG, JPG/JPEG, and raw text.
* 🔍 **Smart Clause Extraction** — Identifies important sections and legal clauses.
* 🌐 **Multilingual Explanation** — Explains complex terms in English, Tamil, Telugu, Malayalam, Hindi, Spanish, and French.
* 💬 **RAG-Based Q&A** — Answers questions using the uploaded document as context.
* ⚖️ **Risk Analysis** — Identifies unusual, risky, or noteworthy clauses.
* 📊 **Policy Safety Score** — Provides an explainable risk score from 0–100 with an overall verdict.
* 🚨 **Document Forensics** — Highlights potentially suspicious or fraudulent content for further review.
* 📥 **Audit Reports** — Exports analysis in Markdown and PDF formats.
* 🔐 **Privacy First** — Core AI processing is performed locally using Ollama.

---

## 🏗️ Technology Stack

```text
User
 ↓
PDF / Image / Text
 ↓
Text Extraction + OCR
 ↓
Clause Extraction
 ↓
Embedding Generation
 ↓
FAISS Vector Store
 ↓
Ollama + Llama 3.2
 ↓
RAG Q&A + Risk Analysis
 ↓
Safety Score & Verdict
 ↓
Streamlit Dashboard
 ↓
PDF / Markdown Report
```

### 🛠️ Main Technologies

**Python • Streamlit • Ollama • Llama 3.2 • Nomic Embed Text • EasyOCR • FAISS • pdfplumber • pypdf • ReportLab**

---

## ⚡ Quick Start

### 1. Install Dependencies

```bash
pip install -r requirements.txt
```

### 2. Download Local AI Models

```bash
ollama pull llama3.2
ollama pull nomic-embed-text
```

### 3. Run the Application

```bash
streamlit run app.py
```

Open the application in your browser:

```text
http://localhost:8501
```

---

## 🔐 Privacy & Responsible AI

DocuSense AI follows a **local-first approach**. Instead of depending on external AI APIs, documents are processed using local OCR, embeddings, FAISS, and Ollama-based models.

The **Policy Safety Score** and forensic analysis are AI-assisted indicators intended to help users identify areas that may require attention. They **do not constitute legal certification or professional legal advice**.

---

## 👥 Team 2

| Member                      | Registration Number | Contribution                                |
| --------------------------- | ------------------- | ------------------------------------------- |
| **KADIRISANI SAINATH GOUD** | `RA2411053010033`   | Full-Stack Architecture, RAG & Streamlit    |
| **KAVIN M**                 | `RA2411004010025`   | Team Lead, AI/LLM & Ollama Pipeline         |
| **ANTO CHINNADURAI N A**    | `RA2411004010029`   | Document Parser, Regex & EasyOCR            |
| **DEEBA KUMAR M**           | `RA2411004010039`   | Risk Evaluation & Multilingual Localization |
| **KANISHA R**               | `RA2411004010020`   | QA, PDF Export & Demo Dataset               |

---

## 🎯 Vision

> **Upload → Understand → Ask → Analyze → Identify Risks → Make an Informed Decision**

DocuSense AI aims to make important documents **simpler, clearer, more accessible, and easier to understand for everyone**.

---

## 🏆 Hackathon

**Built for the Hack & Fest AI Innovation Hackathon**
**SRM Institute of Science and Technology (SRMIST)**

### Team 2 — Track 1

**Document Intelligence Systems | Problem Statement 1.2**

---
