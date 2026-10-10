# 🌐 DomainForge MCP

[![MCP](https://img.shields.io/badge/MCP-Live%20Tools-7c3aed)](https://domainforge-api.agentweb-hub.workers.dev/mcp) [![Smithery](https://img.shields.io/badge/Smithery-100%2F100-16a34a)](https://smithery.ai/server/tofan96you/domainforge-mcp)

## Buy domains with evidence, not vibes

ChatGPT can give an opinion about a domain. **DomainForge queries the live internet**: RDAP registration and expiry, DNS infrastructure, Internet Archive history, and Certificate Transparency logs. It turns those independent signals into a transparent acquisition-risk screen before you spend money on a domain.

## Live tools

| Tool | What it does |
|---|---|
| `domain.architect` | Creates a due-diligence plan for a target domain |
| `domain.profile_live` | Live RDAP registration, expiry, registrar, status and nameservers |
| `dns.inspect_live` | Live A, AAAA, MX, NS and TXT/email-auth signals |
| `history.analyze_live` | Live Internet Archive captures and historical presence |
| `certificates.discover_live` | Live Certificate Transparency subdomain discovery |
| `domain.score_live` | Combines live evidence into a transparent 0–100 screening score |

## Quick start

```json
{
  "mcpServers": {
    "domainforge": {
      "url": "https://domainforge-api.agentweb-hub.workers.dev/mcp"
    }
  }
}
```

No API key required. Start free — 10 requests/day, no signup, no card.

## Pricing

**Gumroad:** $7.99 single-server lifetime access or $14.99 all-access suite: https://amygraphics.gumroad.com/l/mcp-pro

**Solana USDC:** send payment to the wallet below, then use the transaction signature for verification.

```text
8sDLX3okSV974wdjdeKhN9uWLZDr45DeGCJ28zgTLEdJ
```

## Important limitation

This is an automated screening layer, not legal, trademark, backlink, traffic, or financial advice. Always manually verify transferability, trademark conflicts, backlink quality, traffic analytics, and seller ownership before purchase.

## Links

- MCP endpoint: https://domainforge-api.agentweb-hub.workers.dev/mcp
- AgentWeb MCP Hub: https://mcp-hub.agentweb-hub.workers.dev
- Smithery: https://smithery.ai/server/tofan96you/domainforge-mcp
