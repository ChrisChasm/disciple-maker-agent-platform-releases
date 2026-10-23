# Disciple Maker Agent Platform releases

Distribution repository for the macOS application. Application source belongs in the separate private `ChrisChasm/disciple-maker-agent-platform` repository.

This repository is currently private. Download access and the authenticated update route are not yet configured; it is not a functioning update service yet.

Each published release will contain the signed and notarized application ZIP, `latest-mac.yml` for the native macOS updater, `release.json` with checksums and the exact application and Hermes source revisions, and release notes.

Hermes is bundled at a tested, pinned revision. Engine upgrades ship only as part of an evaluated Disciple Maker Agent Platform release. Never put source documents, `.env` files, Apple credentials, provider keys, or maintainer GitHub tokens in distribution assets.

Before a release is considered ready, verify installation and a complete native version-to-version update, including persistence of profiles, conversations, and settings.
