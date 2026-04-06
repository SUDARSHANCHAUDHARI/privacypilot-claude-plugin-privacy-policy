# PrivacyPilot — Privacy Policy

This repository hosts the official privacy policy for the **PrivacyPilot** Claude Code plugin.

**Live privacy policy:** https://sudarshanchaudhari.github.io/privacypilot-claude-plugin-privacy-policy/

---

## About PrivacyPilot

**PrivacyPilot** is a Claude Code plugin for Android developers. It automatically scans your `AndroidManifest.xml` and Gradle files to detect every permission and third-party SDK, then generates a fully compliant HTML privacy policy ready to deploy to GitHub Pages — all from a single command inside Claude Code.

### What It Does

1. Reads `AndroidManifest.xml` — detects every `<uses-permission>` and maps it to the data it collects
2. Reads `build.gradle` / `libs.versions.toml` — detects AdMob, Firebase, Crashlytics, Facebook SDK, Adjust, AppsFlyer, and more
3. Generates a complete HTML privacy policy covering GDPR, CCPA, COPPA, and Google Play Data Safety requirements
4. Deploys it to GitHub Pages at `https://[username].github.io/[appname]-privacy-policy/`

### Commands

| Command | Description |
|---|---|
| `/privacypilot:generate` | Scan manifest + Gradle and generate a complete privacy policy |
| `/privacypilot:audit` | Audit an existing policy for compliance gaps |
| `/privacypilot:github-page` | Deploy the generated policy to GitHub Pages |
| `/privacypilot:update` | Update an existing policy when permissions or SDKs change |

### Compliance Coverage

- **Google Play** — Data Safety form alignment
- **GDPR** — EEA data subject rights, legal basis, data transfers
- **CCPA** — California consumer rights
- **COPPA** — Children's privacy statement

---

## Install

```bash
/plugin marketplace add SUDARSHANCHAUDHARI/PrivacyPilot
/plugin install privacypilot@privacypilot
```

When you enable the plugin, Claude Code prompts you for your developer details once (name, company, email, GitHub username, country). These are stored globally in your Claude Code settings and used automatically in every project.

---

## Plugin Repository

Full source code, documentation, and issue tracker:
**https://github.com/SUDARSHANCHAUDHARI/PrivacyPilot**

---

## Privacy Policy for This Plugin

PrivacyPilot does **not** collect, transmit, or store any user data. All file reading and policy generation happens locally on your machine. Your developer details are stored only in your local Claude Code settings.

The full privacy policy for this plugin is available at:
**https://sudarshanchaudhari.github.io/privacypilot-claude-plugin-privacy-policy/**

---

## Author

**SUDARSHANCHAUDHARI** — [github.com/SUDARSHANCHAUDHARI](https://github.com/SUDARSHANCHAUDHARI)
SudarshanTechLabs | sudarshantechlabs@gmail.com

## License

MIT
