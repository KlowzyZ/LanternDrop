# Changelog

## 1.1.0 — UI & Messaging Polish

### Changed

- Removed visible GitHub references from the About page and update status messages for a cleaner product experience.
- Refined Dark and Light themes for deeper contrast and a more modern appearance.
- Softened control radii, improved button and card padding, and polished navigation spacing.
- Tightened sidebar logo treatment and overall window spacing.
- Improved Home page visual hierarchy and action-card balance.

### Notes

- Transfer engine, session security, and privacy guarantees are unchanged from 1.0.0.
- Update checks still work the same way; only user-visible wording was cleaned.

## 1.0.0 — First Stable Release

### Included

- The complete hardened LanternDrop send/receive feature set from the public preview.
- Stable-channel update discovery that ignores future prerelease builds.
- Refreshed Windows x64 executable, ZIP package, documentation, and SHA-256 checksums.

### Known limitations

- Windows 11 x64 is the primary target.
- A trusted private LAN is required; local HTTP traffic is not encrypted.
- The executable is unsigned and may trigger Microsoft Defender SmartScreen.
- Windows Firewall may require a user decision for Private-network access.
- LanternDrop has not received an external security audit.
- Automatic download or self-installation of updates is not included.

## 0.1.0-preview — Initial Preview

### Included

- Send files and plain text from Windows to a phone.
- Receive files and plain text from a phone.
- QR-based temporary sessions over the selected local network.
- Streaming uploads and downloads, including HTTP Range downloads.
- Collision-safe receive behavior.
- Upload cancellation and partial-file cleanup.
- Automatic session expiration and manual stop.
- Dark and Light themes.
- Reduce Motion.
- Per-transfer progress, bytes, speed, and activity.
- Optional update checks.
- No cloud relay, account, telemetry, analytics, or phone installation.

### Known limitations

- Windows 11 x64 is the primary target.
- A trusted private LAN is required.
- Local HTTP transfer traffic is not encrypted.
- The unsigned preview executable may trigger Microsoft Defender SmartScreen.
- Windows Firewall may require a user decision for Private-network access.
- The preview has not received an external security audit.
- Stable licensing terms are not finalized.
- Automatic download or self-installation of updates is not included.
