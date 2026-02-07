# 🤖 Agentic Lead Researcher & Outreach Automation
### *Enterprise-Grade n8n Workflow with GPT-4o Intelligence & Custom Error Recovery*

---

![n8n](https://img.shields.io/badge/n8n-Workflow%20Automation-FF6C37?style=for-the-badge&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4o-412991?style=for-the-badge&logo=openai&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-Database-34A853?style=for-the-badge&logo=googlesheets&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Error%20Handling-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 🗺️ Workflow Architecture
This project implements an autonomous **Agentic Intelligence** system designed to transform raw company domains into high-conversion outreach pipelines.

### 🖼️ Workflow Overview
![Lead Generation Workflow](./assets/workflow-main.png)
*Visual representation of the n8n logic: Ingestion ⮕ Scrape ⮕ Qualify ⮕ Personalize.*

### 🛠️ Key Features
* **Live DOM Scraping:** Dynamically extracts content from company websites to understand their value proposition in real-time.
* **Agentic Qualification:** Uses **GPT-4o Reasoning** to score leads against a custom ICP rubric (0-100 score).
* **System Reliability Layer:** Custom logic to catch and parse complex Axios/HTTP 400 errors, ensuring DNS issues never break the execution thread.
* **Hyper-Personalized Sync:** Generates 1:1 outreach drafts based on specific "pain points" and syncs them to Google Sheets.

---

## 🔧 Technical Stack & Tools
* **[n8n.io](https://n8n.io/)**: Core workflow orchestration.
* **[OpenAI GPT-4o](https://openai.com/api/)**: Lead qualification and copywriting engine.
* **[Google Sheets API](https://developers.google.com/workspace/sheets)**: Centralized Lead Database.

---

## 🔌 Extensible API Integration
Modular architecture allowing easy swapping of research APIs:
* **[Firecrawl](https://www.firecrawl.dev/)**: Best-in-class for converting websites to LLM-ready Markdown.
* **[Exa AI](https://exa.ai/)**: Neural search for finding company news and social profiles.
* **[Tavily AI](https://tavily.com/)**: AI-native search built specifically for agents.

---

## 🚀 Business Impact
* **Zero-Downtime:** Automated error recovery saves 5+ hours of manual troubleshooting weekly.
* **Scalable Personalization:** Replaces generic templates with research-backed outreach.
* **Auditable Pipeline:** Every failure is logged with human-readable reasons for easy maintenance.

---

**Developed by SM**
