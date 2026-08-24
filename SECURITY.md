# LanternDrop Security

LanternDrop 0.1.0-preview is intended only for trusted private networks.

## Network model

- Transfer traffic uses local HTTP and is not encrypted.
- The random temporary session token reduces casual unauthorized access, but it does not protect against a capable attacker who can intercept or modify local-network traffic.
- Public, shared, or otherwise untrusted Wi-Fi is not recommended.
- The preview has not received an external security audit.

Use a trusted home LAN or personal hotspot, keep the QR code and session link private, and stop the temporary session when the transfer is finished.

## Reporting a vulnerability

Please use the repository's **Security** tab and GitHub private vulnerability-reporting option when it is available. If no private reporting form is available, open a minimal GitHub Issue requesting a private contact channel. Do not include exploit steps, tokens, private files, or other sensitive details in a public Issue.

General usage problems that do not expose a security weakness may be reported through GitHub Issues.
