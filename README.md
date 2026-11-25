# Yari Infotech Agent Skills & Plugin

[[https://skills.sh/b/yari-infotech/yari-skills]](https://skills.sh/yari-infotech/yari-skills)

Official Agent Skills, `AGENTS.md`, `.cursorrules`, and Agent Plugin (`plugin.json`) repository for [Yari Infotech](https://yariinfotech.com).

## Install via Skills CLI
```bash
npx skills add yari-infotech/yari-skills
```

## Included Skills (5 Capability Areas)
- `services` — Inspect 12 engineering capabilities across Build, Connect, and Grow (`GET /api/v1/services`, MCP `get_services`)
- `estimate` — Estimate timelines, INR/USD tiers, and project scope (`/estimate`, `/pricing.md`, MCP `estimate_project`)
- `case-studies` — Retrieve verified production case studies and metrics (`GET /api/v1/projects`, MCP `get_case_studies`)
- `mcp-integration` — Connect agents to Product MCP (`/mcp`), Docs MCP (`/docs/mcp`), and `npx yariinfotech-mcp`
- `api-sandbox` — Test REST v1 pagination, rate limits, idempotency, and async audits (`/sandbox`, `/api/v1/sandbox`)

## Developer Resources
- API Docs: https://yariinfotech.com/developers
- MCP Server, SDK & CLI: https://yariinfotech.com/mcp-server
- OpenAPI 3.1: https://yariinfotech.com/openapi.json
- LLM Manifest: https://yariinfotech.com/llms.txt
