# Hunter (hunter)
Hunter is an email finding and verification service that helps find professional email addresses associated with a domain and verify email deliverability.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/hunter/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Contact Discovery, Email, Email Verification, Lead Generation, Prospecting, Sales Intelligence

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-18

## APIs

### Hunter Domain Search API
Returns all the email addresses found using a given domain name, with sources.

**Human URL:** [https://hunter.io/api/domain-search](https://hunter.io/api/domain-search)

#### Tags:

 - Contact Discovery, Domain, Email, Search

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#domain-search)
- [OpenAPI](openapi/hunter-api-openapi.yml)

### Hunter Email Finder API
Generates the most likely email address from a domain name, a first name and a last name.

**Human URL:** [https://hunter.io/api/email-finder](https://hunter.io/api/email-finder)

#### Tags:

 - Contact Discovery, Email, Finder, Lead Generation

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#email-finder)
- [OpenAPI](openapi/hunter-api-openapi.yml)

### Hunter Email Verifier API
Verifies the deliverability of a given email address.

**Human URL:** [https://hunter.io/api/email-verifier](https://hunter.io/api/email-verifier)

#### Tags:

 - Data Quality, Email, Validation, Verification

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#email-verifier)
- [OpenAPI](openapi/hunter-api-openapi.yml)

### Hunter Email Count API
Returns the number of email addresses found for a given domain.

**Human URL:** [https://hunter.io](https://hunter.io)

#### Tags:

 - Analytics, Count, Email

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#email-count)
- [OpenAPI](openapi/hunter-api-openapi.yml)

### Hunter Account API
Returns information about the account associated with the API key.

**Human URL:** [https://hunter.io](https://hunter.io)

#### Tags:

 - Account, Management, Usage

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#account)
- [OpenAPI](openapi/hunter-api-openapi.yml)

### Hunter Discover API
Returns companies matching a set of criteria using natural language queries or robust filters.

**Human URL:** [https://hunter.io/api/discover](https://hunter.io/api/discover)

#### Tags:

 - Companies, Discover, Lead Generation, Prospecting

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#discover)
- [OpenAPI](openapi/hunter-api-openapi.yml)

### Hunter Email Enrichment API
Returns comprehensive personal information linked to an email address or LinkedIn profile.

**Human URL:** [https://hunter.io/api/lead-enrichment](https://hunter.io/api/lead-enrichment)

#### Tags:

 - Data, Email, Enrichment, People

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#email-enrichment)
- [OpenAPI](openapi/hunter-api-openapi.yml)

### Hunter Company Enrichment API
Returns detailed organizational data associated with a domain name.

**Human URL:** [https://hunter.io/api/company-enrichment](https://hunter.io/api/company-enrichment)

#### Tags:

 - Company, Data, Enrichment, Firmographic

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#company-enrichment)
- [OpenAPI](openapi/hunter-api-openapi.yml)

### Hunter Combined Enrichment API
Merges person and company information for a single email address.

**Human URL:** [https://hunter.io/api/combined-enrichment](https://hunter.io/api/combined-enrichment)

#### Tags:

 - Combined, Company, Enrichment, People

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#combined-enrichment)
- [OpenAPI](openapi/hunter-api-openapi.yml)

### Hunter Leads API
Manage the leads stored in Hunter, including listing, creating, updating, upserting, and deleting leads.

**Human URL:** [https://hunter.io/api/leads](https://hunter.io/api/leads)

#### Tags:

 - Contacts, CRM, Leads, Management

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#leads)
- [OpenAPI](openapi/hunter-api-openapi.yml)

### Hunter Leads Lists API
Manage leads lists in Hunter, including listing, creating, updating, and deleting lead collection groups.

**Human URL:** [https://hunter.io/api/leads](https://hunter.io/api/leads)

#### Tags:

 - Leads, Lists, Management, Organization

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#leads_lists)
- [OpenAPI](openapi/hunter-api-openapi.yml)

### Hunter Campaigns API
Manage email sequences including listing campaigns, managing recipients, and starting sequences.

**Human URL:** [https://hunter.io/api/campaigns](https://hunter.io/api/campaigns)

#### Tags:

 - Automation, Campaigns, Email Outreach, Sequences

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#campaigns)
- [OpenAPI](openapi/hunter-api-openapi.yml)

### Hunter Logo API
Retrieves any company logo using a domain name.

**Human URL:** [https://hunter.io/api/logo](https://hunter.io/api/logo)

#### Tags:

 - Branding, Company, Images, Logo

#### Properties

- [Documentation](https://hunter.io/api-documentation/v2#logo)
- [OpenAPI](openapi/hunter-api-openapi.yml)

## Common Properties

- [Portal](https://hunter.io/api)
- [Documentation](https://hunter.io/api-documentation/v2)
- [Authentication](https://hunter.io/api-documentation/v2#authentication)
- [RateLimits](https://hunter.io/api-documentation/v2#rate-limiting)
- [Pricing](https://hunter.io/pricing)
- [TermsOfService](https://hunter.io/terms)
- [PrivacyPolicy](https://hunter.io/privacy-policy)
- [StatusPage](https://status.hunter.io)
- [Blog](https://hunter.io/blog)
- [GitHubOrganization](https://github.com/hunter-io)

## Features

| Name | Description |
|------|-------------|
| Domain Search | Find all email addresses associated with a domain name along with confidence scores and sources. |
| Email Finder | Generate the most likely email address for a person given their name and company domain. |
| Email Verification | Verify the deliverability and validity of email addresses with detailed status reporting. |
| Lead Management | Store, organize, and manage prospect leads with lists, tags, and CRM-like contact management. |
| Email Campaigns | Create and manage automated email outreach sequences with recipient tracking and scheduling. |
| Data Enrichment | Enrich email addresses and domains with personal, company, and firmographic data points. |
| Company Discovery | Find companies matching ideal customer profiles using natural language queries and advanced filters. |

## Use Cases

| Name | Description |
|------|-------------|
| Sales Prospecting | Find and verify email addresses for sales outreach by searching company domains and building prospect lists. |
| Lead Qualification | Enrich leads with company and personal data to qualify prospects and prioritize outreach efforts. |
| Email List Cleaning | Verify large email lists to reduce bounce rates and improve email deliverability. |
| Account-Based Marketing | Discover key contacts at target accounts using domain search and build targeted outreach campaigns. |
| Recruitment Outreach | Find professional email addresses for passive candidates at target companies for recruitment campaigns. |

## Integrations

| Name | Description |
|------|-------------|
| Salesforce | Push verified leads and enriched contacts directly to Salesforce CRM for pipeline management. |
| HubSpot | Sync leads and contact data with HubSpot CRM for unified sales and marketing workflows. |
| Pipedrive | Export leads to Pipedrive CRM with enriched contact and company information. |
| Zapier | Connect Hunter with thousands of apps through Zapier for automated lead processing workflows. |
| Google Sheets | Export domain search results and verified emails directly to Google Sheets for analysis. |
| Zoho CRM | Integrate lead data with Zoho CRM for end-to-end sales pipeline management. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Hunter API](openapi/hunter-api-openapi.yml)

### JSON-LD

- [Hunter Context](json-ld/hunter-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Hunter API](capabilities/shared/hunter-api.yaml) -- 25 operations for email finding, verification, and lead management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Sales Prospecting](capabilities/sales-prospecting.yaml) | Hunter API | 20 | Sales Development Rep |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
