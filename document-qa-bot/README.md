# Document Q&A Bot (RAG on Telegram)

## Problem statement
Support and operations teams lose time manually searching long internal documents to answer repetitive questions quickly and accurately.

## Architecture
![n8n canvas placeholder](./assets/architecture-placeholder.png)

## Tech stack
![n8n](https://img.shields.io/badge/n8n-Workflow_Automation-EA4B71?logo=n8n&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-Chat_Interface-26A5E4?logo=telegram&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-Vector_DB-0E76FD)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-Embeddings-4285F4?logo=google&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-LLM_Routing-111111)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-Session_Log-34A853?logo=googlesheets&logoColor=white)

## Setup instructions
1. Import `Document Q&A Bot (RAG on Telegram).json` into n8n.
2. Create and connect credentials (use your own values):
   - Telegram Bot API
   - Pinecone API
   - Google Gemini API
   - OpenRouter API
   - Google Sheets OAuth2
3. Configure placeholders in the workflow:
   - `YOUR_SHEET_ID`
   - `YOUR_SHEET_GID`
   - `YOUR_CREDENTIAL_ID`
4. Point Pinecone settings to your own index and namespace.

## Workflow JSON
[Download workflow JSON](./Document%20Q%26A%20Bot%20(RAG%20on%20Telegram).json)

## Demo
![Demo placeholder](./assets/demo-placeholder.gif)
