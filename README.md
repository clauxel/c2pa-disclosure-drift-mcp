# C2PA Disclosure Drift MCP

C2PA disclosure policy MCP with structured receipts.

Paid remote MCP for C2PA disclosure policy MCP, structured receipts, audit logs, and reviewer-ready evidence.

## Public Endpoints

- Website: https://c2padisclosure.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://c2padisclosure.clauxel.com/mcp
- Server card: https://c2padisclosure.clauxel.com/server-card.json
- Registry name: `com.clauxel.c2padisclosure/c2padisclosure-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `check_disclosure_policy`
- `validate_c2pa_status`
- `issue_ai_media_receipt`
- `explain_region_rule`
- `export_disclosure_log`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://c2padisclosure.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://c2padisclosure.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://c2padisclosure.clauxel.com/server-card.json
- MCP endpoint: https://c2padisclosure.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
