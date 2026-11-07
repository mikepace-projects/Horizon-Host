---
layout: default
title: Horizon Privacy Policy
permalink: /privacy/
---
# Horizon Privacy Policy

Effective date: 7 November 2026

This policy covers the Horizon iPhone and iPad app and its connections to Horizon Hosts. Horizon is provided by Michael Pace ([mikepace-projects](https://github.com/mikepace-projects)). “We” refers to the Horizon maintainers, not the operator of a computer you connect to.

## How Horizon works

Horizon is a client for computers you choose to pair with. Your files stay on those computers unless you open, edit, cache, download, export, or share them. We do not operate a Horizon cloud service that receives your workspace files. A Horizon account is not required.

## Data the app processes

- **Workspace content:** file and folder names, paths, document contents, images, tables, change history, Git information, and other files you choose to access. Horizon transfers these between your device and your paired Hosts to display and edit your work and perform operations you request.
- **Connections and preferences:** Host names and addresses, Host and client identifiers, pairing credentials, approved folders, Projects, Categories, and app settings. These let Horizon authenticate connections, remember your choices, and organize your work. Pairing credentials on iOS are stored in the device-only Keychain.
- **Local copies:** opened content and file lists may be cached on your device. Unsaved text and workbook edits are stored separately to help preserve your work if iOS closes the app. Imports and exports can create temporary file copies.
- **Camera and selected media:** if you choose Scan QR Code, Horizon requests camera permission to read a pairing code. Horizon does not send camera images to us or retain a camera recording. You can paste a code instead. Horizon accesses files or media you select for import and can save media to Photos when you choose that action and grant permission.
- **Support information:** if you contact us, we receive the message, contact or GitHub account information you provide, and any diagnostics or attachments you choose to send. Do not send passwords, pairing codes, API keys, or confidential files.

The app does not include advertising, cross-app advertising tracking, or a developer-operated analytics or automatic crash-upload service. We do not sell personal information or use workspace content to train AI models.

## Where information goes

Your requests and workspace content are sent to Hosts you authorize. Shared Project and Category information, including names, folder paths, Git remote addresses, and Host icons, can be copied to other paired Hosts and clients sharing those Hosts. Unpairing a device does not erase information already copied to another Host or client. If you configure Host Sync, selected Skills, agent configuration, and Project Secrets are copied between the participating computers you select.

Horizon connections use HTTPS through your Tailscale network. Tailscale is a separate service you configure; its account and network handling are described in [Tailscale's privacy policy](https://tailscale.com/privacy-policy/). A Host's owner or administrator can access data stored on that Host. Pair only with computers and networks you trust.

Git operations, GitHub authentication on a Host, agent configuration, external links, remote images, and development-server previews can involve services you choose. Those services may receive content and connection information needed for the action and apply their own privacy policies. Previewed websites can use their own cookies or storage. Horizon does not add an advertising tracker to them. Configuring an AI agent or its integrations on your computer may affect what that agent later sends to its providers; review its settings and provider policies before using sensitive content.

We do not provide workspace information to analytics, advertising, or AI-processing partners. If we engage a provider to process personal information on our behalf, we require protection consistent with this policy and applicable requirements. Independently selected services and user-operated Hosts are under your control and are not a Horizon cloud-storage service.

The public documentation and support pages are hosted by GitHub. Visiting them or opening an issue is subject to [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement), including its handling of web requests and account information. Information posted in public issues is public.

## Retention, deletion, and your choices

- **Cached files:** use Horizon's Settings → Storage → Clear to remove eligible cached content and temporary transfer copies. iOS may also remove cache data under storage pressure. Clear does not delete unsaved edits.
- **Unsaved work:** save or discard pending edits to remove their recovery copies. Removing the app deletes its app-container data; exports, Host files, backups, and device Keychain items are separate.
- **Host access:** use Unpair while the Host is reachable to revoke this device's access. If the Host is offline and you only remove it from this device, revoke its credential on the Host separately. Removing the app alone is not a reliable way to revoke a Host credential.
- **Original and shared data:** files remain on your Hosts until you delete them. Shared Project metadata and deletion records can remain in other clients or Hosts without an automatic expiry. Remove data from those computers and any backups separately. Copies you export or share are controlled by their destination.
- **Permissions:** revoke camera or Photos permission in iOS Settings. Stop using an optional integration or disconnect its account to end future access through that service.
- **Support requests:** we keep information you send for as long as needed to address the request, resolve related issues, or meet applicable legal obligations. You can request access, correction, or deletion through the contact below. Public GitHub content and service backups remain subject to GitHub's controls and retention. We cannot delete files on your computers or data controlled by independently chosen services.

Your connected services and backups may store data in other countries under their own arrangements. Horizon does not choose a developer-operated cloud region for your workspace files.

## Changes and contact

We will update this page and its effective date when this policy changes. For privacy questions or requests, email Michael Pace at [growth@signalrankmedia.com](mailto:growth@signalrankmedia.com). You can also [open a public issue](https://github.com/mikepace-projects/Horizon-Host/issues/new) for a non-sensitive question. Do not post private information in public issues.
