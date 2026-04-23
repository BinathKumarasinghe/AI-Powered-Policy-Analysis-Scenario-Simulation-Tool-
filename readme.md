# PolicyLens - Policy Summarisation & Scenario Generation

PolicyLens is a Flask-based web application that allows users to:
- Upload policy documents (PDF, DOCX, TXT)
- Extract and clean text
- Generate structured summaries using NLP (TF-IDF)
- Adapt policies for different real-world scenarios
- Optionally use AI (OpenAI / Anthropic) for advanced policy drafting

---

## Features

### 1. Document Processing
- Supports PDF, DOCX, and TXT files
- Uses:
  - pdfplumber (primary PDF extraction)
  - PyPDF2 (fallback)
  - python-docx (DOCX parsing)

### 2. Text Cleaning & NLP
- Removes formatting noise
- Tokenization and stop-word filtering
- TF-IDF based sentence scoring
- Extractive summarization

### 3. Structured Summaries
Generates:
- Goals & Objectives
- Key Measures
- Guiding Principles
- Key Terms

### 4. Scenario-Based Policy Generation
Supports multiple contexts:
- Rural
- Youth / Startups
- Elderly / Accessibility
- Crisis / Emergency
- Investment
- Education
- Healthcare

Includes:
- Template-based generation (offline mode)
- Optional AI-powered generation

### 5. REST API Endpoints

| Endpoint        | Method | Description                  |
|----------------|--------|------------------------------|
| /api/health    | GET    | System status                |
| /api/upload    | POST   | Upload & extract file        |
| /api/summarise | POST   | Generate summary             |
| /api/generate  | POST   | Generate policy draft        |
| /api/scenarios | GET    | Get preset scenarios         |

---

## Installation

### 1. Clone the repository
```bash
git clone <your-repo-url>
cd policylens