# AI Email Assistant

## Problem statement
Teams handling growing inbox volume need faster, consistent replies without losing human oversight on sensitive responses.

## Architecture
![n8n canvas placeholder](./assets/image.png)

## Tech stack
![n8n](https://img.shields.io/badge/n8n-Workflow_Automation-EA4B71?logo=n8n&logoColor=white)
![Gmail](https://img.shields.io/badge/Gmail-Email_Trigger_&_Reply-D14836?logo=gmail&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-LLM-4285F4?logo=google&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-Approval_Flow-4A154B?logo=slack&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-Message_Logging-34A853?logo=googlesheets&logoColor=white)

## Setup instructions
1. Import `AI Email Assistant.json` into n8n.
2. Create and connect credentials (use your own values):
   - Gmail OAuth2
   - Google Sheets OAuth2
   - Slack API
3. Configure placeholders in the workflow:
   - `YOUR_SHEET_ID`
   - `YOUR_SHEET_GID`
   - `YOUR_SLACK_CHANNEL_ID`
   - `YOUR_CREDENTIAL_ID`
4. Enable the Gmail trigger and webhook nodes after validating permissions.

## Workflow JSON
[Download workflow JSON](./AI%20Email%20Assistant%20(2).json)

## Demo
![Demo placeholder](./assets/demo.mp4)
