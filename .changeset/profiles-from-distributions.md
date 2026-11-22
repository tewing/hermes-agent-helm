---
"@jyje/hermes-agent-helm": minor
---

Feature(values): Profiles from pinned distributions

Declare extra Hermes profiles under `profiles`: install each from a profile distribution at a pinned tag or branch and refresh it from that ref on every start, or define one entirely in values with a per-profile `config`; install per-profile `plugins` before the gateway starts; and give each profile its own Secret for its credentials.
