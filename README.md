<div align="center">

#  AI Instagram Lead Generation Automation

### AI-Powered Instagram Comment & DM Automation built with n8n, OpenRouter AI & Meta Graph API

![n8n](https://img.shields.io/badge/n8n-Automation-orange?style=for-the-badge)
![OpenRouter](https://img.shields.io/badge/OpenRouter-AI-blue?style=for-the-badge)
![Instagram](https://img.shields.io/badge/Instagram-API-E4405F?style=for-the-badge&logo=instagram&logoColor=white)


An intelligent automation workflow that instantly replies to Instagram comments, starts AI-powered conversations in Direct Messages, follows up with potential customers, and helps businesses generate leads 24/7.


</div>

---

#  Project Demo

<div align="center">

<a href="https://drive.google.com/file/d/1oL6y7RUe_wSN4C3rBP1DyQ2A1r86uL37/view?usp=sharing">

<img src="https://img.shields.io/badge/▶%20Watch%20Full%20Demo-red?style=for-the-badge&logo=youtube&logoColor=white" height="60">

</a>

### 👆 Click the button above to watch the complete workflow in action.

</div>

---

#  Overview

This project is a fully automated **Instagram Lead Generation System** built inside **n8n**.

Whenever someone comments on your Instagram post or sends a Direct Message, the workflow automatically responds, engages the user with an AI chatbot, asks follow-up questions, qualifies the lead, and keeps the conversation going naturally.

Think of it as your **24/7 AI Sales Representative** for Instagram.

---

#  Features

-  Instagram Webhook Integration
-  AI-powered Chatbot
-  Automatic Comment Replies
-  Instagram Direct Message Automation
-  OpenRouter AI Integration
-  Lead Qualification
-  Business Inquiry Handling
-  Intelligent Follow-up Conversations
-  Production Ready Workflow
-  Secure Credential Configuration
-  Modular n8n Workflow

---

#  Workflow Architecture

```text
                    Instagram User
                           │
                           ▼
                 Instagram Webhook
                           │
                           ▼
               Webhook Verification
                           │
                           ▼
              Detect Incoming Event
                           │
           ┌───────────────┴───────────────┐
           │                               │
           ▼                               ▼
    Instagram Comment              Instagram DM
           │                               │
           ▼                               ▼
  Auto Public Comment Reply         AI Chatbot
           │                               │
           ▼                               ▼
      Generate AI DM             Generate AI Reply
           │                               │
           └───────────────┬───────────────┘
                           ▼
                Send Instagram Message
                           │
                           ▼
             Continue Customer Conversation
```

---

#  How It Works

## 1️ Receive Webhook

The workflow receives Instagram events from the Meta Graph API.

Supported events include:

- Instagram Comments
- Instagram Direct Messages
- Webhook Verification

---

## 2️ Detect Event Type

The workflow automatically determines whether the event is:

-  Comment
-  Direct Message

and routes the workflow accordingly.

---

## 3️ Auto Reply to Comments

Whenever a user comments on a post, the workflow instantly replies publicly.

Example:

> Thanks for your comment! Check your DM 📩

This increases engagement while moving the conversation into private messages.

---

## 4️ AI Chatbot

Once inside Instagram DM, the AI chatbot takes over.

It can:

- Answer customer questions
- Explain products or services
- Handle pricing inquiries
- Collect customer details
- Qualify potential leads
- Understand buying intent
- Ask intelligent follow-up questions
- Continue conversations naturally

---

## 5️ Response Processing

The workflow cleans every AI response before sending it.

It automatically:

- Removes markdown
- Supports different LLM output formats
- Generates fallback replies
- Limits message length
- Produces Instagram-compatible responses

---

## 6️ Send Instagram Message

The final AI-generated response is delivered back to the user through the Instagram Messaging API.

The conversation continues naturally until the customer is qualified.

---

#  Technologies Used

- n8n
- OpenRouter AI
- Meta Graph API
- Instagram Messaging API
- JavaScript
- HTTP Request Nodes
- AI Chains
- Webhooks

---

#  Requirements

- Latest version of n8n
- Meta Developer Account
- Meta App
- Facebook Page
- Instagram Professional Account
- OpenRouter API Key

---

#  Required Configuration

Replace the placeholders below after importing the workflow.

```text
YOUR_PAGE_ACCESS_TOKEN

YOUR_INSTAGRAM_ACCESS_TOKEN

YOUR_VERIFY_TOKEN

YOUR_PAGE_ID

YOUR_WEBHOOK_ID
```

---

#  Recommended Environment Variables

```text
META_PAGE_ACCESS_TOKEN

META_VERIFY_TOKEN

META_PAGE_ID

INSTAGRAM_ACCESS_TOKEN

OPENROUTER_API_KEY
```

---

#  Installation

Clone the repository

```bash
git clone https://github.com/kashakmodii/Instagram-Automation.git
```

Then:

1. Import the workflow into **n8n**
2. Configure your credentials
3. Replace placeholder values
4. Activate the workflow
5. Configure your Meta Webhook
6. Start receiving Instagram comments and DMs automatically

---

#  Webhook Example

```text
https://your-domain.com/webhook/instagram-webhook
```

Verification Token

```text
YOUR_VERIFY_TOKEN
```

---

#  Security

This repository **does not include**:

- API Keys
- Access Tokens
- Credentials
- Workflow IDs
- Secrets

Configure these after importing the workflow.

---

#  Use Cases

- Digital Marketing Agencies
- SaaS Companies
- E-commerce Stores
- Real Estate
- Coaches
- Consultants
- Local Businesses
- Educational Platforms
- Customer Support Teams

---


</div>
