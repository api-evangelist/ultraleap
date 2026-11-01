# Ultraleap

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Ultraleap Limited (Bristol, UK) is the hand-tracking and mid-air haptics company formed in 2019 when Ultrahaptics acquired Leap Motion. It ships the Leap Motion Controller 2 and Stereo IR 170 / 3Di hand-tracking cameras, the Ultraleap Hand Tracking Software (Gemini V5, now Hyperion V6) with its native LeapC C API, first-party Unity and Unreal plugins, an implicit OpenXR API layer implementing XR_EXT_hand_tracking, Python bindings, a LeapJS-compatible tracking WebSocket server, and the TouchFree touchless interaction tooling for web and Unity. Its ultrasonic haptics SDK is supplied on request rather than published. The developer surface is a locally installed SDK and service, not a hosted HTTP API, so there is no OpenAPI or base URL. In 2025 the company announced it is joining ROLI, the music-technology company.

**Areas:** Company · Hand Tracking · Computer Vision · Spatial Computing · Haptics · Augmented Reality · Virtual Reality · Extended Reality · Gesture Recognition · OpenXR · SDK · Hardware

## Ultraleap on APIs.io

Everything profiled for Ultraleap is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ultraleap/](https://apis.io/providers/ultraleap/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [LeapC Tracking API](https://apis.io/apis/ultraleap/leapc-tracking-api/) — LeapC is the native C API of the Ultraleap Hand Tracking Software. A client opens a connection to the locally running tracking service and polls it for…
- [Ultraleap OpenXR API Layer](https://apis.io/apis/ultraleap/openxr-api-layer/) — An implicit Khronos OpenXR API layer, installed with the Hand Tracking Software, that serves XR_EXT_hand_tracking, XR_EXT_hand_joints_motion_range,…
- [Ultraleap Tracking WebSocket](https://apis.io/apis/ultraleap/tracking-websocket/) — An open-source WebSocket server from Ultraleap that restores the LeapJS-compatible surface removed when Leap Motion Orion V4 was replaced by Ultraleap…
- [TouchFree Tooling](https://apis.io/apis/ultraleap/touchfree-tooling/) — TouchFree turns Ultraleap hand tracking into touchless cursor and gesture input for kiosks, digital signage and existing 2D user interfaces. The TouchFree…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Ultraleap Domain Security](https://apis.io/security/ultraleap/ultraleap-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ultraleap.com/)
- [Documentation](https://docs.ultraleap.com/hand-tracking/index.html)
- [Getting started](https://docs.ultraleap.com/hand-tracking/getting-started.html)
- [API reference](https://docs.ultraleap.com/api-reference/tracking-api/index.html)
- [Support](https://www.ultraleap.com/contact/)
- [Changelog](https://docs.ultraleap.com/openxr/changelog/index.html)
- [Blog](https://docs.ultraleap.com/ultralab/index.html)
- [Terms of service](https://www.ultraleap.com/legal/ultraleap-ltd-terms-conditions-of-business/)
- [Privacy policy](https://www.ultraleap.com/legal/privacy-policy/)
- [GitHub](https://github.com/ultraleap)

## API Evangelist rating

**Kin Score 30.4** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 69.6 |
| Contract quality | 6.5 |
| Contract governance | 18.2 |
| Operational transparency | 18.4 |
| Developer ergonomics | 52.4 |
| Access clarity | 28.9 |

**Agent readiness 4.1** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 21.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ultraleap/](https://apis.io/providers/ultraleap/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Ultraleap: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ultraleap/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
