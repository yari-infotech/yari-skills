---
name: mcp-integration
description: Connect Claude Desktop, Cursor, or custom AI agents to Yari Infotech Product MCP (/mcp), Docs MCP (/docs/mcp), and the yariinfotech-mcp CLI.
---

# MCP Integration Skill

Configure Streamable HTTP MCP servers or run the official `yariinfotech-mcp` CLI/SDK.

## When to Use
Use when setting up MCP tool access for Yari Infotech services, documentation search, case study verification, or scope estimation.

## Endpoints & CLI
- Product MCP Server: `https://yariinfotech.com/mcp` (tools: `get_services`, `get_case_studies`, `estimate_project`)
- Docs MCP Server: `https://yariinfotech.com/docs/mcp` (tools: `search_docs`, `read_doc_page`; resources: `yari://docs/*`)
- Server Cards: `https://yariinfotech.com/.well-known/mcp/server-cards.json`
- npm CLI / SDK: `npx yariinfotech-mcp services` (https://www.npmjs.com/package/yariinfotech-mcp)
