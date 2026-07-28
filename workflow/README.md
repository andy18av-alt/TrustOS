# TrustOS Workflow

This folder contains the primary n8n workflow that powers **TrustOS**, an Enterprise AI-Native Trust & Safety Operating System.

## Contents

- **TrustOS - Autonomous Marketplace Enforcement.json** — Sanitized export of the production workflow.

## Workflow Overview

The workflow orchestrates multiple specialised AI agents to automate enterprise Trust & Safety investigations:

1. Evidence Agent
2. Policy Agent
3. Vision Agent
4. Risk Committee
5. Executive Reporter

Together, these agents analyse evidence, assess policy compliance, evaluate visual counterfeit indicators, produce an explainable enforcement decision, and generate an executive investigation report.

## Security Notice

To protect infrastructure and credentials, the following have been replaced with placeholders:

- API credentials
- Google Sheets IDs
- Webhook URLs
- Credential identifiers

The workflow structure, prompts, orchestration logic, JavaScript, and multi-agent architecture remain unchanged for evaluation.

## Running the Workflow

1. Import the workflow into n8n.
2. Configure your own API credentials.
3. Connect your own Google Sheets (or other data sources).
4. Update the webhook endpoint.
5. Execute an investigation by sending a webhook request.

---

This workflow is provided for demonstration and evaluation purposes as part of the TrustOS hackathon submission.
