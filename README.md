# Sojo for Cursor

Make games that play inside posts on X. Create, deploy and run them from chat, then get paid.

- **MCP server:** `https://sojo.gg/mcp`. The first call opens sojo.gg so you can click Allow once. Sojo reads only your X name, handle and picture, and never posts.
- **Skill:** `sojo`, which points your agent at the rules and the integration docs.

## Add it by hand

Put this in `.cursor/mcp.json` (one project) or `~/.cursor/mcp.json` (every project):

```json
{
  "mcpServers": {
    "sojo": { "url": "https://sojo.gg/mcp" }
  }
}
```

## Docs

- Start here: https://sojo.gg/agents.txt
- Integration: https://sojo.gg/docs/integrate.md
- Hosting: https://sojo.gg/docs/hosting.md
