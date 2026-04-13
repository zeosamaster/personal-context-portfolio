# Role and Responsibilities

## Core Responsibilities

- **CI/CD health:** Own the improvement of merge queue success rates across the team's repos. Track weekly and monthly metrics, report trends, and drive the work to get success rates consistently above 90%.
- **E2e health:** Own e2e test quality. Identify flaky and failing tests weekly, assign owners, drive fixes, and track improvement over time.
- **Wallet integrations:** Own wallet support end-to-end — from integrating new wallets for new chain families to building and maintaining the Playwright models used in e2e testing.
- **Architecture:** Lead architecture decisions across dApps. Review proposals, provide assessments, and ensure technical direction is sound and consistent.

## Weekly Cadence

- **CI/CD metrics review:** Run a script to pull merge queue success rates and durations from GitHub's API for the past week and current/prior month. Copy results into a Google Sheet tracking historical trends.
- **E2e failure summary:** Pull test execution data via a custom Currents SDK script. Create a new sheet in the centralized spreadsheet, run an agent to surface the top 5 flaky and top 5 failing tests, review each for root cause, assign owners, and post the summary to Slack.
- **PR reviews:** Review a large share of the team's PRs, confirming technical direction and enforcing best practices.
- **Technical document reviews:** Review proposals and design documents for new initiatives.
- **Mentoring — Ryan (weekly):** One-on-one with the team's most junior engineer. Probe for current tasks, surface gaps in planning or execution, and coach toward better engineering judgment.
- **Mentoring — Alejandro & Tom (occasional):** Similar format to Ryan sessions; less frequent.
- **Architecture sessions:** Present a challenge or topic, guide the group through design decisions, and help them build stronger engineering judgment.
- **1:1 with Bradford (weekly):** Covers team topics, processes, struggles, wins, priorities, and longer-term initiatives. A key input for understanding company direction and shaping quarterly focus.
- **Cross-team sync (rotating):** Weekly sync with one of the four frontend teams (CCIP dApps, Econ dApps, CCIP Integrations, "other" dApps + horizontal). Each team repeats every four weeks. Goal: stay aligned on engineering practices, architecture direction, and monorepo/tooling/e2e needs. Produce action items or plans from each session.

## Bi-Weekly Cadence

- **dApp guild:** Lead a knowledge-sharing meeting with my team (14 members) and the Econ team (6 members). Manage the topic backlog, prioritize discussion, provide assessments on all topics, collect action items, and follow up on completion.

## Monthly / Quarterly Rhythms

- **Quarterly planning:** Company-wide planning sets my focus for the quarter. I don't participate directly, but weekly 1:1s with Bradford frequently shape and refine what I should be working on — so in practice my quarterly direction is set collaboratively with my manager.

## Key Decisions

- **E2e backlog prioritization:** Which failing or flaky tests to tackle next, based on impact and fastest path to improvement.
- **Meeting agenda and direction:** What challenges and topics to bring to architecture sessions, the dApp guild, and cross-team syncs.
- **E2e ownership:** Who owns each failing test — the relevant dApp team or me (for infrastructure or cross-cutting issues).

## What I Produce

- **Weekly CI/CD report:** Success rate and run duration metrics tracked in Google Sheets.
- **Weekly e2e failure report:** Top flaky and failing tests with root cause analysis, posted to Slack.
- **PR and document reviews:** Ongoing feedback on code and technical proposals.
- **Code:** Improvements to CI/CD pipelines and e2e infrastructure.

## Reporting Structure

- Reports to: Bradford (Engineering Manager)
- Direct reports: None
