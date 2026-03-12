# Helm ADE Releases

Distribution repository for [Helm ADE](https://github.com/mdmagnuson-creator/helm-ade-macos) — the native macOS Agentic Development Environment.

## What's Here

- **`appcast.xml`** — Sparkle auto-update feed for macOS
- **`releases/`** — DMG installer files
- **`index.html`** — Landing page (served via GitHub Pages)

## For Testers

1. Download the latest DMG from [Releases](https://github.com/mdmagnuson-creator/helm-ade-releases/releases/latest)
2. Open the DMG and drag Helm ADE to Applications
3. Launch Helm ADE — it will check for updates automatically via Sparkle

## Auto-Updates

Helm ADE checks for updates automatically using [Sparkle](https://sparkle-project.org/). You can also check manually via **Helm ADE → Check for Updates...** in the menu bar.

**Appcast URL:** `https://mdmagnuson-creator.github.io/helm-ade-releases/appcast.xml`

## Automated

This repository is updated automatically by the [macOS Release workflow](https://github.com/mdmagnuson-creator/helm-ade-macos/actions/workflows/macos-release.yml). Do not edit files manually.
