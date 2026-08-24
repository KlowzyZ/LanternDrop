# LanternDrop Privacy

LanternDrop is designed for direct local transfer with minimal data collection.

- No account is required.
- No analytics or telemetry are collected.
- File and text transfers remain on the user-selected local network.
- Transfer data is not uploaded to GitHub or another cloud service.
- Settings remain local to the Windows profile.

## Update checks

LanternDrop contacts the GitHub Releases API only when a user manually checks for updates or enables automatic checks. Automatic checks are disabled by default.

Like any ordinary internet request, GitHub can observe network metadata such as the public IP address from which the request arrives, request time, and the LanternDrop User-Agent. The update request does not include transferred content, filenames, local paths, clipboard text, phone data, session tokens, an advertising identifier, analytics, or telemetry.

Update checks do not change the local-only transfer path. LanternDrop remains usable for LAN transfers when the internet or GitHub is unavailable.
