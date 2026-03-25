# Awesome MCP Servers 2026 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of Model Context Protocol (MCP) servers for AI agents — focused on **production-ready, free, and self-hosted** options.

> MCP lets AI assistants (Claude, ChatGPT, Cursor) connect to external tools, APIs, and data sources. Think of it as USB-C for AI.

## Contents

- [What is MCP?](#what-is-mcp)
- [Web & Search](#web--search)
- [Data & Research](#data--research)
- [Social Media](#social-media)
- [Developer Tools](#developer-tools)
- [Business & Productivity](#business--productivity)
- [AI & ML](#ai--ml)
- [Self-Hosted](#self-hosted)
- [On Apify](#on-apify)
- [Building Your Own](#building-your-own)

## What is MCP?

Model Context Protocol (MCP) is an open standard by Anthropic that lets AI assistants connect to external data sources and tools. Instead of copy-pasting data into chat, MCP servers provide it automatically.

**How it works:**
```
AI Assistant ←→ MCP Client ←→ MCP Server ←→ External API/Database
```

**Key benefits:**
- Universal protocol — works with Claude, Cursor, and other MCP-compatible tools
- Secure — controlled access to specific data
- Composable — connect multiple servers for complex workflows

## Web & Search

| Server | Description | Free? |
|--------|-------------|-------|
| [Playwright MCP](https://github.com/anthropics/mcp-playwright) | Browser automation — navigate, click, screenshot | ✅ |
| [Fetch MCP](https://github.com/anthropics/mcp-fetch) | Fetch web pages and convert to markdown | ✅ |
| [Firecrawl MCP](https://github.com/firecrawl/mcp-server) | Web scraping with JavaScript rendering | Freemium |
| [Google Search MCP](https://apify.com/datascoutapi/google-search-mcp-server) | Google search results for AI agents | Apify credits |
| [Tavily MCP](https://github.com/tavily-ai/tavily-mcp) | AI-optimized web search | API key |

## Data & Research

| Server | Description | Free? |
|--------|-------------|-------|
| [Research Tools MCP](https://apify.com/halilc4/research-tools-mcp) | Academic papers, citations, research | Apify credits |
| [Company Researcher MCP](https://apify.com/knotless_cadence/mcp-company-researcher) | Domain intel, tech stacks, funding | Apify credits |
| [PostgreSQL MCP](https://github.com/anthropics/mcp-postgres) | Query PostgreSQL databases | ✅ |
| [SQLite MCP](https://github.com/anthropics/mcp-sqlite) | Query SQLite databases | ✅ |
| [Filesystem MCP](https://github.com/anthropics/mcp-filesystem) | Read/write local files | ✅ |

## Social Media

| Server | Description | Free? |
|--------|-------------|-------|
| [Reddit MCP Scraper](https://apify.com/crawlerbros/reddit-mcp-scraper) | Reddit posts and comments | Apify credits |
| [Slack MCP](https://github.com/anthropics/mcp-slack) | Read/send Slack messages | ✅ |
| [Bluesky MCP](https://github.com/keturiosakys/bluesky-context) | Bluesky social posts | ✅ |
| [Social Monitor MCP](https://apify.com/knotless_cadence/mcp-social-monitor) | Multi-platform social monitoring | Apify credits |

## Developer Tools

| Server | Description | Free? |
|--------|-------------|-------|
| [GitHub MCP](https://github.com/anthropics/mcp-github) | Repos, issues, PRs, code search | ✅ |
| [Git MCP](https://github.com/anthropics/mcp-git) | Local git operations | ✅ |
| [Sentry MCP](https://github.com/getsentry/sentry-mcp) | Error tracking and monitoring | API key |
| [Linear MCP](https://github.com/linear/linear-mcp) | Project management | API key |
| [Tester MCP Client](https://apify.com/jiri.spilka/tester-mcp-client) | Test MCP servers | Apify credits |

## Business & Productivity

| Server | Description | Free? |
|--------|-------------|-------|
| [Google Drive MCP](https://github.com/anthropics/mcp-gdrive) | Read Google Drive files | ✅ |
| [Notion MCP](https://github.com/anthropics/mcp-notion) | Notion pages and databases | ✅ |
| [Lead Finder MCP](https://apify.com/knotless_cadence/mcp-lead-finder) | Find emails, tech stacks | Apify credits |
| [Trend Detector MCP](https://apify.com/knotless_cadence/mcp-trend-detector) | Emerging tech trends | Apify credits |
| [Memory MCP](https://github.com/anthropics/mcp-memory) | Persistent memory for AI | ✅ |

## AI & ML

| Server | Description | Free? |
|--------|-------------|-------|
| [EverArt MCP](https://github.com/anthropics/mcp-everart) | AI image generation | API key |
| [Brave Search MCP](https://github.com/anthropics/mcp-brave-search) | Web search via Brave | API key |
| [Sequential Thinking MCP](https://github.com/anthropics/mcp-sequential-thinking) | Step-by-step reasoning | ✅ |

## Self-Hosted

These servers run on your own infrastructure:

| Server | Description |
|--------|-------------|
| [MCP Server Template](https://github.com/anthropics/create-mcp-server) | Create your own MCP server |
| [MCP Python SDK](https://github.com/anthropics/mcp-python-sdk) | Python SDK for building servers |
| [MCP TypeScript SDK](https://github.com/anthropics/mcp-typescript-sdk) | TypeScript SDK |

## On Apify

MCP servers that run on Apify platform (cloud-hosted, no setup needed):

- [Company Researcher](https://apify.com/knotless_cadence/mcp-company-researcher) — Domain intelligence
- [Trend Detector](https://apify.com/knotless_cadence/mcp-trend-detector) — Tech trend detection
- [Lead Finder](https://apify.com/knotless_cadence/mcp-lead-finder) — Business lead generation
- [Social Monitor](https://apify.com/knotless_cadence/mcp-social-monitor) — Social media monitoring
- [Web Search](https://apify.com/knotless_cadence/mcp-web-search) — Multi-source web search

## Building Your Own

```bash
# Install the MCP SDK
pip install mcp

# Create a new server
npx @anthropics/create-mcp-server my-server
```

### Resources
- [MCP Specification](https://modelcontextprotocol.io/)
- [MCP Documentation](https://docs.anthropic.com/en/docs/build-with-claude/mcp)
- [Awesome Web Scraping 2026](https://github.com/spinov001-art/awesome-web-scraping-2026) — 60+ scraping tools
- [Awesome No-Auth APIs](https://github.com/spinov001-art/awesome-no-auth-apis) — 50+ free APIs

## Contributing

PRs welcome! Add your MCP server with a brief description and link.

## License

CC0 — Public Domain
