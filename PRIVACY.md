# Foxtopia Launcher Privacy Notice

Last updated: 16 October 2026

Foxtopia Launcher is published and operated by **Klausenn (Foxtopia)**. For questions about this notice or to request access, correction or deletion of Foxtopia data, contact **[iratakano99@gmail.com](mailto:iratakano99@gmail.com)**.

This notice covers the launcher and the Foxtopia services it connects to. Microsoft, game and content providers, and optional third-party software also process information under their own notices. Foxtopia Launcher is an independent application; it is not an official Minecraft product and is not approved by or associated with Mojang or Microsoft.

## Information stored on your device

The launcher stores your preferences, selected game profiles, account names and identifiers, saved skin entries, installed-content records and optional-content removal preferences. Game files, downloaded mods, resource packs, shaders and their own settings are stored locally. Validated settings backups can contain earlier preferences and skin entries. Removing a saved skin changes the active wardrobe; a previous local backup can still contain that entry.

Saved wardrobes are separated by account type and identifier. They are local records, not a cloud backup or a promise that skins will appear on another computer. Remembered Foxtopia sessions and Microsoft sign-in caches are encrypted using supported operating-system secure-storage facilities. Other settings, game files and saved skin images are not all encrypted. The embedded map can also create local web-cache data.

## Sign-in and server access

Microsoft sign-in takes place through Microsoft's device-code flow. Do not enter your Microsoft password into a Foxtopia form. The launcher receives authentication results and requests Minecraft profile and entitlement information from Microsoft/Minecraft services. A Minecraft access token is submitted to Foxtopia's account service to verify a Microsoft sign-in; that service uses it for verification rather than retaining it in its account database.

For separate Foxtopia username/password accounts, the account service receives the credentials over HTTPS and stores a salted password hash, account name and account type. Microsoft-linked records contain the account name and Microsoft/Minecraft profile identifier. The service also maintains hashed session identifiers and expiry times, and temporary game-admission proofs. These records authenticate the selected account and protect server access. A Foxtopia account does not provide a Minecraft license.

