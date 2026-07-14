# Jamf Spotlight — update feed

This repository exists **only** to host the auto-update feed for
[Jamf Spotlight](https://github.com/joshikavan92/jamf-spotlight), a ⌘K command palette for
the Jamf suite.

- `appcast.xml` — the Sparkle feed the app checks for new versions.
- Releases here carry the signed, notarized `.dmg` that Sparkle downloads.

It contains no source code. Every update is signed with an EdDSA key and verified by the app
against the public key baked into its bundle, so an update the app can't verify is refused.

**Installing?** Grab the DMG from the latest release. The app updates itself from then on.
