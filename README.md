# Ajvo

Software engineer building backend-heavy data products, internal platforms, and AI-assisted analytics tooling.

I work across the full path from ingestion to UI: ETL pipelines, APIs, metadata catalogs, lineage, operator tools, and developer-facing AI integrations. Most of my strongest work lives in private GitHub repos because it runs inside production analytics environments.

I am strongest when the problem is technically messy, operationally important, and needs to become reliable software.

## What I Bring

- I turn manual or fragile analytics workflows into maintainable internal products
- I replace legacy SSIS-style and ad hoc processes with code-first `.NET` services
- I build systems that connect `SQL Server`, `PostgreSQL`, `Power BI`, external APIs, and frontend operator tooling
- I use AI pragmatically: for debugging, search, catalog exploration, and control surfaces, not as decoration

## Flagship Project

### TEDOM Data Platform `private`

At TEDOM Energie I am building a unified on-premise platform that combines:

- `.NET 9` ETL worker with **7 adapters** for Raynet, Oracle, EEX, SendGrid, Excel, REST APIs, and AI tasks
- `.NET 8` catalog/API layer with **50+ endpoints**
- `Vue 3` application with **14 views** for operations, lineage, catalog search, and monitoring
- `Semantic Kernel` AI agent with **36 tools** and MCP integration
- metadata graph with **2,600+ objects** and **2,500+ relations**

The value is simple: one system for running pipelines, understanding data dependencies, querying operational state, and debugging failures.

## Selected GitHub Work

| Project | Scope | What it shows |
|---|---|---|
| `TEDOM Data Platform` `private` | Unified ETL + catalog + AI operations platform | End-to-end ownership from ingestion and orchestration to API, UI, AI agent, and MCP surface |
| `Tedom-Hub-Catalog` `private` | Internal metadata catalog and lineage product | Search, impact analysis, Power BI and SQL metadata modeling, grounded AI assistance |
| `ETLToDWH` `private` | TEDOM Energie ETL modernization | Raynet, Oracle ZIS, and Excel ingestion; migration away from SSIS; measured **2.2x speedup** across **130+ tables** |
| `SendGrid` `private` | SendGrid ELT service for analytics | Bulk export orchestration, Microsoft Graph mailbox boundary, transactional SQL imports, dedupe-safe event loading |
| [`powerbi-mcp`](https://github.com/AjvoGod/powerbi-mcp) | Public Power BI MCP server | Developer tooling, PBIX analysis, semantic model extraction, report export, cloud operations |
| [`mcp-sql-agent`](https://github.com/AjvoGod/mcp-sql-agent) | Public read-only SQL MCP server | Safe SQL access for AI assistants across PostgreSQL and SQL Server |

## Current Focus

- Internal platform engineering for analytics and BI teams
- Metadata, lineage, and operator tooling that make complex systems easier to inspect
- AI-assisted workflows around SQL, Power BI, and production data operations

## Stack

`C#` `TypeScript` `.NET 8/9` `SQL Server` `PostgreSQL` `Vue 3` `React` `Power BI` `Docker` `Semantic Kernel` `RAG` `MCP`

## Connect

- LinkedIn: [ivo-schwarz-8577832a2](https://www.linkedin.com/in/ivo-schwarz-8577832a2/)
- Email: [ivoschwarz@seznam.cz](mailto:ivoschwarz@seznam.cz)
