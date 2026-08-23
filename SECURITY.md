# Security Policy

## Project status

This package is a legacy GPT-3-era wrapper and is not recommended for new integrations. Its documented endpoints, models, dependencies, and assumptions may be obsolete.

## Reporting a vulnerability

Do not disclose vulnerabilities, API keys, request logs, prompts, or response data in a public issue or pull request.

Use this repository's private vulnerability reporting page:

https://github.com/Fiskers/openai-api/security/advisories/new

Include the affected commit or package version, reproduction steps, impact, and a minimal proof of concept with all credentials and personal data removed.

## API keys

Load API keys from environment variables or a dedicated secret manager. Never commit keys to source files, tests, fixtures, notebooks, lockfiles, or logs. Revoke and replace any key that may have been exposed.

## Supported versions

No version is currently supported for production use. A maintained release would require migration to current API endpoints, dependency upgrades, tests, and a fresh security review.
