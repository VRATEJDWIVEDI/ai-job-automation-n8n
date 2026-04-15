# 🚀 AI-Powered Job Scraper & Analyzer (n8n)

## 🧠 Overview
This project is an automated job pipeline built using n8n.

It fetches job listings, analyzes them using AI, filters valid results, and stores them in Google Sheets.

## ⚙️ Features
- ⏰ Automated job fetching (SerpAPI)
- 🤖 AI-based job analysis (OpenRouter)
- 📊 Job scoring system (1–10)
- 🧹 Data cleaning using IF node
- 📁 Google Sheets integration

## 🧩 Workflow
API → AI → IF Filter → Google Sheets

## 🔧 Tech Stack
- n8n
- OpenRouter (LLM)
- Google Sheets API
- SerpAPI

## 🐞 Issues Faced & Fixes
- Fixed OpenRouter authentication errors
- Solved Google Sheets 404 issue
- Handled JSON parsing errors
- Fixed inconsistent keys (job_title vs job\_title)
- Added IF node to remove invalid data

## 📸 Screenshots
(Add images here)

## 🚀 How to Use
1. Import `workflow.json` into n8n
2. Add your API keys
3. Run the workflow

## 💡 Note
This project was implemented as part of learning n8n and improved by debugging and optimizing the workflow.
