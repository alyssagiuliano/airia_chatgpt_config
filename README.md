# Airia Configuration Guides — ChatGPT Suite

![Airia Configuration Guides — ChatGPT Suite](images/4.png)

This repository contains setup guides for connecting the ChatGPT Suite to the Airia Gateway.

## Guides

**ChatGPT Desktop (Work and Codex), and Codex CLI**
- [ChatGPT Desktop and Codex CLI (macOS)](ChatGPT%20Desktop%20and%20Codex%20CLI%20%28macOS%29.md) — configure Codex inference in ChatGPT Desktop (Work and Codex) and Codex CLI to route through the Airia AI Gateway on mac devices.
- [ChatGPT Desktop and Codex CLI (Windows)](ChatGPT%20Desktop%20and%20Codex%20CLI%20%28Windows%29.md) — configure Codex inference in ChatGPT Desktop (Work and Codex) and Codex CLI to route through the Airia AI Gateway on Windows devices.
- [ChatGPT Desktop and Codex CLI OAuth Passthrough](ChatGPT%20Desktop%20and%20Codex%20CLI%20OAuth%20Passthrough.md) — route the same surfaces through the Airia AI Gateway while keeping your own ChatGPT sign-in, so requests run on your ChatGPT plan instead of an Airia-managed key.

## Helpful Codex Scripts

**Config Files — macOS**
- View the Codex config: `cat ~/.codex/config.toml`
- View the Codex environment file: `cat ~/.codex/.env`

**Config Files — Windows (PowerShell)**
- View the Codex config: `Get-Content "$env:USERPROFILE\.codex\config.toml"`
- View the Codex environment file: `Get-Content "$env:USERPROFILE\.codex\.env"`
