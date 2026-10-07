# Security

AgentShield is a defensive testing tool. Use it only on agents you own or are authorized to test.

- Secrets live in `.env` only and are never committed.
- Target agents run in an isolated process with no access to real credentials.
- Generated attacks are stored locally and never sent to third parties other than the configured model provider.

Report vulnerabilities by opening a private security advisory on this repository.
