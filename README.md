# Automation

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white)
![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)
![Webhooks](https://img.shields.io/badge/Webhooks-6E56CF?style=for-the-badge&logo=webhook&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white)

Hands-on learning repo for building no-code AI agents, automations, and voice agents using **n8n**, built while preparing for a B2B integration & automation-focused internship at Systems Limited (PartnerLinQ).

This repo documents workflows, notes, and projects completed while working through *n8n — AI Agents, AI Automations & AI Voice Agents (No-code!)*.

---

## Why this repo exists

PartnerLinQ automates B2B/EDI workflows using AI agents for partner onboarding, transaction monitoring, and exception handling. This repo is my hands-on sandbox for understanding that same class of problem — trigger-based workflows, agentic decision-making, and API/webhook orchestration — using n8n as the practical, fastest path to building that intuition.

---

## What's covered

### Fundamentals
- Core building blocks of n8n: nodes, triggers, APIs, webhooks, data handling, workflow testing
- Understanding the differences between automation, AI automation, AI agents, AI assistants, RAG, and multi-agent systems — and when to use each
- How LLMs work (ChatGPT, DeepSeek, Claude, Gemini, Mistral) and how to connect any of them to n8n
- Prompt engineering basics for guiding agent behavior
- What APIs are and how to integrate them into automations

### AI Agents & Automation
- Building AI agents that talk, reply to emails, and perform automated actions
- Mastering the AI agent node in n8n — from basic chat to multi-agent orchestration
- Building a first team of AI agents that collaborate and share memory across tasks and tools
- Automating business processes using agentic workflows
- Making agents more reliable using the "Think" node

### RAG & Knowledge Bases
- Setting up Retrieval-Augmented Generation (RAG) agents using vector databases in n8n
- Setting up metadata, chunking, and embedding models
- Using Pinecone and Supabase to create dynamic, searchable knowledge bases
- Building AI assistants with long-term memory using Supabase

### Integrations
- Connecting OpenAI, Retell AI, Eleven Labs, WhatsApp, Telegram, Google, and more to n8n
- Building a smart Gmail manager/classifier from scratch
- Building a DeepSeek R1 WhatsApp AI agent for planning and research
- Automating appointment booking using AI voice agents

### Voice Agents
- Building a business-ready receptionist AI voice agent (adaptable to any industry) with n8n & Retell AI
- Building fully automated voice agents that make and answer calls
- Using pre-built AI voice agents (VAPI, Eleven Labs, Retell AI)

### Applied Projects
- Fully automated client onboarding system
- Invoice extractor AI agent
- Lead generation agent using Apollo
- Multichannel RAG agent with Pinecone
- Team of email AI agents

---

## Tech stack

| Category | Tools |
|---|---|
| Orchestration | n8n (self-hosted) |
| LLMs | OpenAI, DeepSeek, Claude, Gemini, Mistral, OpenRouter, Grok |
| Voice | Retell AI, VAPI, Eleven Labs |
| Vector DB | Pinecone, Supabase |
| Messaging | WhatsApp, Telegram, Gmail |
| Protocol | MCP (Model Context Protocol) |

---

## Repo structure

```
automation/
├── workflows/          # Exported n8n workflow JSON files
├── notes/               # Concept notes per module
├── projects/            # Applied end-to-end builds
│   ├── receptionist-voice-agent/
│   ├── gmail-classifier/
│   ├── invoice-extractor/
│   └── onboarding-system/
└── README.md
```

---

## Progress

- [ ] Fundamentals & core n8n concepts
- [ ] First AI agent build
- [ ] RAG agent with vector database
- [ ] Multi-agent orchestration
- [ ] Voice agent (Retell AI)
- [ ] Applied project: automated onboarding system

---

## Notes

This repo is exploratory and workflow-first — the goal is applied intuition for agentic + workflow automation patterns relevant to B2B integration platforms, not production deployment.
