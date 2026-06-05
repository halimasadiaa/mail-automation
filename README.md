# 📧 Mail Automation Workflow (n8n)

This project is an automated email follow-up system built in **n8n**, designed to manage leads, track meeting times, generate AI-powered follow-up emails, and send them automatically using Gmail.

---

## 🚀 Overview

The workflow automates the full lifecycle of client meeting follow-ups:

- Reads leads from Google Sheets
- Calculates time remaining until meeting
- Detects expired meetings
- Generates AI-based follow-up emails (1, 2, and 3)
- Sends emails at the correct time intervals
- Marks follow-ups as sent
- Updates lead status in Google Sheets

---

## 🧠 Core Workflow Logic

### 1. Schedule Trigger ⏰
Runs automatically every hour to process all leads.

---

### 2. Load Leads (Google Sheets)
Fetches all rows from:
