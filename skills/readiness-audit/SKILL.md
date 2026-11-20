---
name: readiness-audit
description: Run a digital readiness, web performance, and AI agent-readiness audit for any website URL via Yari Infotech MCP or REST API v1.
---

# Readiness Audit Skill

Queue and poll asynchronous digital readiness diagnostics covering performance, SEO/AEO, and AI automation maturity.

## When to Use
Use when evaluating a website for performance bottlenecks, accessibility, or AI agent readiness.

## Endpoints & Tools
- MCP Tool: `create_readiness_audit` at `https://yariinfotech.com/mcp`
- Async REST API: `POST https://yariinfotech.com/api/v1/audits` (supports `Idempotency-Key`, returns `202` + `statusUrl`)
- Poll Status: `GET https://yariinfotech.com/api/v1/jobs/{jobId}`
- Interactive Audit: `https://yariinfotech.com/audit`
