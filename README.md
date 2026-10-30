# Hunter

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

Hunter is an email finding, verification and B2B prospecting platform. Its v2 API finds the professional email addresses associated with a company domain, predicts an address for a named person, verifies deliverability, enriches people and companies, discovers target accounts by natural-language query or structured filter, and manages the leads, lead lists and outreach sequences built from those results. Hunter also operates a first-party remote MCP server at https://mcp.hunter.io/mcp exposing roughly 100 tools, and publishes its own packaged Agent Skills, making it one of the few providers whose agent surface is wider than its documented REST contract.

**Areas:** Contact Discovery · Email · Email Verification · Lead Generation · Prospecting · Sales Intelligence

## Hunter on APIs.io

Everything profiled for Hunter is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/hunter/](https://apis.io/providers/hunter/)** — or go straight to one of the APIs or properties below.

### APIs (12)

- [Hunter Account API](https://apis.io/apis/hunter/hunter-account-api/) — Retrieve account information and usage statistics.
- [Hunter Campaigns API](https://apis.io/apis/hunter/hunter-campaigns-api/) — Manage email sequences and recipients.
- [Hunter Combined Enrichment API](https://apis.io/apis/hunter/hunter-combined-enrichment-api/) — Merge person and company enrichment for a single email address.
- [Hunter Company Enrichment API](https://apis.io/apis/hunter/hunter-company-enrichment-api/) — Enrich company information linked to a domain name.
- [Hunter Discover API](https://apis.io/apis/hunter/hunter-discover-api/) — Find companies matching criteria using natural language or filters.
- [Hunter Domain Search API](https://apis.io/apis/hunter/hunter-domain-search-api/) — Search for email addresses associated with a domain.
- [Hunter Email Count API](https://apis.io/apis/hunter/hunter-email-count-api/) — Count email addresses found for a domain.
- [Hunter Email Enrichment API](https://apis.io/apis/hunter/hunter-email-enrichment-api/) — Enrich personal information linked to an email or LinkedIn profile.
- [Hunter Email Finder API](https://apis.io/apis/hunter/hunter-email-finder-api/) — Find the most likely email address for a person at a company.
- [Hunter Email Verifier API](https://apis.io/apis/hunter/hunter-email-verifier-api/) — Verify the deliverability of an email address.
- [Hunter Leads API](https://apis.io/apis/hunter/hunter-leads-api/) — Manage leads stored in Hunter.
- [Hunter Leads Lists API](https://apis.io/apis/hunter/hunter-leads-lists-api/) — Manage leads list collections in Hunter.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (10)

Multi-step workflows that chain operations into a business task.

- [Hunter Account-Guarded Domain Search](https://apis.io/arazzos/hunter/hunter-account-guarded-domain-search-workflow/)
- [Hunter Combined Enrich and Upsert Lead](https://apis.io/arazzos/hunter/hunter-combined-enrich-upsert-lead-workflow/)
- [Hunter Create List and Add Lead](https://apis.io/arazzos/hunter/hunter-create-list-add-lead-workflow/)
- [Hunter Discover, Search, and Count](https://apis.io/arazzos/hunter/hunter-discover-search-count-workflow/)
- [Hunter Domain Search to Build a Verified List](https://apis.io/arazzos/hunter/hunter-domain-search-build-list-workflow/)
- [Hunter Domain Search, Find, and Verify](https://apis.io/arazzos/hunter/hunter-domain-search-find-verify-workflow/)
- [Hunter Enrich, Verify, and Create Lead](https://apis.io/arazzos/hunter/hunter-enrich-verify-create-lead-workflow/)
- [Hunter Find, Verify, and Add Campaign Recipient](https://apis.io/arazzos/hunter/hunter-find-verify-add-recipient-workflow/)
- [Hunter Find, Verify, and Create Lead](https://apis.io/arazzos/hunter/hunter-find-verify-create-lead-workflow/)
- [Hunter Verify and Add to Campaign](https://apis.io/arazzos/hunter/hunter-verify-add-to-campaign-workflow/)

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Hunter Webhooks](https://apis.io/asyncapis/hunter/hunter-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [hunter](https://apis.io/servers/hunter/hunter/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Hunter Agentic Access](https://apis.io/agentic-access/hunter/hunter-agentic-access/)

#### JSON Schema (41)

The data models the API reads and writes.

- [AccountResult](https://apis.io/schemas/hunter/hunter-account-result/)
- [AccountResult](https://apis.io/schemas/hunter/hunter-accountresult/)
- [Campaign](https://apis.io/schemas/hunter/hunter-campaign/)
- [CampaignRecipient](https://apis.io/schemas/hunter/hunter-campaign-recipient/)
- [CampaignRecipient](https://apis.io/schemas/hunter/hunter-campaignrecipient/)
- [CompanyEnrichment](https://apis.io/schemas/hunter/hunter-company-enrichment/)
- [CompanyGeoLocation](https://apis.io/schemas/hunter/hunter-company-geo-location/)
- [CompanyEnrichment](https://apis.io/schemas/hunter/hunter-companyenrichment/)
- [CompanyGeoLocation](https://apis.io/schemas/hunter/hunter-companygeolocation/)
- [DiscoverRequest](https://apis.io/schemas/hunter/hunter-discover-request/)
- [DiscoverResult](https://apis.io/schemas/hunter/hunter-discover-result/)
- [DiscoverRequest](https://apis.io/schemas/hunter/hunter-discoverrequest/)
- [DiscoverResult](https://apis.io/schemas/hunter/hunter-discoverresult/)
- [DomainEmail](https://apis.io/schemas/hunter/hunter-domain-email/)
- [DomainSearchResult](https://apis.io/schemas/hunter/hunter-domain-search-result/)
- [DomainEmail](https://apis.io/schemas/hunter/hunter-domainemail/)
- [DomainSearchResult](https://apis.io/schemas/hunter/hunter-domainsearchresult/)
- [EmailCountResult](https://apis.io/schemas/hunter/hunter-email-count-result/)
- [EmailFinderResult](https://apis.io/schemas/hunter/hunter-email-finder-result/)
- [EmailVerifierResult](https://apis.io/schemas/hunter/hunter-email-verifier-result/)
- [EmailCountResult](https://apis.io/schemas/hunter/hunter-emailcountresult/)
- [EmailFinderResult](https://apis.io/schemas/hunter/hunter-emailfinderresult/)
- [EmailVerifierResult](https://apis.io/schemas/hunter/hunter-emailverifierresult/)
- [Error](https://apis.io/schemas/hunter/hunter-error/)
- [GeoLocation](https://apis.io/schemas/hunter/hunter-geo-location/)
- …and 16 more published on APIs.io

#### JSON Structure (24)

Data models expressed in JSON Structure.

- [Hunter Account Result Structure](https://apis.io/json-structure/hunter/hunter-account-result-structure/)
- [Hunter Campaign Recipient Structure](https://apis.io/json-structure/hunter/hunter-campaign-recipient-structure/)
- [Hunter Campaign Structure](https://apis.io/json-structure/hunter/hunter-campaign-structure/)
- [Hunter Company Enrichment Structure](https://apis.io/json-structure/hunter/hunter-company-enrichment-structure/)
- [Hunter Company Geo Location Structure](https://apis.io/json-structure/hunter/hunter-company-geo-location-structure/)
- [Hunter Discover Request Structure](https://apis.io/json-structure/hunter/hunter-discover-request-structure/)
- [Hunter Discover Result Structure](https://apis.io/json-structure/hunter/hunter-discover-result-structure/)
- [Hunter Domain Email Structure](https://apis.io/json-structure/hunter/hunter-domain-email-structure/)
- [Hunter Domain Search Result Structure](https://apis.io/json-structure/hunter/hunter-domain-search-result-structure/)
- [Hunter Email Count Result Structure](https://apis.io/json-structure/hunter/hunter-email-count-result-structure/)
- [Hunter Email Finder Result Structure](https://apis.io/json-structure/hunter/hunter-email-finder-result-structure/)
- [Hunter Email Verifier Result Structure](https://apis.io/json-structure/hunter/hunter-email-verifier-result-structure/)
- [Hunter Error Structure](https://apis.io/json-structure/hunter/hunter-error-structure/)
- [Hunter Geo Location Structure](https://apis.io/json-structure/hunter/hunter-geo-location-structure/)
- [Hunter Lead Input Structure](https://apis.io/json-structure/hunter/hunter-lead-input-structure/)
- [Hunter Lead Structure](https://apis.io/json-structure/hunter/hunter-lead-structure/)
- [Hunter Leads List Structure](https://apis.io/json-structure/hunter/hunter-leads-list-structure/)
- [Hunter Meta Structure](https://apis.io/json-structure/hunter/hunter-meta-structure/)
- [Hunter Pagination Meta Structure](https://apis.io/json-structure/hunter/hunter-pagination-meta-structure/)
- [Hunter Person Enrichment Structure](https://apis.io/json-structure/hunter/hunter-person-enrichment-structure/)
- [Hunter Source Structure](https://apis.io/json-structure/hunter/hunter-source-structure/)
- [Hunter Structure](https://apis.io/json-structure/hunter/hunter-structure/)
- [Hunter Usage Counter Structure](https://apis.io/json-structure/hunter/hunter-usage-counter-structure/)
- [Hunter Verification Status Structure](https://apis.io/json-structure/hunter/hunter-verification-status-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Hunter Context](https://apis.io/jsonld/hunter/hunter-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Hunter Domain Vocabulary](https://apis.io/vocabularies/hunter/hunter-vocabulary/)

#### Examples (23)

Example requests and responses.

- [Hunter Account Result Example](https://apis.io/examples/hunter/hunter-account-result-example/)
- [Hunter Campaign Example](https://apis.io/examples/hunter/hunter-campaign-example/)
- [Hunter Campaign Recipient Example](https://apis.io/examples/hunter/hunter-campaign-recipient-example/)
- [Hunter Company Enrichment Example](https://apis.io/examples/hunter/hunter-company-enrichment-example/)
- [Hunter Company Geo Location Example](https://apis.io/examples/hunter/hunter-company-geo-location-example/)
- [Hunter Discover Request Example](https://apis.io/examples/hunter/hunter-discover-request-example/)
- [Hunter Discover Result Example](https://apis.io/examples/hunter/hunter-discover-result-example/)
- [Hunter Domain Email Example](https://apis.io/examples/hunter/hunter-domain-email-example/)
- [Hunter Domain Search Result Example](https://apis.io/examples/hunter/hunter-domain-search-result-example/)
- [Hunter Email Count Result Example](https://apis.io/examples/hunter/hunter-email-count-result-example/)
- [Hunter Email Finder Result Example](https://apis.io/examples/hunter/hunter-email-finder-result-example/)
- [Hunter Email Verifier Result Example](https://apis.io/examples/hunter/hunter-email-verifier-result-example/)
- [Hunter Error Example](https://apis.io/examples/hunter/hunter-error-example/)
- [Hunter Geo Location Example](https://apis.io/examples/hunter/hunter-geo-location-example/)
- [Hunter Lead Example](https://apis.io/examples/hunter/hunter-lead-example/)
- [Hunter Lead Input Example](https://apis.io/examples/hunter/hunter-lead-input-example/)
- [Hunter Leads List Example](https://apis.io/examples/hunter/hunter-leads-list-example/)
- [Hunter Meta Example](https://apis.io/examples/hunter/hunter-meta-example/)
- [Hunter Pagination Meta Example](https://apis.io/examples/hunter/hunter-pagination-meta-example/)
- [Hunter Person Enrichment Example](https://apis.io/examples/hunter/hunter-person-enrichment-example/)
- [Hunter Source Example](https://apis.io/examples/hunter/hunter-source-example/)
- [Hunter Usage Counter Example](https://apis.io/examples/hunter/hunter-usage-counter-example/)
- [Hunter Verification Status Example](https://apis.io/examples/hunter/hunter-verification-status-example/)

#### Collections (14)

Postman and Open Collection request collections.

- [Hunter Account API](https://apis.io/collections/hunter/open-hunter-account-api/)
- [Hunter API](https://apis.io/collections/hunter/open-hunter-api/)
- [Hunter Account Campaigns API](https://apis.io/collections/hunter/open-hunter-campaigns-api/)
- [Hunter Account Combined Enrichment API](https://apis.io/collections/hunter/open-hunter-combined-enrichment-api/)
- [Hunter Account Company Enrichment API](https://apis.io/collections/hunter/open-hunter-company-enrichment-api/)
- [Hunter Account Discover API](https://apis.io/collections/hunter/open-hunter-discover-api/)
- [Hunter Account Domain Search API](https://apis.io/collections/hunter/open-hunter-domain-search-api/)
- [Hunter Account Email Count API](https://apis.io/collections/hunter/open-hunter-email-count-api/)
- [Hunter Account Email Enrichment API](https://apis.io/collections/hunter/open-hunter-email-enrichment-api/)
- [Hunter Account Email Finder API](https://apis.io/collections/hunter/open-hunter-email-finder-api/)
- [Hunter Account Email Verifier API](https://apis.io/collections/hunter/open-hunter-email-verifier-api/)
- [Hunter Account Leads API](https://apis.io/collections/hunter/open-hunter-leads-api/)
- [Hunter Account Leads Lists API](https://apis.io/collections/hunter/open-hunter-leads-lists-api/)
- [Hunter API](https://apis.io/collections/hunter/postman-hunter-api/)

#### Overlays (25)

OpenAPI overlays, including conversational phrasing for each operation.

- [Hunter Account Api Overlay](https://apis.io/overlays/hunter/hunter-account-api-overlay/)
- [Hunter Account Api Phrasing Overlay](https://apis.io/overlays/hunter/hunter-account-api-phrasing-overlay/)
- [Hunter Campaigns Api Overlay](https://apis.io/overlays/hunter/hunter-campaigns-api-overlay/)
- [Hunter Campaigns Api Phrasing Overlay](https://apis.io/overlays/hunter/hunter-campaigns-api-phrasing-overlay/)
- [Hunter Combined Enrichment Api Overlay](https://apis.io/overlays/hunter/hunter-combined-enrichment-api-overlay/)
- [Hunter Combined Enrichment Api Phrasing Overlay](https://apis.io/overlays/hunter/hunter-combined-enrichment-api-phrasing-overlay/)
- [Hunter Company Enrichment Api Overlay](https://apis.io/overlays/hunter/hunter-company-enrichment-api-overlay/)
- [Hunter Company Enrichment Api Phrasing Overlay](https://apis.io/overlays/hunter/hunter-company-enrichment-api-phrasing-overlay/)
- [Hunter Discover Api Overlay](https://apis.io/overlays/hunter/hunter-discover-api-overlay/)
- [Hunter Discover Api Phrasing Overlay](https://apis.io/overlays/hunter/hunter-discover-api-phrasing-overlay/)
- [Hunter Domain Search Api Overlay](https://apis.io/overlays/hunter/hunter-domain-search-api-overlay/)
- [Hunter Domain Search Api Phrasing Overlay](https://apis.io/overlays/hunter/hunter-domain-search-api-phrasing-overlay/)
- [Hunter Email Count Api Overlay](https://apis.io/overlays/hunter/hunter-email-count-api-overlay/)
- [Hunter Email Count Api Phrasing Overlay](https://apis.io/overlays/hunter/hunter-email-count-api-phrasing-overlay/)
- [Hunter Email Enrichment Api Overlay](https://apis.io/overlays/hunter/hunter-email-enrichment-api-overlay/)
- [Hunter Email Enrichment Api Phrasing Overlay](https://apis.io/overlays/hunter/hunter-email-enrichment-api-phrasing-overlay/)
- [Hunter Email Finder Api Overlay](https://apis.io/overlays/hunter/hunter-email-finder-api-overlay/)
- [Hunter Email Finder Api Phrasing Overlay](https://apis.io/overlays/hunter/hunter-email-finder-api-phrasing-overlay/)
- [Hunter Email Verifier Api Overlay](https://apis.io/overlays/hunter/hunter-email-verifier-api-overlay/)
- [Hunter Email Verifier Api Phrasing Overlay](https://apis.io/overlays/hunter/hunter-email-verifier-api-phrasing-overlay/)
- [Hunter Full Overlay](https://apis.io/overlays/hunter/hunter-full-overlay/)
- [Hunter Leads Api Overlay](https://apis.io/overlays/hunter/hunter-leads-api-overlay/)
- [Hunter Leads Api Phrasing Overlay](https://apis.io/overlays/hunter/hunter-leads-api-phrasing-overlay/)
- [Hunter Leads Lists Api Overlay](https://apis.io/overlays/hunter/hunter-leads-lists-api-overlay/)
- [Hunter Leads Lists Api Phrasing Overlay](https://apis.io/overlays/hunter/hunter-leads-lists-api-phrasing-overlay/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Hunter — jsonschema rules](https://apis.io/rules/hunter/hunter-jsonschema-spectral-rules/)
- [Hunter API Rules](https://apis.io/rules/hunter/hunter-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Hunter Authentication](https://apis.io/security/hunter/hunter-authentication/)
- [Hunter Domain Security](https://apis.io/security/hunter/hunter-domain-security/)
- [Hunter Vulnerability Disclosure](https://apis.io/security/hunter/hunter-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Hunter Scopes](https://apis.io/scopes/hunter/hunter-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Hunter Plans Pricing](https://apis.io/plans/hunter/hunter-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Hunter Rate Limits](https://apis.io/rate-limits/hunter/hunter-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Hunter Finops](https://apis.io/finops/hunter/hunter-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.hunter.io/)
- [Documentation](https://hunter.io/api-documentation/v2)
- [API reference](https://hunter.io/api-documentation/v2)
- [Pricing](https://hunter.io/pricing)
- [Support](https://help.hunter.io)
- [Changelog](https://hunter.io/changelog)
- [Blog](https://hunter.io/blog)
- [Security](https://hunter.io/security-policy)
- [Compliance](https://help.hunter.io/en/articles/1890029-gdpr-compliance)
- [Terms of service](https://hunter.io/terms)
- [Privacy policy](https://hunter.io/privacy-policy)
- [GitHub](https://github.com/hunter-io)
- [Status](https://status.hunter.io)

## API Evangelist rating

**Kin Score 69.1** — exemplar · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 68.3 |
| Contract quality | 63.7 |
| Contract governance | 45.5 |
| Operational transparency | 76.3 |
| Developer ergonomics | 60.7 |
| Access clarity | 67.1 |

**Agent readiness 61.0** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | documented (partial credit) |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | verified |
| Event Surface Described | yes |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |

**Regulatory alignment 41.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/hunter/](https://apis.io/providers/hunter/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Hunter: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/hunter/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
