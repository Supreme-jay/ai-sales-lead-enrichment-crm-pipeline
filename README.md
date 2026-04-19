# AI Sales Lead Enrichment & CRM Pipeline
### Built with n8n + Groq (Free AI) | Turns form submissions into qualified leads in 10 seconds

![workflow](screenshots/workflow.png)

## Project Summary
The AI Sales Lead Enrichment & CRM Pipeline is an automation project built with n8n and Groq AI to turn lead form submissions into enriched, scored, and actionable sales opportunities in seconds. It automates lead intake, AI-based research, pain point identification, lead scoring, personalized outreach generation, CRM storage, and internal sales alerts.

This project demonstrates practical workflow automation, AI-assisted sales operations, CRM pipeline design, and multi-app orchestration using free tools. It is designed as a portfolio-ready automation project for real-world sales and operations teams.

## The Problem
Sales reps spend 3–4 hours per day manually researching leads, qualifying prospects, writing outreach emails, and updating CRM records. This workflow reduces that process to about 10 seconds at zero tool cost.

## What This Does
- Webhook receives lead form submission
- Groq AI researches the company and identifies likely pain points
- Scores the lead as hot, warm, or cold
- Writes a personalized outreach email for the lead’s specific role
- Hot and warm leads receive automated email outreach
- Cold leads are flagged in Slack for manual review
- All leads are saved to Airtable CRM with enrichment data

## Workflow Overview
This workflow starts when a lead submits a form connected to an n8n webhook. The workflow sends the lead details to Groq AI for enrichment, scoring, pain point identification, and email generation. Based on the classification result, leads are either contacted automatically or flagged for internal review. All processed lead data is then stored in Airtable for CRM tracking.

## Files Included
- `workflow.json` — n8n workflow export
- `screenshots/workflow.png` — project visual
- `SETUP.md` — setup instructions

## Tech Stack

| Tool | Purpose | Cost |
|------|---------|------|
| n8n | Workflow automation | Free |
| Groq (Llama 3.3 70B) | Research, scoring, email generation | 100% Free |
| Webhook | Lead intake | Built into n8n |
| Airtable | CRM database | Free |
| Gmail | Outreach emails | Free |
| Slack | Sales team alerts | Free |

## Key Features
- Lead capture through webhook
- AI-powered lead enrichment
- Role-based pain point identification
- Automated lead scoring
- Personalized outreach email generation
- Automatic Gmail outreach for qualified leads
- Slack alerts for leads needing manual review
- Airtable CRM storage for all processed leads

## Use Case
This project is ideal for:
- sales teams
- founders
- agencies
- business development teams
- AI automation engineer portfolios
- CRM workflow automation use cases

## Built By
**Ifeanyi Nwadike**  
Open to AI Automation Engineer, Python Developer, Backend Developer, and Workflow Automation roles.

- LinkedIn: https://www.linkedin.com/in/ifeanyi-nwadike-aab752356
- GitHub: https://github.com/Supreme-jay
