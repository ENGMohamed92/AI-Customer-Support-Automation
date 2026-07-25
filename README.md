# AI Customer Support Automation

An AI-powered customer support automation workflow built with **n8n**, designed to automate customer communication, answer frequently asked questions, classify customers, and streamline appointment booking.

---

## Overview

This project demonstrates how AI can replace repetitive customer support tasks by integrating multiple communication channels and CRM systems into one intelligent workflow.

The solution acts as a virtual receptionist capable of handling customer conversations, routing requests, collecting customer information, and assisting with appointment booking.

---

## Features

- AI-powered customer support
- AI virtual receptionist
- Frequently Asked Questions (FAQ)
- Customer classification
- Appointment booking automation
- CRM integration
- Telegram integration
- Chatwoot integration
- AI Memory
- Human handoff capability
- Workflow routing
- Error handling

---

## Tech Stack

- n8n
- DeepSeek V4 Flash
- Telegram Bot API
- Chatwoot
- Twenty CRM
- Supabase Memory
- HTTP Request
- Webhooks
- JavaScript (Code Node)

---

## Workflow Architecture

```
Telegram

↓

Webhook

↓

Pre-processing

↓

AI Agent

↓

Switch / Router

├── FAQ

├── Appointment Booking

├── Customer Classification

└── Human Agent

↓

Chatwoot

↓

Twenty CRM

↓

Customer Response
```

---

## Workflow Components

### Telegram Trigger

Receives customer messages.

### AI Agent

Processes user requests and generates responses.

### Switch Router

Routes requests based on customer intent.

### Chatwoot Integration

Creates and updates conversations.

### Twenty CRM

Stores customer information.

### AI Memory

Maintains conversational context using Supabase.

---

## Use Cases

- Medical Clinics
- Dental Clinics
- Customer Service Teams
- Small Businesses
- Service Providers

---

## Skills Demonstrated

- Workflow Automation
- AI Agent Integration
- REST APIs
- CRM Integration
- Prompt Engineering
- Customer Support Automation
- Business Process Automation
- Webhook Integration
- Error Handling
- Workflow Design

---

## Future Improvements

- Voice Support
- WhatsApp Integration
- Calendar Integration
- Multi-language Support
- RAG Knowledge Base

---

## Author
Mohamed Khaled
