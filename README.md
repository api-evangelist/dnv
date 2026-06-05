# DNV (dnv)

DNV is a global classification, certification, and assurance provider for the maritime, energy, and industrial sectors. The API portfolio includes the Class Status API for vessel classification data, the Veracity industry data platform, and the public Vessel Register, supporting fleet management, regulatory compliance, and operational analytics workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/apis.yml)

## Tags

- Maritime
- Energy
- Classification
- Vessel
- Data Platform

## Timestamps

- **Modified:** 2026-05-19

## APIs

### DNV Class Status API

DNV's Class Status API provides programmatic access to vessel classification data. Authentication uses OAuth 2.0 with Azure AD B2C as the identity provider. Access tokens are obtained from https://login.microsoftonline.com/dnvglb2cprod.onmicrosoft.com/oauth2/token and are valid for approximately 20 minutes. Access requires a separate API contract with DNV.

- **Human URL:** [https://maritime.dnv.com/api/cs-iacs-customer](https://maritime.dnv.com/api/cs-iacs-customer)
- **Base URL:** `https://maritime.dnv.com/api/cs-iacs-customer`

#### Tags

- Azure AD
- Classification
- Maritime
- OAuth2
- Safety
- Vessel

#### Properties

- [Reference](https://maritime.dnv.com/api/cs-iacs-customer/docs/index.html)
- [Documentation](https://maritime.dnv.com/api/cs-iacs-customer)
- [Authentication](https://maritime.dnv.com/api/cs-iacs-customer)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/openapi/dnv-class-status-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/dnv-class-status.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dnv-class-status.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DNV Veracity Platform API

DNV Veracity is an open and secure industry data platform facilitating exchange of datasets, APIs, applications, and insights across maritime, oil and gas, and energy sectors. Veracity APIs enable access to operational vessel data, maritime analytics, and fleet management services for over 18,000 companies and 200,000 users.

- **Human URL:** [https://www.veracity.com/](https://www.veracity.com/)
- **Base URL:** `https://api.veracity.com`

#### Tags

- Analytics
- Data Platform
- Energy
- IoT
- Maritime

#### Properties

- [Documentation](https://developer.veracity.com/docs/section/api-explorer/api-explorer)
- [Reference](https://developer.veracity.com/docs/section/datastandards/operationalvesseldata)
- [Portal](https://www.veracity.com/)
- [Postman Collection](collections/dnv-class-status.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dnv-class-status.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DNV Vessel Register

DNV Vessel Register provides access to DNV's public registry of classified vessels including vessel identification, classification status, certificates, and survey history. The register supports fleet management and regulatory compliance workflows.

- **Human URL:** [https://vesselregister.dnv.com/vesselregister](https://vesselregister.dnv.com/vesselregister)
- **Base URL:** `https://vesselregister.dnv.com`

#### Tags

- Classification
- Fleet Management
- Maritime
- Vessel Registry

#### Properties

- [Documentation](https://vesselregister.dnv.com/vesselregister)
- [Postman Collection](collections/dnv-class-status.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dnv-class-status.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/dnv-opensource)
- [LinkedIn](https://www.linkedin.com/company/det-norske-veritas-dnv-gl-)
- [Website](https://www.dnv.com/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/openapi/dnv-class-status-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/json-schema/dnv-vessel-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/json-ld/dnv-context.jsonld)
- [Portal](https://www.veracity.com/)
- [Documentation](https://developer.veracity.com/docs/section/api-explorer/api-explorer)
- [Authentication](https://maritime.dnv.com/api/cs-iacs-customer)
- [Support](https://help-center.veracity.com/en/)
- [Support](https://support.veracity.com/)
- [Privacy Policy](https://www.dnv.com/privacy/)
- [Terms of Service](https://www.dnv.com/terms/)
- [Status Page](https://vesselregister.dnv.com/vesselregister)
- [Getting Started](https://www.dnv.com/maritime/)

## Maintainers

**Email:** kin@apievangelist.com
