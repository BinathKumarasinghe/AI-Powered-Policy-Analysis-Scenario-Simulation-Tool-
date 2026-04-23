# AI-Powered-Policy-Analysis-Scenario-Simulation-Tool-

🤖 AI-Powered Policy Analysis & Scenario Simulation Tool

📌 Overview

This project is an intelligent web-based system that transforms complex policy documents into actionable insights and adaptive strategies.

#Using the National Digital Government Policy of Sri Lanka as a case study, the application:

Extracts and cleans raw document data
Generates structured summaries
Identifies key policy goals, measures, and principles
Produces scenario-based policy adaptations using AI

⚙️ Tech Stack

Backend: Flask (Python)
NLP: Custom TF-IDF summarization, keyword extraction
AI Integration: OpenAI / Anthropic APIs (optional)
Document Processing:
pdfplumber
PyPDF2
python-docx
Data Processing: Regex, tokenization, sentence scoring

🧠 Core Features

1. 📄 Document Ingestion
Supports PDF, DOCX, and TXT files
Extracts structured text with metadata (pages, tables, etc.)

2. 🧹 Data Cleaning
Removes noise (headers, formatting artifacts)
Fixes broken text (hyphenation, encoding issues)

3. 📊 Smart Summarization
Uses TF-IDF-based extractive summarization
Categorizes content into:
Goals
Measures
Principles
Extracts key policy terms automatically

4. 🎯 Scenario-Based Policy Adaptation

Generates customized policy outputs based on real-world contexts:

Rural (low connectivity, accessibility)
Youth (innovation, startups)
Elderly (inclusivity, accessibility)
Crisis (emergency response)
Investment (FDI, global alignment)
Education / Healthcare

Each scenario produces:

Priority focus
Objectives
Policy statements
Implementation notes

📈 Example Use Case

Using Sri Lanka’s Digital Government Policy, the system can:

Identify that:
Citizen-centric governance is a core principle
Digital inclusion and accessibility are key goals
Transparency and efficiency drive policy direction
Then adapt it into:
👉 A rural implementation strategy (offline-first services, SMS systems)
👉 A startup-friendly framework (APIs, open data, sandbox environments)
👉 A crisis-ready model (emergency data sharing, rapid deployment systems)

🚀 How It Works

Upload policy document
System extracts and cleans text
NLP engine generates structured summary
AI module produces scenario-based adaptations
Output is returned via API / UI

📌 Key Insights from Policy

Citizen-centric digital governance is prioritized
Strong emphasis on data protection & transparency
Push for interoperability and digital identity (SLUDI)
Focus on inclusive and accessible digital services

📦 Project Structure

/app.py
/uploads
/static
/config.py

💡 Future Improvements

Add abstractive summarization (LLM-based)
Frontend dashboard (React / Streamlit)
Multi-language support (Sinhala / Tamil)
Real-time policy comparison engine

🎯 Impact

This system can support:

Government decision-making
Policy analysis teams
Researchers & analysts
Public sector innovation
