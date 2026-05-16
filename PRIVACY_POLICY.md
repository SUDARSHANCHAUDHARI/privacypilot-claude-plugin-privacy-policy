# PrivacyPilot Privacy Policy

**Effective Date:** May 17, 2026
_Last updated: May 17, 2026_
**Version:** 1.0.0

PrivacyPilot ("we," "our," or "us") is a Claude Code plugin for Android developers that scans local Android manifest and Gradle files, detects permissions and SDKs, generates privacy-policy content, audits policy gaps, and can help prepare GitHub Pages deployment steps. This Privacy Policy explains what information the plugin can access locally, how it is used, and the choices you have. By installing or using PrivacyPilot, you agree to the practices described below.

## Information We Collect

### Location Data
- **Not collected**: PrivacyPilot is a Claude Code plugin, not an Android app or mobile service. It does not request, collect, infer, store, or share device location data.
- **No background location**: The plugin does not run a mobile background location service and does not use GPS, Wi-Fi, Bluetooth, or cell-tower location signals.

### Account Information
- **No plugin account**: PrivacyPilot does not require a separate account, login, or hosted user profile.
- **Local developer settings**: The plugin may use developer details you enter in Claude Code settings or local project configuration, if relevant to the command you run.
- **GitHub identity**: If a workflow references GitHub repositories, it uses the repository URLs or usernames you provide locally. PrivacyPilot does not operate a separate identity service.

### Device Information
- **Local project files**: Android manifest files, Gradle files, version catalogs, package names, app names, SDK names, permission declarations, and existing privacy-policy text that you ask the plugin to scan or audit.
- Developer details entered in Claude Code plugin settings, such as name, company, email, GitHub username, and country.
- **Environment information**: The plugin may inspect local tool availability, such as Git, Java, Gradle, shell commands, or Claude Code plugin settings, only to perform requested local workflows.
- **No telemetry**: PrivacyPilot does not collect analytics, device identifiers, advertising IDs, crash reports, or usage telemetry.

## How We Use Your Information

### Location Sharing
- **Not applicable**: PrivacyPilot does not provide location sharing and does not share your location with anyone.
- Any location-related Android permissions in projects you inspect are treated only as local project text if they appear in files you ask Claude Code to analyze.

### Account Management
- There is no hosted PrivacyPilot account to create, manage, or delete.
- Local developer settings are used only to avoid repeated prompts and to generate project-specific output when you run commands.

### Service Improvement
- PrivacyPilot does not send usage data, diagnostics, or generated output to a SudarshanTechLabs server.
- Improvements happen through local plugin updates, source-code changes, documentation updates, and issue reports you choose to file manually.
- We do not run ads and do not sell, rent, or monetize your data to third parties.

## Storage and Retention

### Data Storage
- PrivacyPilot may generate local privacy-policy files such as `privacy-policy/index.html`, markdown policy drafts, or deployment instructions. It does not create a remote account or remote database.
- All plugin-accessed content remains in your local Claude Code session, local filesystem, or the project repository you are working in.
- No plugin data is stored on a SudarshanTechLabs backend server.

### Data Retention
- Local settings remain until you delete them, reset Claude Code plugin settings, remove the project config, or uninstall the plugin.
- Generated files remain in your local project until you delete or commit them.
- Claude Code itself may retain conversation or workspace context according to Anthropic/Claude Code settings and policies; PrivacyPilot does not control that retention.

### Data Security
- PrivacyPilot is designed for local-first use inside Claude Code.
- Sensitive generated content, such as signing snippets, local config, or project metadata, should be reviewed before committing to git.
- The plugin does not intentionally transmit plugin-accessed data to external servers.

## Data Sharing

### Family Groups
- **Not applicable**: PrivacyPilot does not include family groups, groups, teams, social sharing, or location-sharing communities.
- Data is not shared with family members or other users by the plugin.

