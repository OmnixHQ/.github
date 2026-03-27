# Omnix

**Agentic commerce infrastructure. Connect any store to every AI agent.**

Omnix is source-available middleware that plugs Magento, Shopware, and Shopify into AI shopping agents through the [Universal Commerce Protocol (UCP)](https://ucp.dev). No replatforming. No plugins. One integration.

---

## Products

| Repo | Description | Status |
|---|---|---|
| [omnix-gateway](https://github.com/OmnixHQ/omnix-gateway) | Multi-tenant UCP gateway — translates store APIs into UCP | 🟢 Developer preview |
| [omnix-agent](https://github.com/OmnixHQ/omnix-agent) | AI shopping agent with Chat UI and reasoning layer | 🟢 Developer preview |
| [omnix-client](https://github.com/OmnixHQ/omnix-client) | UCP client SDK for building agents and integrations | 🟢 Developer preview |

---

## How it works

```
Magento 2   ╮
Shopware 6  ├──▶  ⚡ Omnix Gateway  ──▶  ChatGPT / Gemini / Custom agents
Shopify     ╯      (UCP protocol)
```

1. **Point your store** — add a single proxy rule to forward AI-agent traffic to Omnix
2. **Omnix translates** — the gateway converts your store's native API into UCP
3. **Agents shop your store** — any UCP-compatible agent can now discover, compare, and buy autonomously

---

## Protocol support

| Protocol | Status |
|---|---|
| UCP (Universal Commerce Protocol) | 🟢 Live |
| ACP (Agent Commerce Protocol) | 🟡 Roadmap |
| AP2 | 🟡 Roadmap |
| MCP server | 🟡 Planned |

---

## License

All Omnix repositories are released under the [Elastic License 2.0 (ELv2)](https://www.elastic.co/licensing/elastic-license) — source-available, self-hostable, no vendor lock-in.

---

## Links

- 🌐 Website: [getomnix.dev](https://getomnix.dev)
- 📧 Contact: [hello@getomnix.dev](mailto:hello@getomnix.dev)
- 🏢 Built by [Momentum Group s. r. o.](https://www.linkedin.com/in/artemiy-karkusha/) · Bratislava, Slovakia
