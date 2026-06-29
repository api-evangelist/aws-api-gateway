# Programmatic API Onboarding — AWS API Gateway

A single-file, zero-dependency Node.js (18+) CLI that reproduces SoundCloud's
`sc-api-auth.mjs` pattern for AWS API Gateway: register an application / obtain credentials
programmatically instead of clicking through a dashboard, so agents and developers
can onboard at the command line.

- Script: [`aws-api-gateway-api-auth.mjs`](aws-api-gateway-api-auth.mjs)
- Run `node aws-api-gateway-api-auth.mjs --help` for usage and the required environment variables.
- Story / rationale: https://apievangelist.com/2026/07/04/aws-api-gateway-and-the-self-serve-onboarding-it-refuses/

Part of the API Evangelist "Programmatic API Onboarding for the Agentic Moment" series.
