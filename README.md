# Unknown (dnv)

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/apis.yml)

## Timestamps

- **Modified:** 2026-03-18 

## APIs

### DNV Class Status API
DNV's Class Status API provides programmatic access to vessel classification data. Authentication uses OAuth 2.0 with Azure AD B2C as the identity provider. Access tokens are obtained from https://login.microsoftonline.com/dnvglb2cprod.onmicrosoft.com/oauth2/token and are valid for approximately 20 minutes. Access requires a separate API contract with DNV. The API supports .NET ADAL library (NuGet: Microsoft.IdentityModel.Clients.ActiveDirectory) and includes retry logic recommendations using exponential backoff.

**Human URL:** [https://maritime.dnv.com/api/cs-iacs-customer](https://maritime.dnv.com/api/cs-iacs-customer)


#### Tags:

 - Maritime, Classification, Vessel, Safety, OAuth2, Azure AD

#### Properties

- [Reference](https://maritime.dnv.com/api/cs-iacs-customer/docs/index.html)
- [Documentation](https://maritime.dnv.com/api/cs-iacs-customer)
- [Authentication](https://maritime.dnv.com/api/cs-iacs-customer)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/openapi/dnv-class-status-openapi.yml)

### DNV Veracity Platform API
DNV Veracity is an open and secure industry data platform facilitating exchange of datasets, APIs, applications, and insights across maritime, oil and gas, and energy sectors. Veracity APIs enable access to operational vessel data, maritime analytics, and fleet management services for over 18,000 companies and 200,000 users.

**Human URL:** [https://www.veracity.com/](https://www.veracity.com/)


#### Tags:

 - Maritime, Data Platform, IoT, Analytics, Energy

#### Properties

- [Documentation](https://developer.veracity.com/docs/section/api-explorer/api-explorer)
- [Reference](https://developer.veracity.com/docs/section/datastandards/operationalvesseldata)
- [Portal](https://www.veracity.com/)

### DNV Vessel Register
DNV Vessel Register provides access to DNV's public registry of classified vessels including vessel identification, classification status, certificates, and survey history. The register supports fleet management and regulatory compliance workflows.

**Human URL:** [https://vesselregister.dnv.com/vesselregister](https://vesselregister.dnv.com/vesselregister)


#### Tags:

 - Maritime, Vessel Registry, Classification, Fleet Management

#### Properties

- [Documentation](https://vesselregister.dnv.com/vesselregister)

## Common Properties

- [Website](https://www.dnv.com/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/openapi/dnv-class-status-openapi.yml)
- [JSONSchema](https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/json-schema/dnv-vessel-schema.json)
- [JSONLDContext](https://raw.githubusercontent.com/api-evangelist/dnv/refs/heads/main/json-ld/dnv-context.jsonld)
- [Portal](https://www.veracity.com/)
- [Documentation](https://developer.veracity.com/docs/section/api-explorer/api-explorer)
- [Authentication](https://maritime.dnv.com/api/cs-iacs-customer)
- [Support](https://help-center.veracity.com/en/)
- [Support](https://support.veracity.com/)
- [PrivacyPolicy](https://www.dnv.com/privacy/)
- [TermsOfService](https://www.dnv.com/terms/)
- [Status](https://vesselregister.dnv.com/vesselregister)
- [GettingStarted](https://www.dnv.com/maritime/)

## Maintainers

**Email:** kin@apievangelist.com
