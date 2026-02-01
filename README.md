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
- `metadata.json`

## Setup
1. Import `workflow.json` into n8n.
2. Configure required credentials for the services used in the workflow nodes.
3. Update any environment variables or static values inside nodes (API keys, URLs, IDs).
4. Run a test execution and then activate the workflow.

## License
MIT License. See `LICENSE`.
