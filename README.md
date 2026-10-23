<div align="center">

  <img src="assets/banner.svg" alt="Awesome Model Context Protocol (MCP) Ecosystem Banner" width="100%" />

  <p align="center">
    <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
    <a href="https://github.com/ishandutta2007/Awesome-Model-Context-Protocol-MCP/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Model-Context-Protocol-MCP?style=flat-square&logo=github&color=gold" alt="Repo Stars" /></a>
    <a href="https://github.com/ishandutta2007/Awesome-Model-Context-Protocol-MCP/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Model-Context-Protocol-MCP?style=flat-square&logo=github&color=blue" alt="Repo Forks" /></a>
    <a href="https://github.com/ishandutta2007/Awesome-Model-Context-Protocol-MCP/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg?style=flat-square" alt="License" /></a>
    <a href="https://github.com/ishandutta2007/Awesome-Model-Context-Protocol-MCP/pulls"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome" /></a>
    <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
  </p>

</div>

---

# ⚡ Awesome Model Context Protocol (MCP)

> **The definitive, SEO-optimized directory of Model Context Protocol (MCP) servers, managed SaaS gateways, developer SDKs, client integrations, and enterprise AI agent infrastructure.**

The **Model Context Protocol (MCP)** is an open standard pioneered by Anthropic that allows AI agents, LLMs, and assistants (Claude Desktop, Claude Code, Cursor, Codex, Windsurf, OpenCode) to securely connect to external tools, databases, enterprise SaaS platforms, and local developer environments via a standardized client-server protocol.

---

## 📑 Table of Contents

