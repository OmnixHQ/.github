# Omnix

**Connect any store to every AI agent.**

Omnix is source-available middleware that connects Magento, Shopware, and Shopify to AI shopping agents through the [Universal Commerce Protocol (UCP)](https://ucp.dev). No replatforming. No plugins. One integration.

---

## Repositories

| Repo | Package | What it does |
|---|---|---|
| [omnix-gateway](https://github.com/OmnixHQ/omnix-gateway) | `@omnix/gateway` | Multi-tenant UCP gateway — translates store APIs into UCP for AI agents |
| [ucp-agent](https://github.com/OmnixHQ/ucp-agent) | `@omnix/agent` | AI shopping agent — Chat UI, AI Brain, tool execution over UCP |
| [ucp-client](https://github.com/OmnixHQ/ucp-client) | `@omnix/client` | UCP client SDK — drop-in library for building UCP-compatible agents |

> Repos `ucp-agent` and `ucp-client` are being renamed to `omnix-agent` and `omnix-client` as part of the Omnix rebrand.

---

## How it works

```
Magento 2   ╮
Shopware 6  ├──▶  ⚡ Omnix Gateway  ──▶  ChatGPT / Gemini / Custom agents
Shopify     ╯      (UCP protocol)
```

1. **Point your store** — add a single proxy rule to forward AI-agent traffic to Omnix
2. **Omnix translates** — the gateway converts your store's native API into UCP
3. **Agents shop your store** — any UCP-compatible agent can discover, compare, and buy autonomously

---

## Stack

Node.js 22 · TypeScript · Fastify · Redis · PostgreSQL · Docker · Next.js (agent UI)

---

## Protocol support

| Protocol | Status |
|---|---|
| UCP — Universal Commerce Protocol | 🟢 Live |
| ACP — Agent Commerce Protocol | 🟡 Roadmap |
| AP2 | 🟡 Roadmap |
| MCP server | 🟡 Planned |

---

## License

All Omnix repositories are released under the [Elastic License 2.0 (ELv2)](https://www.elastic.co/licensing/elastic-license) — source-available, self-hostable, no vendor lock-in.

---

## Links

🌐 [getomnix.dev](https://getomnix.dev) · 📧 [hello@getomnix.dev](mailto:hello@getomnix.dev) · 🏢 Momentum Group s. r. o. · Bratislava, Slovakia
