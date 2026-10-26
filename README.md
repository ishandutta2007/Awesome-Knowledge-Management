# Awesome-Knowledge-Management

# Top Knowledge Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Team Wikis, Documentation Platforms & Self-Hosted Knowledge Bases*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Knowledge Management**. These tools enable teams and organizations to capture, organize, and share institutional knowledge—from internal wikis and process documentation to customer-facing help centers—reducing information silos and accelerating onboarding and support resolution.

**Examples** include ServiceNow Knowledge Management, Guru, Notion, Document360, Bloomfire, Slab, Confluence, Slite, Helpjuice, and GitBook (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosted wikis and documentation platforms—ideal for teams seeking data ownership and Confluence/Notion alternatives without per-seat licensing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ServiceNow Knowledge Management](https://www.servicenow.com/)**  
  Enterprise knowledge management integrated with ITSM workflows, featuring knowledge bases, article templates, feedback management, and the new Knowledge Center with Now Assist AI for article optimization; note that the enhanced editor has reported adoption challenges including missing tables and code view compared to the classic editor .

- **[Guru](https://www.getguru.com/)**  
  AI-powered knowledge management with verified "Cards" for quick answers, contextual help integrations (browser extension, Slack), and strong search; users report ease-of-use as its highest-performing feature but note search can be lackluster at scale .

- **[Notion](https://www.notion.com/)**  
  All-in-one workspace combining wikis, docs, and project management with database-driven pages; free for personal use and $10/user/month for Plus teams; popular for its flexible block-based editor and template ecosystem .

- **[Document360](https://document360.com/)**  
  AI-native knowledge base platform with Eddy AI suite (search, chatbot, authoring), article analytics, and MCP server; SOC 2 Type II and ISO 27001 certified; customers report 70-90% self-service resolution improvements .

- **[Bloomfire](https://bloomfire.com/)**  
  AI knowledge management platform with Enterprise Intelligence Engine that ingests from SharePoint, Google Drive, and Confluence; features self-healing content governance with duplicate/stale content flagging and configurable compliance guardrails .

- **[Slab](https://slab.com/)**  
  Knowledge base and team wiki with a clean editor and Chrome extension for quick access; positioned as a simpler alternative to Confluence for teams wanting minimal setup overhead .

- **[Confluence](https://www.atlassian.com/software/confluence)**  
  Atlassian's team workspace and documentation platform with strong Jira integration; users note it works well once set up but requires effort to maintain organization and can become messy at scale with slow loading on media-heavy pages .

- **[Slite](https://slite.com/)**  
  AI-powered knowledge base with doc verification workflows, agentic search, and MCP/API access; SOC 2 Type II and HIPAA compliant on Enterprise; positioned as a "memory layer" for AI-native teams .

- **[Helpjuice](https://www.helpjuice.com/)**  
  Knowledge base software focused on customer support with accordions, tabs, and decision trees without coding; starts at $120/month .

- **[GitBook](https://www.gitbook.com/)**  
  Documentation platform with Git sync, visual editor, and AI assistant; free tier for individuals, Essential at $65/site/month, and Ultimate at $249/site/month; popular for product and API documentation .

## Open-Source GitHub Projects

- **[Docmost](https://github.com/docmost/docmost)**  
  Leading open-source Confluence/Notion alternative (AGPL-3.0, ~21k GitHub stars); features spaces with nested pages, real-time collaborative editing, granular permissions, comments, full-text search, page history, file attachments, and native diagram support (Draw.io, Excalidraw, Mermaid); built-in email/password auth means teams can start without SSO configuration; Docker-deployable with PostgreSQL and Redis .

- **[Outline](https://github.com/outline/outline)**  
  Polished self-hosted wiki (BSL 1.1, ~38.8k GitHub stars) with a Notion-like block editor and mature API/integration ecosystem built over eight years; requires external OIDC/SAML authentication (no built-in auth); ideal for teams with existing SSO infrastructure who need programmatic access to wiki content .

- **[Wiki.js](https://github.com/requarks/wiki)**  
  Developer-focused wiki (AGPL-3.0, ~25k GitHub stars) with Git-backed content and public-facing capabilities; supports multiple databases and is suited for teams wanting version-controlled documentation with developer workflows .

- **[BookStack](https://github.com/BookStackApp/BookStack)**  
  Structured knowledge base (MIT, ~16k GitHub stars) with book/chapter/page hierarchy; PHP/Laravel + MySQL stack; best for non-technical teams needing a clean, organized wiki without DevOps overhead .

- **[Trilium Notes](https://github.com/zadam/trilium)**  
  Self-contained knowledge graph (AGPL-3.0, ~28k GitHub stars) for personal and small-team use; Node.js-based with a focus on hierarchical note-taking and linking .

### Additional Strong Open-Source Options

- **Gitea Wiki** — MIT-licensed wiki bundled with Gitea; zero additional infrastructure for dev teams already using Gitea for source control .
- **dsh-kb** — Python-based knowledge base tool with zone-based access control, RAG check for vector store consistency, and MCP server for AI agent integration; useful for teams building AI-augmented knowledge retrieval pipelines .

**Frameworks for building custom systems**: Combine **Docmost** for real-time collaborative wiki editing with diagram support, **Outline** for polished documentation with API access, and **BookStack** for structured non-technical knowledge bases in a self-hosted knowledge management stack; layer **dsh-kb** for AI-ready retrieval pipelines if building RAG-based knowledge assistants.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Knowledge management platforms handling internal documentation must comply with applicable data governance policies; access controls and content ownership are critical for sensitive process documentation.
- Self-hosted open-source solutions vary in authentication requirements—Docmost includes built-in auth for quick starts, while Outline requires external OIDC/SAML setup; choose based on existing identity infrastructure.
- Verify license terms for commercial use; Docmost and Wiki.js and Trilium use AGPL-3.0, Outline uses BSL 1.1, and BookStack uses MIT .

---

**Made for documentation teams, knowledge managers, engineering leads, and support operations.**  
Let's make knowledge management more open, findable, and trustworthy.