- [⚡ Awesome Model Context Protocol (MCP)](#-awesome-model-context-protocol-mcp)
  - [📑 Table of Contents](#-table-of-contents)
  - [📊 Sector Overview \& Market Dynamics](#-sector-overview--market-dynamics)
  - [🏢 Enterprise SaaS \& Managed MCP Gateways](#-enterprise-saas--managed-mcp-gateways)
  - [🛠️ Open-Source MCP Servers, SDKs \& Tooling](#️-open-source-mcp-servers-sdks--tooling)
  - [🎯 Key Architectural Highlights](#-key-architectural-highlights)
  - [🤝 How to Contribute](#-how-to-contribute)
  - [🛡️ Security \& Operational Disclaimer](#️-security--operational-disclaimer)
  - [📈 Star History](#-star-history)
  - [💖 Support \& Sponsorship](#-support--sponsorship)

---

## 📊 Sector Overview & Market Dynamics

The global AI agent infrastructure and autonomous execution market is projected to expand from **$7.84 billion in 2025 to over $52.62 billion by 2030** (compounding at a CAGR of 46.3%), catalyzed by widespread enterprise migration toward agentic tool execution and context-aware LLMs. 

The market exhibits a **bifurcated structure**:
- **Tooling & Integration Layer:** **Moderately to highly fragmented**, characterized by rapid product launches across managed OAuth gateways, specialized documentation search engines, local proxy runners, and open-source server repositories.
- **Foundational Execution Layer:** **Highly concentrated**, with hyperscalers and frontier model providers (Anthropic, OpenAI, Microsoft, Google) exerting strong gravity over protocol adoption, client interfaces, and foundational runtime primitives.

---

## 🏢 Enterprise SaaS & Managed MCP Gateways

The following commercial platforms offer managed authentication (OAuth 2.0 / API keys), hosted MCP proxy endpoints, token overhead optimization, and enterprise governance.

*Sorted descending by Company Size (Valuation / Total Capital Raised).*

| 🏢 Platform | 💰 Company Size (Valuation / Raised) | 🏷️ Starting Tier Pricing | 🆓 Free Tier Limits | ⚙️ Key MCP Capabilities |
| :--- | :--- | :--- | :--- | :--- |
| **[Langfuse](https://langfuse.com)** | **$15.0B Valuation** *(ClickHouse parent post-$400M Series D; $4.5M seed)* | **$29 / month** *(Core Plan; Pro at $199/mo)* | **Free forever (Hobby Plan)**: 50,000 traces/events per month, 30-day retention, 2 user seats, zero credit card required. | Open-source LLM observability, trace evaluation, prompt engineering, and native MCP server tracing endpoints for agent workflows. |
| **[Arcade.dev](https://arcade.dev)** *(acquired [Smithery](https://smithery.ai))* | **~$250M Valuation** *($72.0M total funding; $60M Series A led by SYN Ventures)* | **$25 / month** *(Team Platform fee + $0.01/tool call, $0.10/auth event)* | **Free forever (Arcade Cloud)**: 2,000 tool executions/month and 2,000 user auth events/month with no card required. | Action execution runtime and secure MCP gateway with managed OAuth, identity governance, and the integrated Smithery registry directory. |
| **[Braintrust](https://www.braintrust.dev)** | **~$150M Valuation** *($83.0M total funding; Series B led by Coatue)* | **$24 / user / month** *(Pro Plan with unlimited projects)* | **Free forever (Starter Plan)**: 10,000 logged records/month, 100 evaluations/month, and 1 user seat. | Enterprise AI evaluation, prompt testing, and end-to-end tracing for custom MCP client-server tool invocations. |
| **[Composio](https://composio.dev)** | **~$150M Valuation** *($29.0M total funding; $25M Series A led by Lightspeed)* | **$29 / month** *(Pro Plan with dedicated concurrency quotas)* | **Free forever (Hobby Plan)**: 100,000 own-app tool executions/month, 50,000 trigger events/month, supporting up to 3 team seats. | Managed MCP connectivity layer spanning 1,000+ apps (GitHub, Salesforce, Jira, Slack) with remote sandboxed processing to prevent context bloat. |
| **[Superface](https://superface.ai)** | **~$20M Valuation** *(€3.8M / ~$4.1M venture funding raised)* | **€49 / month** *(~$53/month Starter Plan)* | **Free forever (Developer Plan)**: 1,000 API runs/tool executions per month with access to community hub connectors. | Zero-code MCP wrapper and managed API gateway transforming external REST APIs into callable MCP endpoints using single unified API keys. |
| **[Toolhouse](https://toolhouse.ai)** | **~$15M Valuation** *(Seed funding from Ganas Ventures, 500 Global, Vento)* | **$5.00 per 1,000 requests** *(Go Pay-As-You-Go Plan)* | **Free forever (Free Tier)**: 300 tool executions per month, 3 active autonomous agents, and community support. | Agent action marketplace providing sandboxed Python code execution, web scrapers, email dispatchers, and memory tools via MCP endpoints. |
| **[Glama](https://glama.ai)** | **~$10M Valuation** *($2.5M seed funding)* | **$19 / month** *(Pro Plan with team sharing & monitoring)* | **Free forever (Community Plan)**: 50 MCP tool executions per day, unlimited public server searches, zero credit card required. | Cloud search engine, live inspection sandbox, and hosted gateway for Model Context Protocol servers and developer tools. |

---

## 🛠️ Open-Source MCP Servers, SDKs & Tooling

High-impact open-source implementations, official protocol libraries, developer inspection suites, community registries, and cloud platform servers.

*Sorted descending by GitHub Stargazer Count.*

| 📦 Repository & Project | ⭐ GitHub Stars | 📜 License | 💡 Architecture & Primary Use Case |
| :--- | :--- | :--- | :--- |
| **[punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers)** | [![Stars](https://img.shields.io/github/stars/punkpeye/awesome-mcp-servers?style=social&color=white)](https://github.com/punkpeye/awesome-mcp-servers/stargazers) | MIT | **De facto community directory** organizing hundreds of community MCP servers with metadata tags for language, cloud vs. local runtime, and platform compatibility. |
| **[modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers)** | [![Stars](https://img.shields.io/github/stars/modelcontextprotocol/servers?style=social&color=white)](https://github.com/modelcontextprotocol/servers/stargazers) | Apache-2.0 | **Official reference servers** maintained by protocol authors: `Everything` (test/demo), `Fetch` (web extraction), `Filesystem` (secure file I/O), `Git` (VCS operations), `Memory` (knowledge graph), `Sequential Thinking`, and `Time`. |
| **[github/github-mcp-server](https://github.com/github/github-mcp-server)** | [![Stars](https://img.shields.io/github/stars/github/github-mcp-server?style=social&color=white)](https://github.com/github/github-mcp-server/stargazers) | MIT | **GitHub's official MCP server** providing contextual access to repositories, pull requests, issues, branch trees, file diffs, and GitHub Actions workflows. |
| **[modelcontextprotocol/python-sdk](https://github.com/modelcontextprotocol/python-sdk)** | [![Stars](https://img.shields.io/github/stars/modelcontextprotocol/python-sdk?style=social&color=white)](https://github.com/modelcontextprotocol/python-sdk/stargazers) | MIT | **Official Python SDK** providing async client/server primitives, SSE (Server-Sent Events) and stdio transports, plus the high-level `FastMCP` interface. |
| **[microsoft/mcp-for-beginners](https://github.com/microsoft/mcp-for-beginners)** | [![Stars](https://img.shields.io/github/stars/microsoft/mcp-for-beginners?style=social&color=white)](https://github.com/microsoft/mcp-for-beginners/stargazers) | MIT | **Microsoft open-source curriculum** covering core MCP fundamentals, session setup, tool dispatch, and service orchestration across .NET, Java, TypeScript, Rust, and Python. |
| **[modelcontextprotocol/typescript-sdk](https://github.com/modelcontextprotocol/typescript-sdk)** | [![Stars](https://img.shields.io/github/stars/modelcontextprotocol/typescript-sdk?style=social&color=white)](https://github.com/modelcontextprotocol/typescript-sdk/stargazers) | MIT | **Official TypeScript/Node.js SDK** featuring strict Zod schema validation, modular stream transports, and complete protocol type declarations. |
| **[apify/actors-mcp-server](https://github.com/apify/actors-mcp-server)** | [![Stars](https://img.shields.io/github/stars/apify/actors-mcp-server?style=social&color=white)](https://github.com/apify/actors-mcp-server/stargazers) | MIT | **Apify Actor MCP server** connecting agents to thousands of pre-built scrapers, social media crawlers, map extractors, and automated data collectors on the Apify Store. |
| **[hangwin/mcp-chrome](https://github.com/hangwin/mcp-chrome)** | [![Stars](https://img.shields.io/github/stars/hangwin/mcp-chrome?style=social&color=white)](https://github.com/hangwin/mcp-chrome/stargazers) | MIT | **Chrome browser extension server** enabling LLMs to automate tabs, extract clean DOM representations, conduct semantic search, and inspect live network responses. |
| **[tadata-org/fastapi_mcp](https://github.com/tadata-org/fastapi_mcp)** | [![Stars](https://img.shields.io/github/stars/tadata-org/fastapi_mcp?style=social&color=white)](https://github.com/tadata-org/fastapi_mcp/stargazers) | MIT | **FastAPI MCP bridge** that automatically transforms existing Python FastAPI route endpoints into standardized MCP tools with authentication and Pydantic schema parsing. |
| **[modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector)** | [![Stars](https://img.shields.io/github/stars/modelcontextprotocol/inspector?style=social&color=white)](https://github.com/modelcontextprotocol/inspector/stargazers) | MIT | **Visual developer test suite** allowing developers to connect to any local or remote MCP server, trigger tools interactively, evaluate prompt templates, and inspect resources. |
| **[mobile-next/mobile-mcp](https://github.com/mobile-next/mobile-mcp)** | [![Stars](https://img.shields.io/github/stars/mobile-next/mobile-mcp?style=social&color=white)](https://github.com/mobile-next/mobile-mcp/stargazers) | MIT | **Mobile device automation server** providing agents with UI hierarchy inspection, screenshot capture, gesture automation, and screen scraping for iOS and Android. |
| **[modelcontextprotocol/modelcontextprotocol](https://github.com/modelcontextprotocol/modelcontextprotocol)** | [![Stars](https://img.shields.io/github/stars/modelcontextprotocol/modelcontextprotocol?style=social&color=white)](https://github.com/modelcontextprotocol/modelcontextprotocol/stargazers) | MIT | **Specification & governance repository** detailing protocol architecture, JSON-RPC 2.0 messages, lifecycle flows, capabilities negotiation, and security standards. |
| **[mark3labs/mcp-go](https://github.com/mark3labs/mcp-go)** | [![Stars](https://img.shields.io/github/stars/mark3labs/mcp-go?style=social&color=white)](https://github.com/mark3labs/mcp-go/stargazers) | MIT | **High-performance Go implementation** providing lightweight MCP servers and clients with minimal memory footprint and native goroutine concurrency. |
| **[lastmile-ai/mcp-agent](https://github.com/lastmile-ai/mcp-agent)** | [![Stars](https://img.shields.io/github/stars/lastmile-ai/mcp-agent?style=social&color=white)](https://github.com/lastmile-ai/mcp-agent/stargazers) | Apache-2.0 | **Agent orchestration framework** leveraging Model Context Protocol primitives to build multi-agent workflows, router patterns, and persistent state machines. |
| **[firecrawl/firecrawl-mcp-server](https://github.com/firecrawl/firecrawl-mcp-server)** | [![Stars](https://img.shields.io/github/stars/firecrawl/firecrawl-mcp-server?style=social&color=white)](https://github.com/firecrawl/firecrawl-mcp-server/stargazers) | Apache-2.0 | **Firecrawl web crawling MCP server** converting complex dynamic websites into clean, LLM-ready markdown chunks with deep recursive scraping support. |
| **[modelcontextprotocol/registry](https://github.com/modelcontextprotocol/registry)** | [![Stars](https://img.shields.io/github/stars/modelcontextprotocol/registry?style=social&color=white)](https://github.com/modelcontextprotocol/registry/stargazers) | Apache-2.0 | **Decentralized community registry service** for publishing, resolving, and discovering verified MCP servers across public package registries. |
| **[open-webui/mcpo](https://github.com/open-webui/mcpo)** | [![Stars](https://img.shields.io/github/stars/open-webui/mcpo?style=social&color=white)](https://github.com/open-webui/mcpo/stargazers) | MIT | **OpenAPI-to-MCP dynamic proxy server** allowing agents to consume arbitrary OpenAPI 3.x specifications on the fly with Bearer, API key, and Basic auth pass-through. |
| **[cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare)** | [![Stars](https://img.shields.io/github/stars/cloudflare/mcp-server-cloudflare?style=social&color=white)](https://github.com/cloudflare/mcp-server-cloudflare/stargazers) | Apache-2.0 | **Cloudflare official MCP server** enabling AI assistants to configure DNS records, inspect analytics, deploy Workers, manage KV/D1 storage, and execute security rules. |
| **[wong2/awesome-mcp-servers](https://github.com/wong2/awesome-mcp-servers)** | [![Stars](https://img.shields.io/github/stars/wong2/awesome-mcp-servers?style=social&color=white)](https://github.com/wong2/awesome-mcp-servers/stargazers) | MIT | **Curated index of community servers** categorized by databases (PostgreSQL, SQLite, Redis), dev tools, developer cloud APIs, and productivity applications. |
| **[browserbase/mcp-server-browserbase](https://github.com/browserbase/mcp-server-browserbase)** | [![Stars](https://img.shields.io/github/stars/browserbase/mcp-server-browserbase?style=social&color=white)](https://github.com/browserbase/mcp-server-browserbase/stargazers) | MIT | **Browserbase cloud headless browser server** executing CAPTCHA-bypassing, proxy-routed web navigation sessions with video recording and live DOM state inspection. |
| **[docker/mcp-gateway](https://github.com/docker/mcp-gateway)** | [![Stars](https://img.shields.io/github/stars/docker/mcp-gateway?style=social&color=white)](https://github.com/docker/mcp-gateway/stargazers) | Apache-2.0 | **Docker MCP gateway & container runtime** providing sandboxed execution environments for running and isolating untrusted third-party MCP servers. |

---

## 🎯 Key Architectural Highlights

```mermaid
flowchart LR
    subgraph Clients["🤖 AI Clients & Runtimes"]
        C1["Claude Desktop / Code"]
        C2["Cursor & Codex IDEs"]
        C3["Autonomous Agent Frameworks"]
    end

    subgraph Gateway["🔐 MCP Gateway & Action Layer"]
        G1["OAuth & Identity Broker"]
        G2["AST Inspection & Permissions"]
        G3["Context & Token Optimizer"]
    end

    subgraph Servers["📦 MCP Servers & Endpoints"]
        S1["Filesystem & Git"]
        S2["Databases & Knowledge Graphs"]
        S3["Enterprise SaaS APIs"]
        S4["Browser Automation"]
    end

    Clients <-->|"JSON-RPC 2.0 (stdio / SSE)"| Gateway
    Gateway <-->|"Standardized MCP Tools"| Servers
```

- **Transport Decoupling:** MCP operates seamlessly over both local standard input/output (`stdio`) and remote HTTP streaming (`Server-Sent Events / SSE`), making it equally viable for local command-line tools and distributed cloud microservices.
- **Three Core Primitives:**
  - **Tools:** Callable executable routines with typed JSON Schema contracts that produce dynamic side effects.
  - **Resources:** Passive, URI-addressable data sources (file contents, database schemas, log outputs).
  - **Prompts:** Pre-engineered templates with conversational context parameters.
- **Security Isolation:** Local servers run with isolated process permissions; enterprise gateways introduce centralized OAuth tokens, mitigating credential exposure to language models.

---

## 🤝 How to Contribute

Contributions, project submissions, and documentation enhancements are highly encouraged!

1. 🍴 **Fork the repository** to your own GitHub account.
2. 🌿 **Create a descriptive feature branch**:
   ```bash
   git checkout -b feat/add-mcp-server
   ```
3. 📝 **Add your entry** ensuring clear, factual descriptions, links to official documentation, and consistent Markdown table formatting:
   - For SaaS tools: include starting tier pricing, free tier limits, and verifiable company valuation/funding.
   - For open-source repos: include a star badge using the `style=social&color=white` parameters linking to the stargazers page.
   - Maintain sorted order (descending by company size or star count).
4. 🚀 **Commit your modifications** and **open a Pull Request** with an informative summary of your changes.

---

## 🛡️ Security & Operational Disclaimer

- This repository is a **community-curated directory** created for informational, architectural, and educational purposes. Mention of specific vendors, commercial SaaS products, or open-source projects does not constitute an official endorsement.
- **Inspect Capabilities Before Connection:** MCP servers execute code with the permissions of the host process. Always inspect whether a server requests unrestricted local filesystem access, outbound network access, or shell execution.
- **Sandboxed Execution:** For untrusted third-party servers, utilize sandboxed environments (such as Docker MCP gateways or managed proxies) to safeguard sensitive files and internal network resources.

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Model-Context-Protocol-MCP&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Model-Context-Protocol-MCP&type=date&legend=top-left)

---

## 💖 Support & Sponsorship

Thank you for exploring and using this curated directory of Model Context Protocol (MCP) tooling and agent infrastructure! If this resource helps you build or discover MCP tools:

- ⭐ **Star this repository** on GitHub to amplify its reach across the developer ecosystem.
- 🍴 **Fork and share** with colleagues, AI engineers, and agent developers.
- 💬 **Join our community** discussions on [Discord](https://discord.gg/jc4xtF58Ve).
- ☕ **Support continuous maintenance & research**: If this project saves you time or aids your enterprise agent evaluations, please consider sponsoring via the **[GitHub Sponsors Dashboard](https://github.com/sponsors/ishandutta2007)**.

<p align="center">
  <a href="https://github.com/sponsors/ishandutta2007">
    <img src="https://img.shields.io/badge/Sponsor%20on%20GitHub-EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white" alt="Sponsor on GitHub" />
  </a>
</p>

---

<p align="center">
  <strong>Crafted with ❤️ for developers, AI engineers, and platform architects building the future of agentic intelligence.</strong>
</p>
