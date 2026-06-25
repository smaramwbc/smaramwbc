### Hi

Building [**Statewave**](https://github.com/smaramwbc/statewave) — AI memory built for production.

Policies, sensitivity labels, and tamper-evident audit receipts — not just retrieval. Every memory traces to its source. Governance built in from day one.

<a href="https://github.com/smaramwbc/statewave#user-content-how-it-works" target="_blank" rel="noopener noreferrer">
  <picture>
    <source media="(max-width: 600px) and (prefers-color-scheme: dark)"
            srcset="https://raw.githubusercontent.com/smaramwbc/statewave/main/docs/img/how-statewave-works-mobile-dark.png">
    <source media="(max-width: 600px)"
            srcset="https://raw.githubusercontent.com/smaramwbc/statewave/main/docs/img/how-statewave-works-mobile-light.png">
    <source media="(prefers-color-scheme: dark)"
            srcset="https://raw.githubusercontent.com/smaramwbc/statewave/main/docs/img/how-statewave-works-dark.png">
    <img alt="How Statewave works"
         src="https://raw.githubusercontent.com/smaramwbc/statewave/main/docs/img/how-statewave-works-light.png"
         width="720">
  </picture>
</a>

#### Getting started

The fastest path — interactive setup, connects your first memory source in under a minute:

```bash
# macOS / Linux
npx @statewavedev/statewave
# or
curl -fsSL https://www.statewave.ai/install | sh
```

```powershell
# Windows (PowerShell)
irm https://www.statewave.ai/install.ps1 | iex
```

Or run the full stack yourself:

```bash
git clone https://github.com/smaramwbc/statewave && cd statewave
docker compose up -d   # API on http://localhost:8100
```

Then point an SDK — or any HTTP client — at it:

- **Python** — `pip install statewave`
- **TypeScript** — `npm install @statewavedev/sdk`
- **REST API** — any language, via the [OpenAPI docs](http://localhost:8100/docs) (or the [v1 contract](https://github.com/smaramwbc/statewave-docs/blob/main/api/v1-contract.md))

Full walkthrough: **[Getting Started (5 min)](https://github.com/smaramwbc/statewave-docs/blob/main/getting-started.md)**.

#### What I'm working on

- [**statewave**](https://github.com/smaramwbc/statewave) — core engine
- [**statewave-py**](https://github.com/smaramwbc/statewave-py) — Python SDK
- [**statewave-ts**](https://github.com/smaramwbc/statewave-ts) — TypeScript SDK
- [**statewave-connectors**](https://github.com/smaramwbc/statewave-connectors) — integrations
- [**statewave-admin**](https://github.com/smaramwbc/statewave-admin) — admin dashboard and CLI
- [**statewave-docs**](https://github.com/smaramwbc/statewave-docs) — docs and guides

#### Reach me

- [statewave.ai](https://statewave.ai)
- [GitHub Discussions](https://github.com/smaramwbc/statewave/discussions)
- hello@statewave.ai
