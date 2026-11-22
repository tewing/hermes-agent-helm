---
"@jyje/hermes-agent-helm": minor
---

Feature(values): Profiles from pinned distributions

Declare extra Hermes profiles under `profiles`: install each from a profile distribution at a pinned tag or branch, refresh it from that ref on every start, and give each profile its own Secret for its credentials.
