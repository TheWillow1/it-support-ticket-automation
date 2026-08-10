# IT Support Ticket Management & Tracking System

An AI-powered IT support automation built with n8n that automatically
processes incoming support requests, classifies issues, assigns
technicians, calculates SLAs, and tracks ticket status.

## Problem

IT support requests are often handled manually.

This can involve:

- Reading incoming emails
- Creating tickets
- Categorizing issues
- Determining priority
- Assigning technicians
- Calculating SLA deadlines
- Sending notifications
- Tracking ticket status

This workflow automates these repetitive processes.

## Workflow

Gmail
↓
Data Processing
↓
AI Classification
↓
SLA Calculation
↓
Airtable Ticket Creation
↓
Technician Assignment
↓
Airtable Update
↓
Slack Notification
↓
Client Email

## Key Features

- Automated ticket creation
- AI-powered issue classification
- Priority and severity determination
- Automated SLA calculation
- Technician assignment based on workload
- Airtable ticket tracking
- Slack notifications
- Automated client communication
- Ticket status management

## Technologies

- n8n
- Airtable
- Gmail
- Slack
- LLM API
- JavaScript
- JSON
- Webhooks
- REST API integrations

## Example Workflow

A client sends an IT support request by email.

The workflow extracts the relevant information, sends it to an
LLM for classification, calculates the appropriate SLA based on
priority, creates a ticket in Airtable, assigns an available
technician, and notifies the relevant parties.

## Security

The workflow included in this repository has been sanitized.

API keys, access tokens, webhook secrets, credentials, and real
client information have been removed or replaced with placeholders.

## Disclaimer

This is a portfolio/project implementation designed to demonstrate
AI automation, workflow orchestration, systems integration, and
business process automation.
