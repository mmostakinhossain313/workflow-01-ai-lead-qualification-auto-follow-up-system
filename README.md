# AI Lead Qualification & Auto Follow-Up System

## Overview

I built this workflow to solve a common problem that many businesses face.

When a new lead submits a form, there is often a delay before someone reviews the information, follows up, or takes action. In some cases, leads are forgotten completely.

This workflow helps automate that process from start to finish.

A new lead is captured, stored, reviewed by AI, sent to Telegram for instant visibility, and followed up automatically through email.

The main objective of this project is simple:

**No Lead Should Be Lost.**

## The Problem

Many small businesses and freelancers receive inquiries every day but do not have a structured lead management process.

Common challenges include:

* Slow response times
* Missed follow-ups
* Unorganized lead information
* Lost sales opportunities

## The Solution

This workflow creates an automated lead handling process.

Whenever a new lead is submitted:

1. The lead is stored in Google Sheets
2. AI reviews the lead information
3. A Telegram notification is sent instantly
4. A follow-up email is sent automatically

This allows the business owner to respond faster and stay organized without additional manual work.

## Business Value

* Faster lead response
* Better lead organization
* Less manual work
* Improved customer experience
* More opportunities to convert leads into customers

## Tools Used

* n8n
* Google Forms
* Google Sheets
* OpenAI
* Telegram
* Gmail

## Workflow Diagram

```text
Google Form
    │
    ▼
Google Sheets
    │
    ▼
Google Sheets Trigger
    │
    ▼
AI Lead Analysis
    │
    ▼
Telegram Notification
    │
    ▼
Gmail Follow-Up
```

## How It Works

A potential customer fills out a form on the website.

The lead information is automatically stored in Google Sheets, which triggers the automation workflow.

The workflow reviews the lead details, creates a quick AI-generated summary, sends an instant Telegram notification to the business owner, and automatically sends a follow-up email to the lead.

This process helps businesses respond faster, stay organized, and reduce the chances of losing potential customers.
