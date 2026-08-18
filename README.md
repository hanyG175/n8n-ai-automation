# n8n-ai-automation-portfolio

Four production-style AI automation systems built with n8n for the moments when manual work starts piling up and your team just needs relief fast.

| Project | What it does | Tech stack | Link to subfolder |
| --- | --- | --- | --- |
| Competitor Page Watchdog | Checks a competitor product page every hour, compares it to the previous version, and sends a plain-language “what changed” alert. | n8n, HTTP scraping, Google Sheets, Qwen API, Telegram | [competitor-price-monitor](./competitor-price-monitor/) |
| Email Triage Assistant | Watches Gmail, drafts AI replies, routes sensitive messages for approval in Slack, and keeps a log in Sheets. | n8n, Gmail, Google Gemini, Slack, Google Sheets | [email-assistant](./email-assistant/) |
| WhatsApp Support Bot | Handles incoming WhatsApp support chats with AI-generated first responses and supports human takeover when needed. | n8n, WhatsApp API, LLM provider API, Google Sheets | [whatsapp-support-bot](./whatsapp-support-bot/) |
| Document Q&A (RAG) Bot | Answers Telegram questions from your internal docs using vector retrieval so teams stop digging through long files manually. | n8n, Telegram, Pinecone, Google Gemini, OpenRouter, Google Sheets | [document-qa-bot](./document-qa-bot/) |

- **Competitor Page Watchdog — Why this matters:** When you cannot afford to miss a pricing or availability change, this gives you an hourly heads-up without babysitting tabs all day.
- **Email Triage Assistant — Why this matters:** When inbox backlog turns into customer frustration, this cuts response time while still keeping human approval on high-risk replies.
- **WhatsApp Support Bot — Why this matters:** When support pings keep coming after hours, this keeps first-response speed high and consistency intact until an agent steps in.
- **Document Q&A (RAG) Bot — Why this matters:** When answers are buried in dense internal docs, this turns “let me search for that” into instant, grounded responses for the team.