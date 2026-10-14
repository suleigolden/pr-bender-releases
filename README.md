# PR Bender — Releases

This repository hosts the official release assets for [PR Bender](https://prbender.com) — an Offline and AI-assisted code review desktop app for GitHub pull requests.

> The source code is maintained in a private repository. This repo exists solely to distribute installable builds.

---

## Download

| Platform | Installer | Package Manager |
|----------|-----------|-----------------|
| macOS (Apple Silicon) | [PR-Bender-arm64.dmg](https://github.com/suleigolden/pr-bender-releases/releases/latest/download/PR-Bender-arm64.dmg) | Homebrew (see below) |
| Windows (x64) | [PR-Bender-Setup.exe](https://github.com/suleigolden/pr-bender-releases/releases/latest/download/PR-Bender-Setup.exe) | Scoop (see below) |
| Linux | — | Coming soon |

---

## Install via Package Manager

### macOS — Homebrew

```bash
brew tap suleigolden/pr-bender
brew trust suleigolden/pr-bender && brew install --cask pr-bender
```

To update later:

```bash
brew upgrade --cask pr-bender
```

### Windows — Scoop

```powershell
scoop bucket add pr-bender https://github.com/suleigolden/scoop-bucket-pr-bender
scoop install pr-bender
```

To update later:

```powershell
scoop update pr-bender
```

---

## What is PR Bender?

PR Bender is a desktop and online app that connects to your GitHub account and lets you:

- Do manual code reviews with a structured diff viewer online or offline
- Review pull requests with AI-assisted summaries and inline suggestions
- Track review history across your team's repos

Visit [prbender.com](https://prbender.com) to learn more and get started for free.

---

## Release Notes

Full changelogs for each version are in the [Releases](https://github.com/suleigolden/pr-bender-releases/releases) tab.

---

## Support

For bug reports or feature requests, reach out via [prbender.com](https://prbender.com/contact).
