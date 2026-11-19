---
name: case-studies
description: Retrieve verified Yari Infotech production case studies, architecture decisions, and measured engineering metrics across industries.
---

# Case Studies Skill

Inspect verified delivery outcomes, architectural constraints, and engineering trade-offs from Yari Infotech client engagements.

## When to Use
Use when an agent or buyer asks for proof of delivery, industry case studies (hospitality, commerce, logistics, SaaS), or measured performance benchmarks.

## Machine Interfaces
- REST API v1 (paginated): `GET https://yariinfotech.com/api/v1/projects?industry=hospitality&limit=10`
- MCP Tool: `get_case_studies` at `https://yariinfotech.com/mcp`
- Markdown Twin: `https://yariinfotech.com/work.md`
- Schema Feed (JSONL): `https://yariinfotech.com/feeds/projects.jsonl`
