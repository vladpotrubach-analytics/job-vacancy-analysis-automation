# AI Job Vacancy Analysis Automation

## Overview

This project automates the collection and analysis of job vacancies using AI.

The workflow collects vacancies, removes duplicates, compares them with previously processed records, analyzes requirements using OpenAI, assigns a relevance score, and stores results in Google Sheets.

---

## Tools Used

- n8n
- Docker
- OpenAI API
- Google Sheets API
- JavaScript
- HTTP Requests

---

## Workflow

1. Collect job vacancies from an online source
2. Parse and clean raw data
3. Remove duplicate records
4. Compare vacancies with existing entries
5. Analyze job descriptions using OpenAI
6. Assign relevance score and recommendation
7. Store results in Google Sheets

---

## Output

Each vacancy receives:

- Relevance score (1–5)
- Recommendation (Apply / Maybe / Skip)
- AI-generated explanation
- Salary information
- Contract type
- Location

---

## Screenshots

### Workflow Overview

![Workflow Overview](Screenshots/workflow-overview.png)

### OpenAI Analysis Workflow

![OpenAI Analysis](Screenshots/openai-analysis-workflow.png)

### Deduplication Process

![Deduplication](Screenshots/deduplication-process.png)

### Results in Google Sheets

![Results](Screenshots/google-sheet-results.png)

---

## Skills Demonstrated

- Workflow Automation
- Data Processing
- API Integration
- AI-Powered Analysis
- Google Sheets Automation
- JavaScript Scripting
- Docker Deployment
