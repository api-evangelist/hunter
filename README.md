# Hunter (hunter)

Hunter is an email finding and verification service that helps find professional email addresses associated with a domain and verify email deliverability.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/hunter/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/hunter/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Contact Discovery
- Email
- Email Verification
- Lead Generation
- Prospecting
- Sales Intelligence

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Hunter Domain Search API

Returns all the email addresses found using a given domain name, with sources.

- **Human URL:** [https://hunter.io/api/domain-search](https://hunter.io/api/domain-search)
- **Base URL:** `https://api.hunter.io/v2`

#### Tags

- Contact Discovery
- Domain
- Email
- Search

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#domain-search)
- [OpenAPI](openapi/hunter-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hunter-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hunter-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hunter Email Finder API

Generates the most likely email address from a domain name, a first name and a last name.

- **Human URL:** [https://hunter.io/api/email-finder](https://hunter.io/api/email-finder)
- **Base URL:** `https://api.hunter.io/v2`

#### Tags

- Contact Discovery
- Email
- Finder
- Lead Generation

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#email-finder)
- [OpenAPI](openapi/hunter-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hunter-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hunter-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hunter Email Verifier API

Verifies the deliverability of a given email address.

- **Human URL:** [https://hunter.io/api/email-verifier](https://hunter.io/api/email-verifier)
- **Base URL:** `https://api.hunter.io/v2`

#### Tags

- Data Quality
- Email
- Validation
- Verification

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#email-verifier)
- [OpenAPI](openapi/hunter-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hunter-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hunter-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hunter Email Count API

Returns the number of email addresses found for a given domain.

- **Human URL:** [https://hunter.io](https://hunter.io)
- **Base URL:** `https://api.hunter.io/v2`

#### Tags

- Analytics
- Count
- Email

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#email-count)
- [OpenAPI](openapi/hunter-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hunter-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hunter-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hunter Account API

Returns information about the account associated with the API key.

- **Human URL:** [https://hunter.io](https://hunter.io)
- **Base URL:** `https://api.hunter.io/v2`

#### Tags

- Account
- Management
- Usage

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#account)
- [OpenAPI](openapi/hunter-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hunter-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hunter-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hunter Discover API

Returns companies matching a set of criteria using natural language queries or robust filters to find companies aligned with your ideal customer profile.

- **Human URL:** [https://hunter.io/api/discover](https://hunter.io/api/discover)
- **Base URL:** `https://api.hunter.io/v2`

#### Tags

- Companies
- Discover
- Lead Generation
- Prospecting

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#discover)
- [OpenAPI](openapi/hunter-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hunter-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hunter-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hunter Email Enrichment API

Returns comprehensive personal information linked to an email address or LinkedIn profile, providing enriched data points about the person.

- **Human URL:** [https://hunter.io/api/lead-enrichment](https://hunter.io/api/lead-enrichment)
- **Base URL:** `https://api.hunter.io/v2`

#### Tags

- Data
- Email
- Enrichment
- People

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#email-enrichment)
- [OpenAPI](openapi/hunter-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hunter-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hunter-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hunter Company Enrichment API

Returns detailed organizational data associated with a domain name, including company size, industry, location, and other firmographic information.

- **Human URL:** [https://hunter.io/api/company-enrichment](https://hunter.io/api/company-enrichment)
- **Base URL:** `https://api.hunter.io/v2`

#### Tags

- Company
- Data
- Enrichment
- Firmographic

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#company-enrichment)
- [OpenAPI](openapi/hunter-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hunter-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hunter-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hunter Combined Enrichment API

Merges person and company information for a single email address, returning enriched records combining both datasets.

- **Human URL:** [https://hunter.io/api/combined-enrichment](https://hunter.io/api/combined-enrichment)
- **Base URL:** `https://api.hunter.io/v2`

#### Tags

- Combined
- Company
- Enrichment
- People

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#combined-enrichment)
- [OpenAPI](openapi/hunter-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hunter-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hunter-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hunter Leads API

Allows you to manage the leads stored in Hunter, including listing, creating, updating, upserting, and deleting leads.

- **Human URL:** [https://hunter.io/api/leads](https://hunter.io/api/leads)
- **Base URL:** `https://api.hunter.io/v2`

#### Tags

- Contacts
- CRM
- Leads
- Management

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#leads)
- [OpenAPI](openapi/hunter-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hunter-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hunter-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/hunter-lead-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/hunter-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Hunter Leads Lists API

Allows you to manage leads lists in Hunter, including listing, creating, updating, and deleting lead collection groups.

- **Human URL:** [https://hunter.io/api/leads](https://hunter.io/api/leads)
- **Base URL:** `https://api.hunter.io/v2`

#### Tags

- Leads
- Lists
- Management
- Organization

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#leads_lists)
- [OpenAPI](openapi/hunter-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hunter-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hunter-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/hunter-lead-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/hunter-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Hunter Campaigns API

Allows you to manage email sequences including listing campaigns, managing recipients, and starting sequences for automated email outreach.

- **Human URL:** [https://hunter.io/api/campaigns](https://hunter.io/api/campaigns)
- **Base URL:** `https://api.hunter.io/v2`

#### Tags

- Automation
- Campaigns
- Email Outreach
- Sequences

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#campaigns)
- [OpenAPI](openapi/hunter-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hunter-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hunter-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hunter Logo API

Retrieves any company logo using a domain name. Free to use with no authentication required, just a backlink from your site to hunter.io.

- **Human URL:** [https://hunter.io/api/logo](https://hunter.io/api/logo)
- **Base URL:** `https://logos.hunter.io`

#### Tags

- Branding
- Company
- Images
- Logo

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#logo)
- [OpenAPI](openapi/hunter-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/hunter-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/hunter-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/hunterny)
- [Portal](https://hunter.io/api)
- [Documentation](https://hunter.io/api-documentation/v2)
- [OpenAPI](openapi/hunter-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/hunter-lead-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/hunter-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Authentication](https://hunter.io/api-documentation/v2#authentication)
- [Rate Limits](https://hunter.io/api-documentation/v2#rate-limiting)
- [Pricing](https://hunter.io/pricing)
- [Terms of Service](https://hunter.io/terms)
- [Privacy Policy](https://hunter.io/privacy-policy)
- [Status Page](https://status.hunter.io)
- [Blog](https://hunter.io/blog)
- [Login](https://hunter.io/users/sign_in)
- [Sign Up](https://hunter.io/users/sign_up)
- [Changelog](https://hunter.io/changelog)
- [Integrations](https://hunter.io/integrations)
- [GitHub Organization](https://github.com/hunter-io)
- [Contact](https://hunter.io/contact)
- [Support](https://help.hunter.io)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [M C P Server](https://github.com/hunter-io/hunter-mcp)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
