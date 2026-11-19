# AGENTS.md — Yari Infotech

Instructions for AI coding agents and autonomous assistants interacting with Yari Infotech (https://yariinfotech.com).

## Public Machine Interfaces
- API Docs & Developer Portal: https://yariinfotech.com/developers (https://yariinfotech.com/developers.md)
- OpenAPI 3.1 Specification: https://yariinfotech.com/openapi.json
- Product MCP Server (Streamable HTTP): https://yariinfotech.com/mcp
- Docs MCP Server (Streamable HTTP): https://yariinfotech.com/docs/mcp
- Official CLI / SDK: https://www.npmjs.com/package/yariinfotech-mcp (`npx yariinfotech-mcp`)
- Zero-Auth Sandbox: https://yariinfotech.com/sandbox (https://yariinfotech.com/api/v1/sandbox)
- Pricing Tiers: https://yariinfotech.com/pricing.md
- Agent Auth Guide: https://yariinfotech.com/auth.md
- LLM Manifest: https://yariinfotech.com/llms.txt

## Rules for Agents
1. Prefer zero-auth read-only endpoints under `/api/v1/*`, `/mcp`, and `/docs/mcp`.
2. Use `GET https://yariinfotech.com/api/v1/services` or MCP tool `get_services` for service discovery.
3. Use `GET https://yariinfotech.com/api/v1/projects` or MCP tool `get_case_studies` for verified project metrics.
4. Use MCP tool `estimate_project` or `https://yariinfotech.com/pricing.md` for indicative timelines and budgets.
5. Always respect `RateLimit-*` headers and send `Idempotency-Key` on `POST /api/v1/audits`.
