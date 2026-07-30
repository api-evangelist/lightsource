# LightSource

LightSource is an AI-native direct materials procurement platform that connects engineering, procurement, and suppliers across the full sourcing lifecycle from concept to award — automating RFX, AI-assisted bid analysis, supplier collaboration, and cost tracking across a network of 20,000+ live suppliers.

As of July 2026 LightSource publishes **no public API, developer portal, or OpenAPI specification**. Its documentation host is an end-user and supplier help center. This profile therefore captures the company's identity, security/compliance posture, and published `llms.txt` rather than API artifacts.

Backed by: bain-capital-ventures, lightspeed-venture-partners — https://lightsource.ai/

## Artifacts

| Artifact | File | Method |
|---|---|---|
| llms.txt | `llms/lightsource-llms.txt` | searched (verbatim) |
| Domain security | `security/lightsource-domain-security.yml` | probed |
| Vulnerability disclosure | `security/lightsource-vulnerability-disclosure.yml` | searched |
| Trust center / compliance | `security/lightsource-trust-center.yml` | searched |
| Conformance | `conformance/lightsource-conformance.yml` | searched |
| Lifecycle / status page | `lifecycle/lightsource-lifecycle.yml` | searched |
| Well-known (negative result) | `well-known/lightsource-well-known.yml` | probed |

> **Probing note:** `lightsource.ai` is a Next.js static export that returns HTTP 200 with the marketing homepage for *every* unmatched path. All `/.well-known/*` probes are false positives — verified against a control path. Do not trust status codes alone on this host.