The game server processes player identifiers, connection information, gameplay and moderation records to run the world and its plugins. This can include inventories, locations, progress, chat and server logs. Server hosting infrastructure is provided by [Shockbyte](https://shockbyte.com/legal/privacy-policy). Network services can receive source IP addresses and other connection metadata even when those values are absent from an application report.

## Public chat, the map and skins

Server chat is public to other connected players and launcher users. Messages are displayed with player names; avoid posting private information. The island map presents server-world information and can show player names or positions when player markers are available. Public messages and images may also be copied by other users.

Looking up a skin by player name contacts Minecraft profile and texture services. Applying a Microsoft-account skin sends the selected image or texture request to Minecraft's skin service. Applying a separate Foxtopia skin sends the selection to the Foxtopia server integration and its SkinsRestorer provider. For a PNG that needs a signed skin, that integration sends the image and chosen model to **MineSkin** for generation. Generated skins and Minecraft texture URLs should not be treated as private file storage. Do not upload photographs or images containing personal information. MineSkin's processing is described in its [privacy notice](https://legal.inventivetalent.org/privacy/mineskin).

## Downloads and other services

Preparing a game profile contacts Minecraft/Mojang for game and Java runtime files, and the selected Fabric or NeoForge services for loader files. Searching for and downloading optional content contacts Modrinth and the content's approved download host. The requests include the search or file information needed to supply that content. Optional mods, resource packs and shaders are made by other authors and can have additional behavior outside this launcher's control.

GitHub hosts Foxtopia download assets, required-content manifests and branding images. The direct-download edition obtains application updates from GitHub; the Microsoft Store edition uses Microsoft Store for application updates. Choosing to send a report through a GitHub issue opens GitHub's issue form; an issue you publish there can be public. Merely previewing a report in the launcher or game does not publish a GitHub issue.

If Discord activity sharing is enabled and the Discord desktop client is running, the launcher/game sends activity to Discord through its local desktop connection. This can show launcher/game status, Minecraft version, loader and elapsed activity time to people allowed by your Discord settings. You can disable Foxtopia Discord activity in launcher settings; the game uses the preference selected when it starts.

Relevant provider notices: [Microsoft](https://www.microsoft.com/en-us/privacy/privacystatement), [Modrinth](https://modrinth.com/legal/privacy), [GitHub](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement), [Discord](https://discord.com/privacy). Their services and hosting can process requests outside your country. Contact the provider for information it controls independently.

## Diagnostics and support

After an unexpected game exit, the launcher automatically attempts to send a small failure summary to Foxtopia's report service: timestamp, process exit code, termination signal, crash flag and a generic reason such as an unexpected exit or insufficient memory. The automatic body excludes the game log, account name and account identifier. The report service adds a received timestamp and random report identifier. **Automatic failure summaries are currently always enabled; the launcher does not offer an opt-out for this automatic summary.** Network infrastructure can still process connection metadata.

Recent sanitized game output and a session summary are kept locally for troubleshooting. Sanitization removes known token, password and other sensitive patterns, but is not a guarantee that every private detail is removed. A manually submitted in-game bug report has a separate preview and confirmation step; including the recent log is your choice. Read the preview before sending. An exported diagnostic file stays on your device until you choose to share it.

If you email support, your email address, message and attachments are processed to handle the request. The support mailbox uses Gmail, whose hosting is covered by [Google's privacy policy](https://policies.google.com/privacy). Do not send passwords, access tokens, remembered-session files, government identification or a complete launcher data directory.

## Retention and your controls

- Local settings, game files, saved skins and backups remain on your computer until removed or replaced. Signing out, deleting a skin or uninstalling the application does not necessarily remove every local game file or backup. Contact support for help identifying Foxtopia files before removing them.
- Foxtopia remembered sessions expire after at most 30 days and can be revoked sooner. Expired sessions are rejected; cleanup of expired records is performed during account-service activity. Pending account-approval records become eligible for cleanup after seven days. Account registrations have no automatic inactivity-deletion period in the current service.
- The private report mailbox removes reports older than 30 days **when a new report is accepted**. It also removes older reports as needed to stay within 100 reports and 25 MiB. Because cleanup is activity-triggered, this is not a promise that every report disappears exactly 30 days after receipt.
- Server world data, operational logs, hosting backups and support correspondence have different operational and security purposes. No single automatic deletion period applies to all of them. Ask the Foxtopia operator about a particular record or deletion request; third-party providers control their own retention.

You can sign out, choose whether a supported session is remembered, manage your saved skins and optional content, disable Discord activity and decline to submit an optional report or log. Signing out revokes the relevant Foxtopia session when the service is reachable; it does not delete the registered server account or the world data associated with it.

To request access, correction or deletion, email **[iratakano99@gmail.com](mailto:iratakano99@gmail.com)** with your player name, account type and the scope of your request. Foxtopia may need to verify control of the account before disclosing or changing its data. Account deletion is handled through this contact rather than an in-app deletion button. The response will explain which Foxtopia records can be changed or removed and any necessary security, legal or technical limits. Do not send a password or identity document. Microsoft-account controls are available through [Microsoft account and privacy tools](https://account.microsoft.com/privacy).

## Security and changes

Configured account and report requests use HTTPS, and persisted remembered credentials use supported OS encryption. Access controls, bounded report storage and redaction reduce exposure; no system or redaction filter guarantees perfect security. Keep your Windows account and computer protected, especially when sharing a device.

This notice will be updated when Foxtopia's processing changes. The date above identifies the current revision. For support, privacy requests or a safety/content concern, use **[iratakano99@gmail.com](mailto:iratakano99@gmail.com)** and the [support instructions](SUPPORT.md).
