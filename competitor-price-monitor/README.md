# AI Competitor Watchdog

## Problem statement
Pricing and market teams need early warning when competitor product pricing or availability changes so they can react before revenue or positioning is impacted.

## Architecture
![n8n canvas placeholder](./assets/architecture-placeholder.png)

> Placeholder: add the exported n8n canvas screenshot here.

## Tech stack
![n8n](https://img.shields.io/badge/n8n-Workflow_Automation-EA4B71?logo=n8n&logoColor=white)
![HTTP](https://img.shields.io/badge/HTTP-Web_Scraping-00599C)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-State_Store_&_History-34A853?logo=googlesheets&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-Alert_Channel-26A5E4?logo=telegram&logoColor=white)
![Qwen API](https://img.shields.io/badge/Qwen-Alert_Summarization-7B61FF)

## Setup instructions
1. Import `AI Competitor Watchdog.json` into n8n.
2. Create and connect credentials (use your own values):
   - Google Sheets OAuth2
   - Telegram Bot API
   - HTTP ****** (for external LLM endpoint)
3. Configure placeholders in the workflow:
   - `YOUR_SHEET_ID`
   - `YOUR_SHEET_GID`
   - `YOUR_TELEGRAM_CHAT_ID`
   - `YOUR_CREDENTIAL_ID`
4. Set your target product URL and schedule interval before enabling the workflow.

## Workflow JSON
[Download workflow JSON](./AI%20Competitor%20Watchdog.json)

## Demo
![Demo placeholder](./assets/demo-placeholder.gif)

> Placeholder: add a short alert-flow demo GIF or video link.
