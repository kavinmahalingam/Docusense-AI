The DocuSense AI is a simple & honest policy companion.

> Document Intelligence System with AI that is privacy-focused and helps legal and policy documents become more readable.

The Hack & Fest AI Innovation Hackathon takes place at SRM Institute of Science and Technology.Hack & Fest AI Innovation Hackathon is held at SRM Institute of Science and Technology.
Team 2 | Track 1: Document Intelligence Systems | Problem Statement 1.2

---

## 🚀 About the Project

It not only allows users to understand complex documents like land sale agreement, lease agreement, contracts, and Terms of Service, but also helps them access these files.

Users can upload a PDF, image or text, and the system will read it, identify important clauses, explain them in a simple way, answer questions based on the document, and mark potentially risky or suspicious terms.

The system also provides a “Policy Safety Score” (0-100) that will be explainable in order to assist the user in determining where he or she should focus attention.

---

## ✨ Key Features

Support for multi-format Input: PDF, PNG, JPG/JPEG and raw text
Smart Clause Extraction: Highlights key sections and legal clauses
🇪 **Explanation in the Target Language** — Generates explanations in the target language from complex terms.
Q&A with document context provided in a RAG model.
⚖️ Risk Analysis — Identifies clauses that are unusual, risky and noteworthy
Safety Score — Offers a 0-100 risk-based score, overall verdict
Readiness for legal action against suspicious or fraudulent content (potentially)
Please consult the user's guide for instructions on how to use the text.Please refer to user's guide for instructions on how to use the text (English, Tamil, Telugu, Malayalam, Hindi, Spanish and French).
📥 Audit Reports: Export results in Markdown or PDF format
Core AI processing is done locally using Ollama — Privacy First

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
Ollama + llama3.2
 ↓
RAG Q&A + Risk Analysis
 ↓
Safety Score & Verdict
 ↓
Streamlit Dashboard
 ↓
PDF / Markdown Report
```

### Main Technologies

The tools used for this project are Python, Streamlit, Ollama, Llama 3.2, EasyOCR, FAISS, pdfplumber, pypdf, and ReportLab.

---

## ⚡ Quick Start

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Download local AI models

```bash
ollama pull llama3.2
ollama pull nomic-embed-text
```

### 3. Run the application

```bash
streamlit run app.py
```

Open:

```text
http://localhost:8501
```

---

## 🔐 Privacy & Responsible AI

DocuSense AI aims to be built as a **local-first app**. Instead of using external AI APIs, documents are processed using local OCR, embeddings, FAISS and Ollama models.

The safety score produced and forensic results are provided as AI-assisted indicators, not legal certification or legal advice.

---

## 👥 Team 2

| Member                      | Contribution                                |
| --------------------------- | ------------------------------------------- |
Full-Stack Architecture, RAG & Streamlit
| **KAVIN M**                 | Team Lead, AI/LLM & Ollama Pipeline         |
| **ANTO CHINNADURAI N A**    | Document Parser, Regex & EasyOCR            |
DEEBA KUMAR M | Risk Evaluation & Multilingual Localization |
| **KANISHA R**               | QA, PDF Export & Demo Dataset               |

---

## 🎯 Vision

> Upload, Understand, Ask, Analyze, Identify Risks, Make an Informed Decision

DocuSense AI is designed to simplify, clarify, and make important documents easily accessible and understandable for all.

SRMIST 🏆 is a Built for Hack & Fest AI Innovation Hackathon.
