# Privacy and security

## Local data

Liora stores conversations, memories, projects, settings, and logs in its local Windows application data. Backups created by the user may contain the same information and should be protected accordingly.

## External connections

Data may leave the PC when the user explicitly uses a connected service, including:

- cloud AI or coding-agent services;
- web-search providers;
- MCP servers and plugins;
- Git hosting and remote development services;
- ComfyUI or another generation endpoint on a different device;
- OAuth-connected services; and
- feedback or support channels.

Review each provider's terms, privacy policy, account permissions, and fees before enabling it. Do not send confidential files, credentials, personal information, or proprietary source code unless the selected destination is authorized to receive them.

## Credentials

API keys, access tokens, passwords, OAuth secrets, and private keys should never be pasted into chats, screenshots, logs, public issues, or this repository. Use the designated settings and operating-system credential storage offered by the installed version.

## MCP, plugins, and PC operation

MCP servers, plugins, terminal commands, and PC-operation tools can read files, modify projects, run commands, or interact with external systems depending on their permissions. Enable only trusted components and review their scope before use.

Financial transactions and transfers should remain confirmation-gated. Keep backups and Git history for important work, and review diffs and test results before accepting AI-generated changes.

## Reporting security issues

Follow [SECURITY.md](../SECURITY.md). Do not disclose vulnerabilities or sensitive logs through public GitHub issues.
