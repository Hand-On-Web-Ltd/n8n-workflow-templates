# n8n Workflow Templates

A collection of ready-to-import workflow templates for [n8n](https://n8n.io), built for small businesses. Each template handles a common automation task — just import, configure your credentials, and go.

## Workflows

### 1. Lead Capture to CRM
**File:** `workflows/lead-capture-to-crm.json`

Catches new form submissions via webhook and adds them to your CRM. Sends a welcome email to the lead and notifies your sales team on Slack.

**Use case:** Website contact forms, landing pages, Facebook lead ads.

### 2. New Customer Welcome
**File:** `workflows/new-customer-welcome.json`

When a new customer is added to your system, sends a personalised welcome email, creates a task for your team to follow up, and logs the event.

**Use case:** Onboarding new clients, first-purchase follow-up.

### 3. Invoice Reminder
**File:** `workflows/invoice-reminder.json`

Checks for overdue invoices daily and sends polite email reminders. Escalates to your accounts team if unpaid after 14 days.

**Use case:** Freelancers, agencies, any service business with recurring billing.

### 4. Social Media Scheduler
**File:** `workflows/social-media-scheduler.json`

Pulls content from a Google Sheet and posts it to your social media accounts on schedule. Supports multiple platforms.

**Use case:** Batch-creating social content, maintaining consistent posting.

### 5. Google Review Monitor
**File:** `workflows/google-review-monitor.json`

Monitors your Google Business reviews and sends a Slack notification whenever a new review comes in. Flags negative reviews for immediate attention.

**Use case:** Reputation management, responding to reviews quickly.

## How to Import

1. Open your n8n instance
2. Click **Workflows** → **Import from File**
3. Select the JSON file
4. Configure credentials (API keys, SMTP settings, etc.)
5. Activate the workflow

## Customising

Each workflow uses placeholder credentials. You'll need to:
- Set up the relevant n8n credentials (SMTP, Slack, Google Sheets, etc.)
- Update webhook URLs to match your setup
- Adjust timing and filters to your needs

## About Hand On Web
We build AI chatbots, voice agents, and automation tools for businesses.
- 🌐 [handonweb.com](https://www.handonweb.com)
- 📧 outreach@handonweb.com
- 📍 Chester, UK

## Licence
MIT
