# Current Projects

## TON Connect Playwright Model

**Description:** Building a Playwright wallet model for TON Connect to enable e2e test coverage of TON transactions in CCIP dApps.
**Status:** In Progress (~40%)
**My Role:** Solo — designing and implementing the full model.
**Key Collaborators:** None directly. Marek (CCIP dApps) and the CCIP Integrations team are depending on this.
**What Done Looks Like:** CCIP Explorer has an e2e test covering TON Connect wallet connection and proposing a TON transaction for manual message execution. All methods of the abstract wallet interface are implemented.
**Priority:** Highest
**Notes:** TON Connect support already exists in the dApps but has no e2e coverage; occasional regressions on TON transactions have been detected.

## Slush (Sui Wallet) Playwright Model

**Description:** Building a Playwright wallet model for Slush (Sui wallet), following the same pattern as TON Connect.
**Status:** Not Started
**My Role:** Solo.
**Key Collaborators:** None directly. The CCIP Integrations team depends on this.
**What Done Looks Like:** CCIP Explorer can use the model for e2e tests and all wallet interface methods are implemented.
**Priority:** High
**Notes:** After Slush, the next wallet model in the queue is Tron — lower urgency than both Slush and the e2e cross-cutting failures initiative.

## E2e Cross-Cutting Failures

**Description:** Addressing the most prevalent e2e failures that are infrastructure or cross-cutting in nature, not tied to a specific dApp.
**Status:** Not Started (two tickets prioritized)
**My Role:** Solo.
**Key Collaborators:** None.
**What Done Looks Like:** Two active tickets resolved — (1) Chromium profile teardown failure no longer causes test failures; (2) Phantom EVM wallet is no longer incorrectly detected on app load when the user has chosen Phantom Solana.
**Priority:** Medium
**Notes:** Open-ended initiative; these two tickets are the current prioritized slice.