### Third Parties
- PrivacyPilot does not send scanned manifest, Gradle, SDK, or policy content to Firebase, Google Cloud, analytics services, advertising networks, or data brokers.
- If you choose to publish generated policy files to GitHub Pages, GitHub hosts the published page and GitHub’s own terms and privacy policies apply to that hosting.
- See [Anthropic's Privacy Policy](https://www.anthropic.com/privacy) for Claude/Claude Code data practices.
- See [GitHub's Privacy Statement](https://docs.github.com/site-policy/privacy-policies/github-general-privacy-statement) for GitHub-hosted repositories or GitHub Pages that you choose to use.

We do **not** share your data with:
- Advertising networks
- Data brokers
- Analytics services operated by this plugin
- A SudarshanTechLabs backend server

## Permissions Used

### Required Permissions

* **Local workspace file access**: Required so Claude Code and PrivacyPilot can read or update project files that you explicitly work on.
* **Claude Code plugin configuration access**: Required to read plugin settings or command configuration when a command needs it.
* **Command-specific local tool access**: Read access to local Android manifest, Gradle, version-catalog, and privacy-policy files you ask the plugin to scan. Write access to local generated policy files only when you run generation/update workflows. Optional Git/GitHub Pages actions only when you explicitly approve deployment-related steps.

### Optional Permissions

* **Network access**: Not required for normal local policy behavior, except for command-specific tasks you explicitly request, such as downloading a local tool, viewing documentation, or publishing a GitHub Pages repository.
* **Git/GitHub access**: Optional and used only when you explicitly ask for repository or publishing workflows.
* **Shell command execution**: Optional and subject to Claude Code/macOS approval flows when commands need to run local tools.

## Your Rights and Controls

### Location Sharing Control
- PrivacyPilot does not collect or share location data.
- If you inspect an Android project with location permissions, you control that project and its privacy disclosures separately.

### Account Management
- There is no PrivacyPilot hosted account.
- You can remove local plugin settings, project config, generated files, and the plugin itself at any time.

### Data Access
- You can inspect all files generated by PrivacyPilot in your local project.
- You can inspect plugin settings in Claude Code settings where applicable.
- You can review source code and documentation in the plugin repository.

### GDPR Rights (EU Users)
If you are in the European Union, you may have additional rights regarding personal data:
- **Right to Access**: Request a copy of personal data we may hold
- **Right to Rectification**: Correct inaccurate data
- **Right to Erasure**: Request deletion of data
- **Right to Restrict Processing**: Limit how data is used
- **Right to Data Portability**: Receive data in a portable format
- **Right to Object**: Object to certain types of processing

Because PrivacyPilot does not operate a hosted backend or collect plugin telemetry, most plugin-related data is under your direct local control. For questions, contact us using the methods in the Contact Us section.

### Permissions
- You can disable or uninstall PrivacyPilot in Claude Code.
- You can delete generated files from your project.
- You can deny local command execution when Claude Code asks for approval.
- You can avoid GitHub publishing workflows unless you explicitly want to publish generated files.

## Children's Privacy

- PrivacyPilot is a developer tool and is **not intended for children under 13**.
- We do not knowingly collect data from children under 13 through this plugin.
- If you believe a child has provided personal information through plugin-related communication, contact us to request deletion.

## Security

- PrivacyPilot follows a local-first design and does not intentionally transmit plugin-accessed files to a SudarshanTechLabs server.
- Review generated output before committing, publishing, or sharing it.
- Do not commit secrets, private keys, keystores, tokens, local config, or signing material.
- Keep Claude Code, Git, Java, Gradle, and other local tools updated.
- Use git ignore rules for machine-specific and secret files.

## Changes to This Policy

We may update this Privacy Policy to reflect new plugin features, legal requirements, or changes in our practices. Significant changes will be:
- Noted in plugin release notes or changelog when applicable
- Updated in this repository
- Published with a new "Last updated" date

The "Last updated" date at the top of this policy indicates when revisions occurred. Continued use of the plugin after changes constitutes acceptance of the updated policy.

## Contact Us

If you have questions about this Privacy Policy, wish to request deletion of any information you sent us directly, or have privacy concerns:

* **GitHub Repository:** https://github.com/SUDARSHANCHAUDHARI/privacypilot-claude-plugin-privacy-policy
* **Email:** sunny.sudarshan@gmail.com
* **Plugin Repository:** https://github.com/SUDARSHANCHAUDHARI/PrivacyPilot
* **Live Privacy Policy:** https://sudarshanchaudhari.github.io/privacypilot-claude-plugin-privacy-policy/

We will respond as quickly as possible, typically within 48 hours.

## Data Deletion

### How to Delete Your Account:
There is no hosted PrivacyPilot account. You have multiple options to remove plugin-related local data:

#### Option 1: In-App Deletion
1. Open Claude Code
2. Disable or uninstall the PrivacyPilot plugin
3. Remove any PrivacyPilot plugin settings from Claude Code settings
4. Delete any generated files or local configuration from the project where you used the plugin

#### Option 2: Email Deletion Request
Send an email to: **sunny.sudarshan@gmail.com**
- Subject: "PrivacyPilot Privacy/Data Deletion Request"
- Include: What information you believe you sent to us directly
- We'll review and respond within 48 hours

#### Option 3: Web Deletion
PrivacyPilot does not provide a hosted web account deletion portal because it does not create hosted user accounts.

### What Gets Deleted:
- Local plugin settings you remove from Claude Code
- Local generated files you delete from your project
- Local project configuration files you delete
- Any direct support-request information you ask us to delete, where legally and technically possible

### Data Retention After Deletion:
- **Immediate:** Local files/settings are removed when you delete them from your machine
- **Support email:** Support messages may remain in email systems unless you request deletion and deletion is legally/technically possible
- **No hosted plugin backend:** There is no PrivacyPilot server database to delete from

1. Delete generated privacy-policy files from your local project.
2. Remove PrivacyPilot developer settings from Claude Code plugin settings.
3. Uninstall the plugin from Claude Code.
4. If you used the plugin to prepare a GitHub Pages deployment, remove the deployed repository/page manually from GitHub if you no longer want it published.

## Firebase and Google Services

- PrivacyPilot does not use Firebase Authentication, Firebase Realtime Database, Firebase Analytics, Firebase Crashlytics, Google Maps, AdMob, or Google Location Services as part of the plugin privacy-policy workflow.
- If PrivacyPilot helps inspect or generate disclosures for an Android app that uses Firebase or Google services, that information is read from your local project files and belongs to that Android app's own privacy policy.
- See [Google's Privacy Policy](https://policies.google.com/privacy) for Google's data practices when you independently use Google services.

## About PrivacyPilot

PrivacyPilot is a Claude Code plugin for Android developers that scans local Android manifest and Gradle files, detects permissions and SDKs, generates privacy-policy content, audits policy gaps, and can help prepare GitHub Pages deployment steps.

Main commands include: `/privacypilot:generate`, `/privacypilot:audit`, `/privacypilot:github-page`, `/privacypilot:update`.

The plugin is intended to run inside Claude Code and operate on local project files under your control.

## Recent Updates (Version 1.0.0 - May 17, 2026)

- Initial plugin privacy policy aligned with the shared SudarshanTechLabs privacy policy structure.
- Clarifies local-only scanning of Android manifests, Gradle files, SDK disclosures, policy generation, and optional GitHub Pages deployment workflow.
