# Unknown (openstreetmap)

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-03-18 

## APIs

### OpenStreetMap Main Editing API v0.6
The OpenStreetMap main API v0.6 provides CRUD operations for map data editing including nodes, ways, relations, changesets, and notes. Requires OAuth 2.0 authentication for write operations. Maximum bounding box query area is 0.25 square degrees. Returns XML or JSON. Intended for editing, not high-volume read access.

**Human URL:** [https://wiki.openstreetmap.org/wiki/API_v0.6](https://wiki.openstreetmap.org/wiki/API_v0.6)


#### Tags:

 - Geospatial, Mapping, Open Data, REST, Editing

#### Properties

- [Documentation](https://wiki.openstreetmap.org/wiki/API_v0.6)
- [RateLimits](https://operations.osmfoundation.org/policies/api/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-main-openapi.yml)
- [JSONSchema](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/json-schema/openstreetmap-node-schema.json)
- [JSONLDContext](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/json-ld/openstreetmap-context.jsonld)

### OpenStreetMap Overpass API
The Overpass API is a read-only database engine for complex geospatial queries against the OSM dataset. Accepts Overpass QL or XML queries and returns results in XML, JSON, GeoJSON, or CSV. Safe usage: under 10,000 queries/day and under 1 GB/day. Python SDKs include overpass, overpy, and OSMPythonTools; JavaScript SDKs include query-overpass and overpass-ts.

**Human URL:** [https://wiki.openstreetmap.org/wiki/Overpass_API](https://wiki.openstreetmap.org/wiki/Overpass_API)


#### Tags:

 - Geospatial, Mapping, Open Data, XML, Overpass

#### Properties

- [Documentation](https://wiki.openstreetmap.org/wiki/Overpass_API)
- [Reference](https://dev.overpass-api.de/overpass-doc/en/)
- [DeveloperTools](https://overpass-turbo.eu/)

### OpenStreetMap Nominatim Geocoding API
Nominatim is the OpenStreetMap geocoding API providing search (forward geocoding), reverse geocoding, and address lookup for OSM objects. Rate limit is 1 request/second for the public instance. Requires valid User-Agent header. Open source under GNU GPL v3; self-hosted deployment available for higher volume needs.

**Human URL:** [https://nominatim.org/release-docs/latest/api/Overview/](https://nominatim.org/release-docs/latest/api/Overview/)


#### Tags:

 - Geospatial, Mapping, Geocoding, Open Data

#### Properties

- [Documentation](https://nominatim.org/release-docs/latest/api/Overview/)
- [RateLimits](https://operations.osmfoundation.org/policies/nominatim/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-nominatim-openapi.yml)

### OpenStreetMap Overpass API
OpenStreetMap provides the Overpass API for complex geospatial queries against the OSM database. The API accepts Overpass QL queries and returns XML or JSON results for building footprints, road networks, POIs, and administrative boundaries.

**Human URL:** [https://wiki.openstreetmap.org/wiki/Overpass_API](https://wiki.openstreetmap.org/wiki/Overpass_API)


#### Tags:

 - Geospatial, Mapping, Open Data, XML, Overpass

#### Properties

- [Documentation](https://wiki.openstreetmap.org/wiki/Overpass_API)

## Common Properties

- [Portal](https://www.openstreetmap.org/)
- [Website](https://www.openstreetmap.org/)
- [Documentation](https://wiki.openstreetmap.org/wiki/API)
- [Reference](https://wiki.openstreetmap.org/wiki/API_v0.6)
- [RateLimits](https://operations.osmfoundation.org/policies/api/)
- [TermsOfService](https://osmfoundation.org/wiki/Terms_of_Use)
- [PrivacyPolicy](https://osmfoundation.org/wiki/Privacy_Policy)
- [Blog](https://blog.openstreetmap.org/)
- [GitHubOrganization](https://github.com/openstreetmap)
- [Authentication](https://openstreetmap.org/copyright)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-main-openapi.yml)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-nominatim-openapi.yml)
- [JSONSchema](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/json-schema/openstreetmap-node-schema.json)
- [JSONLDContext](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/json-ld/openstreetmap-context.jsonld)
