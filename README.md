# OpenStreetMap (openstreetmap)

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

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Geospatial
- Mapping
- Open Data
- Geocoding
- Editing

## Timestamps

- **Created:** 2026-03-18
- **Modified:** 2026-05-19

## APIs

### OpenStreetMap Main Editing API v0.6

The OpenStreetMap main API v0.6 provides CRUD operations for map data editing including nodes, ways, relations, changesets, and notes. Requires OAuth 2.0 authentication for write operations. Maximum bounding box query area is 0.25 square degrees. Returns XML or JSON. Intended for editing, not high-volume read access.

- **Human URL:** [https://wiki.openstreetmap.org/wiki/API_v0.6](https://wiki.openstreetmap.org/wiki/API_v0.6)
- **Base URL:** `https://api.openstreetmap.org/api/0.6`

#### Tags

- Geospatial
- Mapping
- Open Data
- REST
- Editing

#### Properties

- [Documentation](https://wiki.openstreetmap.org/wiki/API_v0.6)
- [Rate Limits](https://operations.osmfoundation.org/policies/api/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-main-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/json-schema/openstreetmap-node-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/json-ld/openstreetmap-context.jsonld)
- [Postman Collection](collections/openstreetmap-main.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstreetmap-main.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenStreetMap Overpass API

The Overpass API is a read-only database engine for complex geospatial queries against the OSM dataset. Accepts Overpass QL or XML queries and returns results in XML, JSON, GeoJSON, or CSV. Safe usage: under 10,000 queries/day and under 1 GB/day. Python SDKs include overpass, overpy, and OSMPythonTools; JavaScript SDKs include query-overpass and overpass-ts.

- **Human URL:** [https://wiki.openstreetmap.org/wiki/Overpass_API](https://wiki.openstreetmap.org/wiki/Overpass_API)
- **Base URL:** `https://overpass-api.de/api`

#### Tags

- Geospatial
- Mapping
- Open Data
- XML
- Overpass

#### Properties

- [Documentation](https://wiki.openstreetmap.org/wiki/Overpass_API)
- [Reference](https://dev.overpass-api.de/overpass-doc/en/)
- [Developer Tools](https://overpass-turbo.eu/)
- [Postman Collection](collections/openstreetmap-main.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstreetmap-main.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenStreetMap Nominatim Geocoding API

Nominatim is the OpenStreetMap geocoding API providing search (forward geocoding), reverse geocoding, and address lookup for OSM objects. Rate limit is 1 request/second for the public instance. Requires valid User-Agent header. Open source under GNU GPL v3; self-hosted deployment available for higher volume needs.

- **Human URL:** [https://nominatim.org/release-docs/latest/api/Overview/](https://nominatim.org/release-docs/latest/api/Overview/)
- **Base URL:** `https://nominatim.openstreetmap.org`

#### Tags

- Geospatial
- Mapping
- Geocoding
- Open Data

#### Properties

- [Documentation](https://nominatim.org/release-docs/latest/api/Overview/)
- [Rate Limits](https://operations.osmfoundation.org/policies/nominatim/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-nominatim-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openstreetmap-main.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openstreetmap-main.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/openstreetmap-foundation)
- [Website](https://www.openstreetmap.org/)
- [Portal](https://www.openstreetmap.org/)
- [Documentation](https://wiki.openstreetmap.org/wiki/API)
- [Reference](https://wiki.openstreetmap.org/wiki/API_v0.6)
- [Rate Limits](https://operations.osmfoundation.org/policies/api/)
- [Terms of Service](https://osmfoundation.org/wiki/Terms_of_Use)
- [Privacy Policy](https://osmfoundation.org/wiki/Privacy_Policy)
- [Blog](https://blog.openstreetmap.org/)
- [GitHub Organization](https://github.com/openstreetmap)
- [License](https://www.openstreetmap.org/copyright)
- [License](https://opendatacommons.org/licenses/odbl/)
- [Documentation](https://wiki.openstreetmap.org/wiki/Main_Page)
- [Forum](https://community.openstreetmap.org/)
- [Support](https://help.openstreetmap.org/)
- [Authentication](https://www.openstreetmap.org/copyright)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-main-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-nominatim-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/json-schema/openstreetmap-node-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/json-ld/openstreetmap-context.jsonld)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
