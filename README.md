# Email Automation (AI Reply Assistant - n8n Workflow)

This is an automated email assistant built using n8n.  
It reads unread emails, generates professional AI replies, stores them, and marks emails as read.

---

## Features

- Fetches unread emails from Gmail
- Extracts email content and sender details
- Uses AI (OpenAI GPT model) to draft replies
- Stores email data and AI reply in Airtable
- Marks processed emails as read automatically

---

## Workflow Overview

1. Schedule trigger runs every 2 hours
2. Fetch unread emails from Gmail
3. Extract full email details
4. AI generates a professional reply
5. Store email + reply in Airtable
6. Mark email as read in Gmail

---

## Tools Used

- n8n
- Gmail API
- OpenAI (GPT model)
- Airtable
- Schedule Trigger

---

## Use Case

This workflow can be used for:
- Email automation assistant
- Inbox management system
- AI-powered email reply drafting
- Productivity automation tool

---

## Setup

1. Import workflow into n8n
2. Connect Gmail, OpenAI, and Airtable credentials
3. Activate the workflow
4. Let it run automatically every 2 hours

---

