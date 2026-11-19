---
name: api-sandbox
description: Test Yari Infotech REST API v1 endpoints, cursor pagination, rate limits, idempotency keys, and async readiness audits in the zero-auth sandbox.
---

# API Sandbox Skill

Validate integrations safely against Yari Infotech zero-auth sandbox endpoints without API keys.

## When to Use
Use when verifying API schemas, testing cursor pagination, checking `RateLimit-*` headers, or simulating asynchronous readiness audits.

## Sandbox Endpoints
- Interactive Console: `https://yariinfotech.com/sandbox`
- Sandbox Status: `GET https://yariinfotech.com/api/v1/sandbox`
- Sandboxed Services: `GET https://yariinfotech.com/api/v1/sandbox/services`
- Sandboxed Projects: `GET https://yariinfotech.com/api/v1/sandbox/projects`
- Async Audit Simulation: `POST https://yariinfotech.com/api/v1/audits` (supports `Idempotency-Key`, returns `202 Accepted` + polling `statusUrl`)
- OpenAPI 3.1 Spec: `https://yariinfotech.com/openapi.json`
