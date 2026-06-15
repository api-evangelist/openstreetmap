# OpenStreetMap (openstreetmap)

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
