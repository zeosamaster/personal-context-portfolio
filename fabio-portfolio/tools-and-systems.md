# Tools and Systems

## Daily Tools

### Monorepo Tooling
- **pnpm (v10)** — package manager
- **Nx (v20)** — task orchestration and caching
- **Changesets** — versioning

### Language & Runtime
- **TypeScript (v5.9)**
- **Node.js 24.x**

### Frontend
- **Next.js (v16)** — primary web framework
- **React (v19)**
- **Storybook (v10)** — component documentation

### UI & Styling
- **Tailwind CSS (v3.4)** + plugins
- **Radix UI** — dialog, dropdown, tooltip and other primitives
- **Floating UI** — overlays

### State & Data
- **TanStack Query (v5)** — server state
- **TanStack Table (v8)** — data tables
- **TanStack Form (v1)**
- **Zod** — schema validation
- **GraphQL + @graphql-codegen**
- **Hono** — lightweight HTTP framework

### Testing
- **Jest (v29)** — unit tests
- **Vitest (v4)** — component/unit tests
- **Playwright** — E2E tests
- **Currents** — e2e reporting
- **Trunk.io** — e2e reporting

### Communication
- **Slack** — primary work communication tool; target platform for automated reporting (e2e health report currently posted manually; CI/CD metrics reporting a future candidate if charting is supported)

### Build & DX
- **ESLint (v9)** with custom Chainlink rules
- **Prettier (v3.4)**
- **oh-my-zsh** — shell setup

### Infrastructure & Services
- **GitHub Actions** — CI/CD
- **Vercel** — deployments
- **Sentry** — error tracking (currently used effectively on Econ dApps only; planned expansion to all dApps)
- **Auth0** — CRE authentication
- **Supabase** — database (non-sensitive data)
- **imgix** — image optimization and CDN delivery
- **AWS S3** — image storage
- **Postgraphile** — GraphQL-over-Postgres API (owned and maintained by other teams)
- **1Password** — shared credentials
- **direnv** — env var management
- **JIRA** — project management

### Scale
- ~43 apps (console, CCIP, bridge, staking, rewards, NOP, ACE UIs, e2e suites)
- ~44+ libraries (design system, SDK, auth, wallet, web3 utilities)

## Custom Scripts & Workflows

- Scripts for CI/CD metrics (GitHub API → Google Sheets) and e2e failure reporting (Currents SDK → Slack)
- Additional personal scripts to be documented from secondary machine — [PLACEHOLDER: run script inventory session on other computer]

## Data Sources

- **Google Docs** — technical documentation
- **Google Sheets** — CI/CD and e2e metrics tracking (historical data)
- **JIRA** — project and ticket management
- **GitHub** — code, PRs, and merge queue data

## Integrations and Connections

- CI/CD metrics script pulls from GitHub API → output copied to Google Sheets
- E2e reporting script pulls from Currents SDK → agent generates summary → posted to Slack

## Evaluating or Planning to Adopt

- **Claude Code and agent-driven development** — exploring how to incorporate AI agents into daily workflows; current manual steps in CI/CD and e2e reporting are candidates for full automation

## Tried and Rejected

None documented.
