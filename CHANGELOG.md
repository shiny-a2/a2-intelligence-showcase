# Changelog

## 2026-10-18 — Phase 1H

- Validated authenticated licensing and revocation flow in an isolated cross-service test.
- Added identity administration and account recovery safeguards with synthetic users.
- Expanded real-browser PWA and security gate evidence; staging remains pending.

## 2026-10-18 — Phase 1G isolated update

Added cross-language licensing checks and central web login with two-step verification and recovery. These changes make identity and entitlement behavior easier to validate before staging. Local tests used synthetic identities and disposable keys; no live deployment is claimed.

## 2026-10-18 — Phase 1F isolated update

Added a standalone identity foundation, a scoped signed entitlement contract, and a reviewed administration workflow that updates isolated runtime settings. This improves recoverability and makes integration behavior testable. Local tests covered revocation, concurrency, rollback, and the responsive PWA. No staging or production launch is claimed.
