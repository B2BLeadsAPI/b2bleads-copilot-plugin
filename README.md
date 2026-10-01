# B2BLeads Copilot Plugin

Agent Plugins 1.0 marketplace + plugin for [GitHub Copilot](https://github.com/features/copilot) (CLI, VS Code, Copilot app). Adds B2B lead search — business name, address, phone, website, rating, and (on paid plans) email — filtered by industry, city, radius, rating, and price level.

## Install

```bash
copilot plugin marketplace add B2BLeadsAPI/b2bleads-copilot-plugin
copilot plugin install b2bleads
```

The plugin connects to B2BLeads' remote MCP server (`https://api.b2bleadsapi.com/mcp`). On first use you'll be prompted to sign in with a B2BLeads account (or create a free trial) via OAuth — no manual API key needed.

## Tools

- `search_leads` — find business leads by industry, location, and company size
- `search_leads_advanced` — ⚠️ elevated cost (9x quota): exhaustively cover a whole city, up to ~180 results
- `list_industries` — list supported industry values
- `list_saved_lists` — list this account's saved lead lists
- `get_saved_list` — get the leads saved in a specific list
- `find_email` — look up a best-effort contact email for a single business website (Business/Premium plan required)

## Links

- [b2bleadsapi.com](https://b2bleadsapi.com/)
- [Support](https://b2bleadsapi.com/support)
