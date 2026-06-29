# Programmatic API Onboarding — PayPal

A single-file, zero-dependency Node.js (18+) CLI that reproduces SoundCloud's
`sc-api-auth.mjs` pattern for PayPal: register an application / obtain credentials
programmatically instead of clicking through a dashboard, so agents and developers
can onboard at the command line.

- Script: [`paypal-api-auth.mjs`](paypal-api-auth.mjs)
- Run `node paypal-api-auth.mjs --help` for usage and the required environment variables.
- Story / rationale: https://apievangelist.com/2026/09/06/paypal-client-credentials-dashboard-app/

Part of the API Evangelist "Programmatic API Onboarding for the Agentic Moment" series.
