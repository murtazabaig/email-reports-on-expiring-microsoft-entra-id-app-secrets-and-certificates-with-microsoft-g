

![n8n](https://img.shields.io/badge/n8n-workflow-0EA5E9)
![license](https://img.shields.io/badge/license-MIT-green)
![status](https://img.shields.io/badge/status-ready-brightgreen)

# Email reports on expiring Microsoft Entra ID app secrets and certificates with Microsoft Graph

Advanced n8n automation for Email reports on expiring Microsoft Entra ID app secrets and certificates with Microsoft Graph.

## Overview
- Category: DevOps
- Complexity: advanced
- Source: n8n workflow template export

## What This Automation Does
Automate Entra ID secret/cert expiry monitoringscan all apps, filter by N days, and email a formatted HTML report to prevent outages.

## Included Files
- `workflow.json`

## Setup
1. Import `workflow.json` into n8n.
2. Configure required credentials for the services used in the workflow nodes.
3. Update any environment variables or static values inside nodes (API keys, URLs, IDs).
4. Run a test execution and then activate the workflow.

## Tech Stack

- `n8n-nodes-base.aggregate`
- `n8n-nodes-base.emailSend`
- `n8n-nodes-base.filter`
- `n8n-nodes-base.html`
- `n8n-nodes-base.httpRequest`
- `n8n-nodes-base.if`
- `n8n-nodes-base.manualTrigger`
- `n8n-nodes-base.merge`
- `n8n-nodes-base.noOp`
- `n8n-nodes-base.set`
- `n8n-nodes-base.splitOut`
- `n8n-nodes-base.stickyNote`

## Author

Murtaza Baig

## License
MIT License. See `LICENSE`.