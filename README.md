# Disciple Maker Agent Platform releases

Distribution repository for the macOS application. Application source belongs in the separate private `ChrisChasm/disciple-maker-agent-platform` repository.

This repository is public. Installers and updates require no GitHub sign-in; application source remains private. The current release is **0.1.3**, Developer ID signed and Apple notarized.

Each published release contains the signed and notarized application ZIP, `latest-mac.yml` for the native macOS updater, `release.json` with checksums and the exact application and Hermes source revisions, and release notes.

Hermes is bundled at a tested, pinned revision. Engine upgrades ship only as part of an evaluated Disciple Maker Agent Platform release. Never put source documents, `.env` files, Apple credentials, provider keys, or maintainer GitHub tokens in distribution assets.

Before a release is considered ready, verify installation and a complete native version-to-version update, including persistence of profiles, conversations, and settings.

## Download and install

[Download Disciple Maker Agent Platform 0.1.3](https://github.com/ChrisChasm/disciple-maker-agent-platform-releases/releases/download/v0.1.3/Disciple-Maker-Agent-Platform-0.1.3-mac-arm64.zip)

Requires an Apple Silicon Mac running macOS 13 or newer. The download is about 1.8 GB and expands to approximately 5 GB. Expand the ZIP and move **Disciple Maker Agent Platform.app** into Applications. Open it, connect your model, and choose a helper. Accounts and models are not included.

The native updater checks this repository for future releases. Hermes engine self-updates are disabled; engine upgrades arrive inside tested application releases. App updates preserve the data home at `~/.disciple-maker`.

The published archive passed signing, notarization, Gatekeeper, native installed-upgrade, visible conversation continuity, credential-file preservation, and anonymous full-download checksum checks. The packaged app also successfully read this production update feed.

OpenRouter and LM Studio were tested locally. Gmail, subscription logins and third-party MCP account authorization require the recipient's setup and were not live-tested. Clean-machine and older-macOS hardware testing remain unverified. See the [release notes](https://github.com/ChrisChasm/disciple-maker-agent-platform-releases/releases/tag/v0.1.3) for details and known native UI limitations.
