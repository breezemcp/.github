## Breeze

**The internet access layer for AI agents.**

AI agents need to access the web — but they get blocked by anti-bot systems, rate limits, and geo-restrictions. Breeze routes requests through residential IPs in **248 countries**. No captchas. No blocks. Just data.

### 🚀 Get Started in 30 Seconds

Add to your Claude Desktop, Cursor, or Windsurf config:

```json
{
  "mcpServers": {
    "breeze": {
      "command": "npx",
      "args": ["-y", "breeze-mcp"]
    }
  }
}
```

That's it — **10MB free, no signup required.**

### How It Works

```
Your AI  →  Breeze MCP  →  Residential IP (248 countries)  →  Target Website
```

No code changes. No infrastructure. Just plug in and go.

### 🧰 Features

- 🌍 **Geo Targeting** — Real residential IPs in 248 countries, city & state level
- 🤖 **MCP Native** — Works with Claude, Cursor, Windsurf, any MCP client
- ⚡ **Zero Config** — No API key needed to start, just add and go
- 🔍 **Proxy Search** — Google search without captchas or blocks
- 📦 **Batch Fetch** — Multiple URLs, different IP per request
- 🔐 **Sticky Sessions** — Same IP for multi-step workflows

### 💰 Pricing

| Plan | Requests/day | Price |
|------|-------------|-------|
| Anonymous | 10 | Free |
| Free | 100 | $0 (signup) |
| Pro | 25,000 | $29/mo |
| Business | 150,000 | $99/mo |

### 📦 Repos

- **[breeze-mcp](https://github.com/breezemcp/breeze-mcp)** — MCP Server (public)
- **breeze-gateway** — API Gateway (private)

---

[⭐ Star on GitHub](https://github.com/breezemcp/breeze-mcp) · [Get Started →](https://github.com/breezemcp/breeze-mcp#quick-start) · [breezemcp.xyz](https://breezemcp.xyz)
