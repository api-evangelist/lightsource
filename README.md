# LightSource

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
