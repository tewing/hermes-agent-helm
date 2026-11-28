---
"@jyje/hermes-agent-helm": minor
---

Feature(values): `profilesInit.extraEnv` for the profiles init container

Add env to the `profiles` init container only, such as a short-lived GITHUB_TOKEN for private plugin installs that should not reach the gateway.
