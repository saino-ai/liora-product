# Installation and verification

Liora is not distributed as a public installer in this repository.

## Delivery

After purchase confirmation, SAINO provides the purchaser with a time-limited private download link, setup guidance, the expected filename, and verification information.

Do not download Liora installers from unofficial mirrors, public file-sharing links, or third-party repositories.

## Verify the download

The current `1.3.0-beta.1` Limited Beta installer is:

```text
Filename: Liora-Setup-1.3.0-beta.1.exe
SHA-256: 0C15D1AC2A5C81B6B671860C7F8069F21614641AE41F8758B7AAEA0A49FC0FD1
```

In PowerShell, calculate the hash with:

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath ".\Liora-Setup-1.3.0-beta.1.exe"
```

Continue only when the result exactly matches the checksum supplied by SAINO for the downloaded version.

## SmartScreen

The current installer is not code signed, so Windows SmartScreen may display an unrecognized-app warning. This warning does not by itself prove that a file is malicious or safe. Verify the source, filename, and SHA-256 before deciding whether to run it.

Do not disable Microsoft Defender, SmartScreen, or other security tools globally. Organisation-managed PCs may block unsigned applications by policy; obtain administrator approval before purchase or installation.

## Initial setup

Liora includes setup guidance, but local AI models and optional providers are installed separately. Start with one supported local provider, verify basic chat, and then add coding agents, voice, generation, MCP, or automation features one at a time.
