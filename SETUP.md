# Setup Guide

## 1. Import the Workflow
Import `workflow.json` into n8n.

## 2. Groq Setup
Create a free Groq API key from console.groq.com.

Use it in the HTTP Request node for:
- lead enrichment
- pain point identification
- lead scoring
- personalized outreach generation

Recommended model:
- `llama-3.3-70b-versatile`

## 3. Airtable Setup
Create a base named **Sales CRM**.

Create a table named **Leads** with these fields:
- Name
- Email
- Company
- Role
- Score
- Summary
- PainPoint
- EmailSent
- CreatedAt

Connect Airtable credentials in n8n.

## 4. Gmail Setup
Connect Gmail in n8n using OAuth2.

Used for:
- personalized outreach emails to hot and warm leads

## 5. Slack Setup
Connect Slack in n8n.

Used for:
- alerts for cold leads or manual review leads

Recommended channel:
- `sales-alerts`

## 6. Webhook Setup
Copy the webhook URL from the n8n workflow and connect it to your lead form.

Typical fields expected:
- name
- email
- company
- role
- message (optional)

## 7. Activate Workflow
Once credentials are connected:
- activate the workflow
- test with a sample lead form submission

## 8. Expected Flow
- lead form submitted
- webhook receives lead
- Groq enriches and scores lead
- CRM entry created in Airtable
- hot/warm leads get personalized outreach
- cold leads trigger Slack alert

## 9. Notes
This project is designed as a portfolio-ready automation workflow and may require reconnecting credentials if imported into another n8n environment.
