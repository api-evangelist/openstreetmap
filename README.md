# OpenStreetMap

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

OpenStreetMap (OSM) is a collaborative project to create a free, editable map of the world. The OSM ecosystem exposes a family of public REST APIs: the main editing API (v0.6) for CRUD operations on map data, the Overpass API for complex read-only geospatial queries, and the Nominatim API for forward and reverse geocoding. Map data is licensed under the Open Database License (ODbL) 1.0 and tile imagery under CC BY-SA 2.0.

**Areas:** Geospatial · Mapping · Open Data · Geocoding · Editing · OpenStreetMap

## OpenStreetMap on APIs.io

Everything profiled for OpenStreetMap is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/openstreetmap/](https://apis.io/providers/openstreetmap/)** — or go straight to one of the APIs or properties below.

### APIs (11)

- [OpenStreetMap Overpass API](https://apis.io/apis/openstreetmap/overpass-api/) — The Overpass API is a read-only database engine for complex geospatial queries against the OSM dataset. Accepts Overpass QL or XML queries and returns…
- [OpenStreetMap Capabilities API](https://apis.io/apis/openstreetmap/openstreetmap-capabilities-api/) — API version and limits
- [OpenStreetMap Changesets API](https://apis.io/apis/openstreetmap/openstreetmap-changesets-api/) — Changeset management for grouped edits
- [OpenStreetMap Map Data API](https://apis.io/apis/openstreetmap/openstreetmap-map-data-api/) — Bulk map data retrieval by bounding box
- [OpenStreetMap Nodes API](https://apis.io/apis/openstreetmap/openstreetmap-nodes-api/) — OSM node (point) operations
- [OpenStreetMap Notes API](https://apis.io/apis/openstreetmap/openstreetmap-notes-api/) — Community map notes
- [OpenStreetMap Relations API](https://apis.io/apis/openstreetmap/openstreetmap-relations-api/) — OSM relation operations
- [OpenStreetMap Users API](https://apis.io/apis/openstreetmap/openstreetmap-users-api/) — User account information
- [OpenStreetMap Ways API](https://apis.io/apis/openstreetmap/openstreetmap-ways-api/) — OSM way (line/polygon) operations
- [OpenStreetMap Geocoding API](https://apis.io/apis/openstreetmap/openstreetmap-geocoding-api/) — Forward geocoding, reverse geocoding, and OSM object lookup
- [OpenStreetMap Status API](https://apis.io/apis/openstreetmap/openstreetmap-status-api/) — Server status and version information

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Openstreetmap Agentic Access](https://apis.io/agentic-access/openstreetmap/openstreetmap-agentic-access/)

#### JSON Schema (9)

The data models the API reads and writes.

- [Capabilities](https://apis.io/schemas/openstreetmap/openstreetmap-capabilities/)
- [Changeset](https://apis.io/schemas/openstreetmap/openstreetmap-changeset/)
- [OpenStreetMap Node](https://apis.io/schemas/openstreetmap/openstreetmap-node/)
- [Note](https://apis.io/schemas/openstreetmap/openstreetmap-note/)
- [NoteCollection](https://apis.io/schemas/openstreetmap/openstreetmap-notecollection/)
- [OSMData](https://apis.io/schemas/openstreetmap/openstreetmap-osmdata/)
- [Relation](https://apis.io/schemas/openstreetmap/openstreetmap-relation/)
- [User](https://apis.io/schemas/openstreetmap/openstreetmap-user/)
- [Way](https://apis.io/schemas/openstreetmap/openstreetmap-way/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Openstreetmap Structure](https://apis.io/json-structure/openstreetmap/openstreetmap-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Openstreetmap Context](https://apis.io/jsonld/openstreetmap/openstreetmap-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [OpenStreetMap Domain Vocabulary](https://apis.io/vocabularies/openstreetmap/openstreetmap-vocabulary/)

#### Collections (19)

Postman and Open Collection request collections.

- [OpenStreetMap API v0.6 Capabilities API](https://apis.io/collections/openstreetmap/open-openstreetmap-capabilities-api/)
- [OpenStreetMap API v0.6 Capabilities Changesets API](https://apis.io/collections/openstreetmap/open-openstreetmap-changesets-api/)
- [OpenStreetMap Nominatim Geocoding API](https://apis.io/collections/openstreetmap/open-openstreetmap-geocoding-api/)
- [OpenStreetMap API v0.6](https://apis.io/collections/openstreetmap/open-openstreetmap-main/)
- [OpenStreetMap API v0.6 Capabilities Map Data API](https://apis.io/collections/openstreetmap/open-openstreetmap-map-data-api/)
- [OpenStreetMap API v0.6 Capabilities Nodes API](https://apis.io/collections/openstreetmap/open-openstreetmap-nodes-api/)
- [OpenStreetMap API v0.6 Capabilities Notes API](https://apis.io/collections/openstreetmap/open-openstreetmap-notes-api/)
- [OpenStreetMap API v0.6 Capabilities Relations API](https://apis.io/collections/openstreetmap/open-openstreetmap-relations-api/)
- [OpenStreetMap Nominatim Geocoding Status API](https://apis.io/collections/openstreetmap/open-openstreetmap-status-api/)
- [OpenStreetMap API v0.6 Capabilities Users API](https://apis.io/collections/openstreetmap/open-openstreetmap-users-api/)
- [OpenStreetMap API v0.6 Capabilities Ways API](https://apis.io/collections/openstreetmap/open-openstreetmap-ways-api/)
- [OpenStreetMap API v0.6 Capabilities API](https://apis.io/collections/openstreetmap/postman-openstreetmap-capabilities-api/)
- [OpenStreetMap API v0.6 Capabilities Changesets API](https://apis.io/collections/openstreetmap/postman-openstreetmap-changesets-api/)
- [OpenStreetMap API v0.6 Capabilities Map Data API](https://apis.io/collections/openstreetmap/postman-openstreetmap-map-data-api/)
- [OpenStreetMap API v0.6 Capabilities Nodes API](https://apis.io/collections/openstreetmap/postman-openstreetmap-nodes-api/)
- [OpenStreetMap API v0.6 Capabilities Notes API](https://apis.io/collections/openstreetmap/postman-openstreetmap-notes-api/)
- [OpenStreetMap API v0.6 Capabilities Relations API](https://apis.io/collections/openstreetmap/postman-openstreetmap-relations-api/)
- [OpenStreetMap API v0.6 Capabilities Users API](https://apis.io/collections/openstreetmap/postman-openstreetmap-users-api/)
- [OpenStreetMap API v0.6 Capabilities Ways API](https://apis.io/collections/openstreetmap/postman-openstreetmap-ways-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [OpenStreetMap — jsonschema rules](https://apis.io/rules/openstreetmap/openstreetmap-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Openstreetmap Authentication](https://apis.io/security/openstreetmap/openstreetmap-authentication/)
- [Openstreetmap Domain Security](https://apis.io/security/openstreetmap/openstreetmap-domain-security/)
- [Openstreetmap Vulnerability Disclosure](https://apis.io/security/openstreetmap/openstreetmap-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Openstreetmap Scopes](https://apis.io/scopes/openstreetmap/openstreetmap-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Openstreetmap Plans Pricing](https://apis.io/plans/openstreetmap/openstreetmap-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Openstreetmap Rate Limits](https://apis.io/rate-limits/openstreetmap/openstreetmap-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Openstreetmap Finops](https://apis.io/finops/openstreetmap/openstreetmap-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.openstreetmap.org/)
- [Documentation](https://wiki.openstreetmap.org/wiki/API)
- [Support](https://help.openstreetmap.org/)
- [Blog](https://blog.openstreetmap.org/)
- [Terms of service](https://osmfoundation.org/wiki/Terms_of_Use)
- [Privacy policy](https://osmfoundation.org/wiki/Privacy_Policy)
- [GitHub](https://github.com/openstreetmap)

## API Evangelist rating

**Kin Score 44.4** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 66.1 |
| Contract quality | 60.5 |
| Contract governance | 9.8 |
| Operational transparency | 23.7 |
| Developer ergonomics | 46.4 |
| Access clarity | 28.9 |

**Agent readiness 28.8** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | negotiable (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | documented (partial credit) |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 40.2** — Government & Public Sector

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/openstreetmap/](https://apis.io/providers/openstreetmap/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for OpenStreetMap: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/openstreetmap/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
