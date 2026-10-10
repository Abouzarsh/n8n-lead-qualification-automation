# Automation & AI Engineering Portfolio

**Aboozar Shabnani** · Software engineer (M.Sc. in Software Engineering) · Background in IT and technical management

I build and document practical workflows and software systems across **n8n automation, Python/FastAPI, API integrations, and retrieval-augmented generation (RAG)**. This page is a short guide for potential clients reviewing my public code.

> **Looking for a collaborator?** I am interested in remote, project-based work involving workflow automation, internal tools, AI assistants, and integrations. Project requirements, availability, security obligations, and payment terms should be agreed before work starts.

## Selected work

| Project | Business use case | What you can inspect |
| --- | --- | --- |
| **[AI Lead Qualification & Follow-Up Automation](https://github.com/Abouzarsh/n8n-lead-qualification-automation)** | Capture incoming leads, score them with transparent rules, store records, and route follow-ups | **[Importable n8n workflow JSON](AI-Lead-Qualification-Public-Template.json)**, [project cover](AI-Lead-Qualification-Portfolio-Cover.png), setup instructions and acceptance-test scenarios |
| **[AI Pet Sales Advisor](https://github.com/Abouzarsh/ai-pet-sales-advisor)** | Route purchase inquiries and product recommendations while answering knowledge-based questions | [Chat screenshot](https://github.com/Abouzarsh/ai-pet-sales-advisor/blob/main/assets/screenshots/chat-ui.png), [product screenshot](https://github.com/Abouzarsh/ai-pet-sales-advisor/blob/main/assets/screenshots/product-card.png), [n8n workflow exports](https://github.com/Abouzarsh/ai-pet-sales-advisor/tree/main/workflows) |
| **[InsightRAG AI Copilot](https://github.com/Abouzarsh/insightrag-ai-copilot)** | Query internal documents using a local language model, semantic search, and controlled agent tools | [Architecture and setup](https://github.com/Abouzarsh/insightrag-ai-copilot#architecture), [dashboard screenshot](https://github.com/Abouzarsh/insightrag-ai-copilot/blob/main/docs/screenshots/dashboard.png), [agent screenshot](https://github.com/Abouzarsh/insightrag-ai-copilot/blob/main/docs/screenshots/agent.png) |
| **[Daaneshyar RAG](https://github.com/Abouzarsh/daaneshyar-rag)** | Search Persian/English document collections and inspect citations behind answers | [Chat screenshot](https://github.com/Abouzarsh/daaneshyar-rag/blob/main/docs/screenshots/chat.png), [architecture](https://github.com/Abouzarsh/daaneshyar-rag/blob/main/docs/architecture.md), [demo guide](https://github.com/Abouzarsh/daaneshyar-rag/blob/main/docs/demo-guide-fa.md) |

## How I approach client work

1. **Clarify the business workflow.** Define the trigger, input data, expected outputs, edge cases, and success criteria.
2. **Design with integrations in mind.** Identify APIs, authentication, error handling, and any human approval steps.
3. **Deliver an inspectable implementation.** Provide readable code or n8n workflow exports, configuration instructions, and representative test scenarios.
4. **Prepare for operational use.** Discuss monitoring, retries, access control, secrets, privacy, and maintenance requirements **before** deployment.

## Example service areas

- **n8n automation:** lead processing, data synchronization, CRM integration, notifications, and approvals.
- **Python / FastAPI:** custom APIs, service integrations, processing jobs, and automation backends.
- **RAG and AI assistants:** document indexing, semantic retrieval, source-aware answers, and local LLM integrations.
- **Workflow modernization:** replace repetitive manual steps with testable, traceable processes.

## What these repositories do—and do not—prove

These repositories are **portfolio implementations** with code, examples, screenshots, and setup documentation. They demonstrate engineering approaches; they are **not** a claim that every integration is running as a hosted public demo or that every project has undergone independent production/security certification.

Some systems require you to supply your own API keys, Telegram bot, SMTP account, data tables, database, or locally running models. Read each repository's setup instructions before trying it.

For a client engagement, data protection, service limits, deployment environment, monitoring, and handover requirements must be defined for that client rather than inferred from the demos.

---

**Source and contact:** [GitHub profile — Abouzarsh](https://github.com/Abouzarsh)

*This portfolio index is maintained in the lead-qualification repository. Each linked repository is the source of truth for its own implementation and requirements.*
