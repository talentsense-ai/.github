# Security Policy

## Supported Versions

TalentSense is under active development. Security fixes are applied to the `main` branch.
If you are running a fork or a deployed instance, please pull the latest changes.

## Reporting a Vulnerability

Please **do not** report security vulnerabilities through public GitHub issues.

Instead, use one of these private channels:

1. **GitHub Private Vulnerability Reporting**

- Go to the repository page → **Security** → **Report a vulnerability**
- Provide the details described below

2. **If private reporting is not available**

- Open a GitHub Discussion with minimal details (no exploit steps), and request a private channel
- Or contact the maintainers via a private communication channel agreed in advance

## What to Include

To help us triage quickly, include:

- A clear description of the vulnerability and its impact
- Affected component(s) (frontend, backend, infra, deployment)
- Steps to reproduce (proof-of-concept if possible)
- Any relevant logs, screenshots, or request/response samples
- Version/commit SHA or environment details (local vs deployed)

Please **remove secrets** (API keys, tokens) and **personal data** from your report.

## Scope

This policy applies to vulnerabilities in:

- The TalentSense codebase and configuration
- Deployment manifests and CI/CD workflows
- Dependencies and supply-chain concerns where actionable

## Disclosure

We will investigate reports responsibly and take reasonable steps to mitigate valid issues.
Please allow us to coordinate a fix before any public disclosure.
