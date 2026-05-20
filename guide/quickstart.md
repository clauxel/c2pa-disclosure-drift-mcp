# Quickstart

C2PA Disclosure Drift is a hosted remote MCP for C2PA disclosure policy MCP.

## Fast Path

1. Open C2PA Disclosure Drift and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://c2padisclosure.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call check_disclosure_policy with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://c2padisclosure.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=c2padisclosure_public_docs&utm_content=quickstart_home
- https://c2padisclosure.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=c2padisclosure_public_docs&utm_content=quickstart_pricing
- https://c2padisclosure.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=c2padisclosure_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://c2padisclosure.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
