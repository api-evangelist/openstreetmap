# OpenStreetMap (openstreetmap)

OpenStreetMap (OSM) is a collaborative project to create a free, editable map of the world. The OSM ecosystem exposes a family of public REST APIs: the main editing API (v0.6) for CRUD operations on map data, the Overpass API for complex read-only geospatial queries, and the Nominatim API for forward and reverse geocoding. Map data is licensed under the Open Database License (ODbL) 1.0 and tile imagery under CC BY-SA 2.0.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Geospatial, Mapping, Open Data, Geocoding, Editing

## Timestamps

- **Created:** 2026-03-18
- **Modified:** 2026-04-28

## APIs

### OpenStreetMap Main Editing API v0.6
The OpenStreetMap main API v0.6 provides CRUD operations for map data editing including nodes, ways, relations, changesets, and notes. Requires OAuth 2.0 authentication for write operations. Maximum bounding box query area is 0.25 square degrees. Returns XML or JSON. Intended for editing, not high-volume read access.

**Human URL:** [https://wiki.openstreetmap.org/wiki/API_v0.6](https://wiki.openstreetmap.org/wiki/API_v0.6)

**Base URL:** https://api.openstreetmap.org/api/0.6

#### Tags

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

**Base URL:** https://overpass-api.de/api

#### Tags

- Geospatial, Mapping, Open Data, XML, Overpass

#### Properties

- [Documentation](https://wiki.openstreetmap.org/wiki/Overpass_API)
- [Reference](https://dev.overpass-api.de/overpass-doc/en/)
- [DeveloperTools](https://overpass-turbo.eu/)

### OpenStreetMap Nominatim Geocoding API
Nominatim is the OpenStreetMap geocoding API providing search (forward geocoding), reverse geocoding, and address lookup for OSM objects. Rate limit is 1 request/second for the public instance. Requires valid User-Agent header. Open source under GNU GPL v3; self-hosted deployment available for higher volume needs.

**Human URL:** [https://nominatim.org/release-docs/latest/api/Overview/](https://nominatim.org/release-docs/latest/api/Overview/)

**Base URL:** https://nominatim.openstreetmap.org

#### Tags

- Geospatial, Mapping, Geocoding, Open Data

#### Properties

- [Documentation](https://nominatim.org/release-docs/latest/api/Overview/)
- [RateLimits](https://operations.osmfoundation.org/policies/nominatim/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-nominatim-openapi.yml)

## Common Properties

- [Website](https://www.openstreetmap.org/)
- [Documentation](https://wiki.openstreetmap.org/wiki/API)
- [Reference](https://wiki.openstreetmap.org/wiki/API_v0.6)
- [RateLimits](https://operations.osmfoundation.org/policies/api/)
- [TermsOfService](https://osmfoundation.org/wiki/Terms_of_Use)
- [PrivacyPolicy](https://osmfoundation.org/wiki/Privacy_Policy)
- [Blog](https://blog.openstreetmap.org/)
- [GitHubOrganization](https://github.com/openstreetmap)
- [License - Copyright](https://www.openstreetmap.org/copyright)
- [License - ODbL 1.0](https://opendatacommons.org/licenses/odbl/)
- [Wiki](https://wiki.openstreetmap.org/wiki/Main_Page)
- [Forum](https://community.openstreetmap.org/)
- [Support](https://help.openstreetmap.org/)
- [Authentication](https://www.openstreetmap.org/copyright)
- [OpenAPI - Main](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-main-openapi.yml)
- [OpenAPI - Nominatim](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/openapi/openstreetmap-nominatim-openapi.yml)
- [JSONSchema](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/json-schema/openstreetmap-node-schema.json)
- [JSONLDContext](https://raw.githubusercontent.com/api-evangelist/openstreetmap/refs/heads/main/json-ld/openstreetmap-context.jsonld)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
