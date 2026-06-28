# watchroom-releases

Auto-update feed and signed DMGs for **Watchroom** (macOS), consumed by
[Sparkle](https://sparkle-project.org). Artifacts only — the app source lives in
a separate private repo.

- `appcast.xml` — the Sparkle feed (`SUFeedURL` points here).
- Release assets — each version's notarized, EdDSA-signed `.dmg`.

Published by the project's `release.sh` script; not edited by hand.
