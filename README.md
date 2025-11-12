# AI-Lead-Qualification-Assistant

# AI Lead Qualification Workflow (n8n + Google Gemini)

This project automates the process of qualifying marketing leads using **n8n** and **Google Gemini**.

## Overview
The workflow receives form submissions via a webhook, analyzes them with Gemini to determine:
- Service type
- Priority level
- Confidence score

It then routes leads:
- High-confidence → Google Sheet (`Qualified Leads`)
- Low-confidence → Google Sheet (`Needs Review`) + email notification

## Tools Used
- n8n (workflow automation)
- Google Gemini (AI classification)
- Google Sheets (data storage)
- Gmail (notifications)

## How It Works
1. Webhook receives new lead data.
2. AI analyzes and classifies the lead.
3. Workflow routes to Sheets and sends notifications.

## Business Value
Reduces manual sorting time, improves consistency, and ensures no lead goes unnoticed.

## Files
- `ai-lead-qualification.json` — full n8n workflow export

## Author
Created by [John Mitchell Diaz] — AI Automation Specialist + UX Designer.

