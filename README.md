# AgentDock downloads

Compiled installers for **AgentDock Pro (Beta)**. This repository contains binaries only; the AgentDock source is not published here.

## Current release: `v0.1.6-dev.4-beta` (Beta, unsigned)

| Platform | File | Size (bytes) | SHA-256 |
|---|---|---|---|
| Windows 10/11, x64 | `AgentDock-0.1.6-dev.4-win-x64.exe` | 368204341 | `1fab060ed54b13c08f2209145ac2e7758f9ac143505d9918fc71d48cecbfc6e5` |
| macOS, Apple Silicon (arm64) | `AgentDock-0.1.6-dev.4-mac-arm64.dmg` | 465734773 | `e40f682c124c903fa49421441d38891744aab3853492572e811cd4295b0fc926` |

Internal version **0.1.6-dev.4**, built from source commit `5cd5577`. Check your download against `SHA256SUMS.txt`.

## Beta and unsigned-build warnings

- These are **Beta** builds and are **not code-signed or notarised**.
- **Windows:** SmartScreen will warn that the publisher is unknown. Choose *More info* then *Run anyway*.
- **macOS:** Gatekeeper will reject the app on first launch. Right-click (or Control-click) the app and choose *Open*, then confirm.
- Unsigned builds do not auto-update. Download new builds from this page.
- **Intel Macs:** the Apple Silicon build does not run on Intel Macs. It is not offered here for Intel.

## Requirements

- Windows 10 or 11 (64-bit), or macOS on Apple Silicon.
- Git, for reviewing and reverting changes.
- Your own coding-agent CLIs/accounts (Claude Code, Codex, etc.) as configured in the app.

## Pro features

Pro features are unlocked only by signing in with a Sarja account that has an active AgentDock Pro entitlement. These release builds contain no developer entitlement overrides. See https://agdc.dev for plans.

Downloads and release information: https://agdc.dev/download
