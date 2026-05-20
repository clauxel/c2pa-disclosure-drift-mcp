# C2PA Disclosure Drift

C2PA Disclosure Drift is a hosted remote MCP for C2PA disclosure policy MCP.

This repository is a public documentation project for C2PA Disclosure Drift. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://c2padisclosure.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=c2padisclosure_public_docs&utm_content=readme_home
- Pricing: https://c2padisclosure.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=c2padisclosure_public_docs&utm_content=readme_pricing
- Checkout: https://c2padisclosure.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=c2padisclosure_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://c2padisclosure.clauxel.com/mcp
- Server card: https://c2padisclosure.clauxel.com/server-card.json
- Registry name: `com.clauxel.c2padisclosure/c2padisclosure-mcp`
- Tools: `check_disclosure_policy`, `validate_c2pa_status`, `issue_ai_media_receipt`, `explain_region_rule`, `export_disclosure_log`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI governance teams, policy reviewers, trust and safety leads, and compliance operators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: check_disclosure_policy
- MCP tool: validate_c2pa_status
- MCP tool: issue_ai_media_receipt
- MCP tool: explain_region_rule
- MCP tool: export_disclosure_log

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
