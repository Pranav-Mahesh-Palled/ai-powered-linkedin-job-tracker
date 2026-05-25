# AI-Powered LinkedIn Job Tracker

An intelligent automation workflow built using :contentReference[oaicite:0]{index=0} and :contentReference[oaicite:1]{index=1} Gemini AI that automatically tracks LinkedIn job postings, extracts technical skills, generates personalized cover letters, and stores structured application data in Google Sheets.

---

## Overview

This project automates the job application tracking process by integrating:

- LinkedIn Job RSS Feeds
- Gemini AI for NLP & skill extraction
- AI-generated personalized cover letters
- Google Sheets for structured storage
- n8n workflow automation

The workflow continuously monitors job postings and intelligently processes each listing using Generative AI.

---

## Features

- Automated LinkedIn job monitoring
- RSS-based job fetching
- AI-powered technical skill extraction
- Personalized cover letter generation
- Google Sheets integration
- Fully automated workflow execution
- Structured job application tracking
- Prompt engineering using Gemini AI

---

## Workflow Architecture

```text
Schedule Trigger
       ↓
LinkedIn RSS Feed
       ↓
Extract Job Details
       ↓
Gemini AI Analysis
       ↓
Skill Extraction
       ↓
Cover Letter Generation
       ↓
Google Sheets Storage
```

---

## Tech Stack

| Technology | Purpose |
|---|---|
| n8n | Workflow automation |
| Google Gemini AI | NLP & content generation |
| Google Sheets API | Data storage |
| RSS Feed | LinkedIn job fetching |
| Prompt Engineering | AI response optimization |

---

## Project Structure

```text
ai-powered-linkedin-job-tracker/
│
├── README.md
│
├── workflow/
│   └── LinkedIn-Job-Tracker.json
│
└── demo/
    └── Screencast-LinkedIn-Job-Tracker.mp4
```

---

## How It Works

### 1. Schedule Trigger
The workflow runs automatically at scheduled intervals.

### 2. RSS Feed Fetching
LinkedIn job postings are fetched using RSS feeds.

### 3. AI Skill Extraction
Gemini AI analyzes the job description and extracts:
- Required skills
- Technologies
- Keywords
- Role expectations

### 4. Cover Letter Generation
The AI generates a personalized cover letter tailored to:
- Job role
- Skills required
- Candidate profile

### 5. Google Sheets Storage
All processed data is stored automatically in Google Sheets for tracking.

---

## Import Workflow into n8n

### Step 1
Download the workflow JSON file:

```text
workflow/LinkedIn-Job-Tracker.json
```

### Step 2
Open n8n.

### Step 3
Import the workflow JSON.

### Step 4
Configure:
- Gemini API credentials
- Google Sheets credentials
- RSS feed URL
- Spreadsheet ID

### Step 5
Run the workflow.

---

## Demo

A complete screencast demonstration is available in:

```text
demo/Screencast-LinkedIn-Job-Tracker.mp4
```

---

## Sample Use Cases

- Internship tracking
- Job application management
- Resume personalization
- Automated cover letter generation
- AI-powered career workflow automation

---

## Security Note

Sensitive credentials and IDs have been removed from the public workflow file.

Before deployment, configure your own:
- Gemini API credentials
- Google Sheets credentials
- Spreadsheet IDs

---

## Future Improvements

- Resume matching score
- AI-based job ranking
- Email notifications
- Multi-platform job support
- ATS optimization analysis
- Vector database integration

---

## Skills Demonstrated

- Workflow Automation
- Generative AI Integration
- Prompt Engineering
- API Integration
- Data Processing
- Automation Design
- AI-based Content Generation

---

## Author

**Pranav Mahesh Palled**

Computer Science Engineering Student  
Focused on AI, Automation, and Intelligent Systems

---

## License

This project is licensed under the MIT License.

---

## Repository Topics

```text
n8n
automation
generative-ai
gemini-ai
workflow-automation
google-sheets
linkedin
job-tracker
prompt-engineering
ai-project
```
