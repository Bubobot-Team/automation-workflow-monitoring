# n8n-integrate-monitoring

This repository contains example n8n workflows that DevOps teams can use to enhance their monitoring and automation processes. These workflows demonstrate best practices for integrating various monitoring tools and services.

## Available Workflows

- Incident Response - [n8n - Incident Response - 1](./n8n/n8n___Incident_Response___1.json)
  - A workflow that handles incident management by integrating AlertManager with PagerDuty, Notion, and Discord notifications
  - Features:
    - Automatic incident creation in PagerDuty
    - Notion database updates for incident tracking
    - Discord notifications for team awareness
    - Business hours detection for appropriate routing

- AWS Service Management - [n8n - AWS Service Management](./n8n/n8n___AWS_Service_Management.json)
  - A workflow that automates AWS service management through Lambda functions
  - Features:
    - Automatic service restart capabilities
    - Dynamic service scaling based on conditions
    - Integration with AWS Lambda for serverless execution
    - Secure AWS service management through IAM roles

## Contact & Community

- Email us at support@bubobot.com
- Join our Discord community: https://discord.gg/qwSKMu4jYA 