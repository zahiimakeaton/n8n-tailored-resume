# AI Resume Tailoring Agent (n8n Workflow)

## 🚀 Overview
This n8n workflow automates resume customization by extracting content from a submitted PDF resume, enhancing it using an AI agent, enriching context via web search, and generating an optimized resume in Google Docs.

Designed to reduce manual effort and improve job application success.

---

## ⚙️ Workflow Architecture

### 🔹 Trigger
- **On Form Submission**
  - Accepts user resume (PDF) and job details.

### 🔹 Processing Pipeline
1. **Extract from File**
   - Extracts text from uploaded PDF resume.

2. **AI Agent (Groq Chat Model)**
   - Enhances and tailors resume content.
   - Uses memory for context-aware improvements.
   - Integrates structured output parsing.

3. **Tavily Search**
   - Fetches relevant job/industry insights.
   - Helps align resume with market expectations.

4. **Structured Output Parser**
   - Converts AI output into structured fields (skills, summary, experience).

5. **Google Docs Integration**
   - Creates a new tailored resume document.
   - Updates the document with formatted content.

---

## 🧠 Tech Stack
- **Automation:** n8n
- **LLM:** Groq Chat Model
- **AI Orchestration:** n8n AI Agent node
- **Search Enrichment:** Tavily API
- **Document Generation:** Google Docs API
- **File Processing:** PDF extraction

---

## ✨ Key Features
- 📄 Automatic PDF resume parsing  
- 🤖 AI-powered resume enhancement  
- 🌐 Web search enrichment for relevance  
- 🧩 Structured output for clean formatting  
- 📑 Auto-generated Google Docs resume  

---

## 📊 Impact
- Reduces manual resume tailoring time by up to **80%**
- Ensures keyword optimization for ATS systems
- Produces ready-to-send resumes instantly

---

## 🔗 Use Cases
- Job seekers applying to multiple roles
- Career services automation
- Recruitment agencies
- AI-powered career platforms

---
-
## screenshoits
-workflow:
<img width="1920" height="1080" alt="Screenshot 2026-02-21 045633" src="https://github.com/user-attachments/assets/e775f531-9cf6-4b54-9d35-b8ba868c8983" />
-trigger:
<img width="1066" height="999" alt="Screenshot 2026-02-21 050138" src="https://github.com/user-attachments/assets/2ac098fb-6ddf-49f8-9883-d369839c4ea5" />
-output:
<img width="1920" height="1008" alt="Screenshot 2026-02-21 050310" src="https://github.com/user-attachments/assets/7a494bb3-56d5-4ab5-882d-d5f58a1ff292" />




## 🛠️ Future Improvements
- Multi-format export (PDF, DOCX)
- ATS score estimation
- Job description auto-scraping
- Email delivery automation
