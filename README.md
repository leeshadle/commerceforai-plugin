# CommerceForAI plugin

[CommerceForAI](https://commerceforai.com) is a commerce API for AI agents: products, stock, Stripe checkout, orders, shipping, returns, print-on-demand and sales tax, on the merchant's own Stripe account. An agent can start with no sign-up: `npx commerceforai init`.

One folder, three agents: a `commerce` skill (how to add a store to an app with CommerceForAI) and the hosted CommerceForAI MCP server (sign in as the store owner).

**Claude Code**

```
/plugin marketplace add https://commerceforai.com/.claude-plugin/marketplace.json
/plugin install commerceforai@commerceforai
```

**Cursor**: reads `.cursor-plugin/plugin.json`, `skills/` and `mcp.json`. To try it locally, copy this folder to `~/.cursor/plugins/local/commerceforai` and reload the window.

**Codex**: reads `plugin.json`, `skills/` and `mcp.json`.

**Any agent that supports skills**: `npx skills add https://commerceforai.com`

Docs: https://commerceforai.com/docs/guides/agents · MIT licensed.
