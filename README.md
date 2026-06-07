# Automation Tools

Catalog for Stefan's reusable automation and workflow tools.

This repository is intentionally an index, not a monorepo. Each publishable
tool keeps its own repository, history, issues, CI, and release boundary. The
local workspace may contain child checkouts beside this README; those
directories are ignored by this catalog repository.

## Boundary

Belongs here:

- standalone CLIs, APIs, and local workflow tools
- reusable automation pattern libraries
- fixture-safe integration, routing, verification, and review tools
- thin concept/proof repos for automation workflow lanes
- local scripts that support automation discovery or monitoring

Does not belong here:

- larger consuming systems that orchestrate these tools
- unrelated apps, course work, media, or general experiments
- source datasets and saved research corpora
- hidden runtime caches managed by another tool

## Tools

| Tool | GitHub repo | Purpose |
| --- | --- |
| `ai-workflow-automation-mini-sprint` | [stefan-mcf/data-pipeline](https://github.com/stefan-mcf/data-pipeline) | Local-first workflow automation tool with CLI, reports, JSON summaries, and optional FastAPI wrapper. |
| `api-webhook-bridge` | [stefan-mcf/api-webhook-bridge](https://github.com/stefan-mcf/api-webhook-bridge) | Fixture-safe FastAPI webhook bridge for validation, mapping, and audit-backed integration walkthroughs. |
| `automation-debugger` | [stefan-mcf/automation-debugger](https://github.com/stefan-mcf/automation-debugger) | Fixture-safe broken automation diagnosis and replay tool. |
| `automation-kit` | [stefan-mcf/automation-kit](https://github.com/stefan-mcf/automation-kit) | Low-code automation pattern library with tested Python equivalents. |
| `browser-research-agent-public-export` | [stefan-mcf/browser-research](https://github.com/stefan-mcf/browser-research) | Public export of the browser automation research agent. |
| `invoice-router` | [stefan-mcf/invoice-router](https://github.com/stefan-mcf/invoice-router) | Fixture-safe invoice extraction, validation, review routing, and accounting export previews. |
| `review-router` | [stefan-mcf/review-router](https://github.com/stefan-mcf/review-router) | Deterministic review-gated AI workflow templates for low-code and API automation. |
| `sheets-airtable-sync` | [stefan-mcf/sheets-airtable-sync](https://github.com/stefan-mcf/sheets-airtable-sync) | Fixture-safe Google Sheets to Airtable validation, dedupe, reporting, API, MCP, and mock upsert proof. |

## Backlinks

Each publishable tool README should link back to this catalog:

```markdown
Part of [Stefan's automation tools catalog](https://github.com/stefan-mcf/automation-tools).
```
