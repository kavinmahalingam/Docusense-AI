Using DocuSense AI, it's easy and straightforward to build policies.

> AI based document intelligence system for legal and policy documents that enables to convert complex documents to readable, understandable and analysable content, while keeping privacy protected.

Hack & Fest AI Innovation Hackathon
SRM Institute of Science and Technology (SRMIST)
Team 2 | Track 1: Document Intelligence Systems | Problem Statement 1.2

---

## About the Project

The DocuSense AI document intelligence system is an AI-based application which helps users to understand complex documents such as land sale agreements, lease agreements, contracts, and Terms of Service.

PDF, picture or plain text file can be added by individuals. It downloads the text, identifies key clauses, translates complicated text in plain language, answers questions about the text and identifies potentially problematic or suspicious clauses.

Also, it has an easy-to-understand Policy Safety Score (0-100) that assists in pinpointing the areas where further attention may be needed.

---

## Key Features

Multi-Format Input: PDF, PNG, JPG/JPEG and raw text.
Important Clause Extraction: extracts important clauses and legal parts.
Multilingual Explanation — Provides explanations of difficult words in English, Tamil, Telugu, Malayalam, Hindi, Spanish and French.
RAG Based Q&A: Answer the Questions on the basis of the Document uploaded.
Recognizes unusual, risky or noteworthy clauses.
A risk score (0-100) with an overall verdict that is explainable: Policy Safety Score.
Document Forensics — Aligns potentially questionable (and/or fraudulent) content for further investigation.
Export analysis reports in Markdown and PDF.
All Core AI processing is done on the local machine with Ollama.

---

## Technology Stack

```text
User
 |
 v
PDF / Image / Text
 |
 v
Text Extraction + OCR
 |
 v
Clause Extraction
 |
 v
Embedding Generation
 |
 v
FAISS Vector Store
 |
 v
Ollama + Llama 3.2
 |
 v
RAG Q&A + Risk Analysis
 |
 v
Safety Score & Verdict
 |
 v
Streamlit Dashboard
 |
 v
PDF / Markdown Report
```

### Main Technologies

Tools used are: Python, Streamlit, Ollama, Llama 3.2, Nomic Embed Text, EasyOCR, FAISS, pdfplumber, pypdf and ReportLab.Technologies used: Python, Streamlit, Ollama, Llama 3.2, Ollama Embed Text, EasyOCR, FAISS, pdfplumber, pypdf and ReportLab.

---

## Quick Start

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

Tap on the app in your browser:

```text
http://localhost:8501
```

---

## Privacy and Responsible AI

DocuSense AI is a local-first application. All documents are processed without calling external AI APIs, with local OCR, embeddings and FAISS and Ollama-based models.

The Policy Safety Score and forensic analysis are AI-aided indicators, which aim to support the user to determine areas of potential concern. Not certification nor legal advice!

---

## Team 2

| Member                      | Registration Number | Contribution                                  |
| --------------------------- | ------------------- | --------------------------------------------- |
| **KADIRISANI SAINATH GOUD** | `RA2411053010033`   | Full-Stack Architecture, RAG and Streamlit    |
| **KAVIN M**                 | `RA2411004010025`   | Team Lead, AI/LLM and Ollama Pipeline         |
| **ANTO CHINNADURAI N A**    | `RA2411004010029`   | Document Parser, Regex and EasyOCR            |
| **DEEBA KUMAR M**           | `RA2411004010039`   | Risk Evaluation and Multilingual Localization |
| **KANISHA R**               | `RA2411004010020`   | QA, PDF Export and Demo Dataset               |

---

## Vision

> The steps for the UNDERSTANDING part of the model are: Upload, Understand, Ask, Analyze, Identify Risks, Make an Informed Decision

DocuSense AI is created to streamline vital paperwork, make them easier to read, use and comprehend for everyone.

---

## Hackathon

Created during Hack and Fest AI Innovation Hackathon
SRM Institute of Science and Technology

Document Intelligence Systems is Track 1 of Team 2.Document Intelligence Systems is Track 1 of Team 2.
**Problem Statement 1.2**
