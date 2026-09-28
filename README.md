# SpendLens for Mac

SpendLens imports credit-card statements, helps you review categories, and explains household spending. Your household data stays on your Mac. This repository contains application downloads and update information, not application source or household data.

**[Download SpendLens for Mac](https://github.com/AliAbdelhamid1/SpendLens-Releases/releases/latest)** — choose `SpendLens_1.0.0_universal.dmg` under Assets.

The universal package includes Apple Silicon and Intel code and targets macOS 13 or later. Initial qualification is limited to macOS 26.1 on Apple Silicon. Older supported-platform and full production update/recovery testing remain incomplete; see the release notes.

## Install

1. Download the DMG from the official release page above.
2. Open it, drag SpendLens into Applications, and eject the disk image.
3. Open SpendLens from Applications.
4. This free build is not verified or notarized by Apple. If macOS blocks it, use System Settings → Privacy & Security → Open Anyway for SpendLens and complete the native authentication prompt. Follow [Apple's instructions](https://support.apple.com/guide/mac-help/open-a-mac-app-from-an-unknown-developer-mh40616/mac). Do not disable Gatekeeper or remove quarantine.

No SpendLens or GitHub account, development tools, or terminal commands are needed for ordinary installation.

If you used a development build before, a message about a separate stable setup means the app preserved that data and needs the maintainer's one-time handoff. Do not delete the existing data folder. This step is separate from installation on a new Mac.

## Updates

Use the App control near the top-left to check for updates. When a newer release is available, choose **Later** to keep working or **Download and restart** when ready. Finish or cancel active imports first. The app verifies each update against its embedded signing key.

If an update cannot finish, retain your data and the error message and contact the maintainer. Do not delete application data or install arbitrary older versions. A failed data activation and an already-committed update have different recovery paths.

## Release integrity

Published releases are immutable. An unsafe release is withdrawn in full and replaced with a new version; its files are not silently replaced. Public downloads and in-app update metadata do not require authentication.

## Withdrawn releases

| Version | UTC withdrawal date | Reason | Replacement |
| --- | --- | --- | --- |
