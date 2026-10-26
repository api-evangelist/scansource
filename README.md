# ScanSource (scansource)

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

ScanSource is an international technology distributor specializing in point-of-sale (POS), payments, barcode, physical security, unified communications, collaboration, telecom, and cloud services. Founded in 1992 in Greenville, South Carolina, ScanSource provides APIs that give partners real-time access to inventory, pricing, order management, and product information to automate the sales cycle and integrate with backend ERP systems and customer portals.

**APIs.json:** [https://github.com/api-evangelist/scansource](https://github.com/api-evangelist/scansource)

## Tags

- ScanSource
- Distribution
- Barcode
- Point Of Sale
- AIDC
- Inventory
- Order Management
- E-Commerce

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs

### ScanSource Product API

The ScanSource Product API provides real-time product information, pricing, and availability checks for technology distribution partners. Supports single and batch queries for up to 40 items per request, with integration targets including ERP systems, sales tools, and customer self-service portals.

- **Human URL:** [https://services.scansource.com/api/Help](https://services.scansource.com/api/Help)
- **Base URL:** `https://services.scansource.com/api`

#### Tags

- Products
- Pricing
- Availability
- Inventory

#### Properties

- [Documentation](https://services.scansource.com/api/Help)
- [OpenAPI](openapi/scansource-product-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scansource-product.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scansource-product.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/scansource-product-schema.json) — [JSON Schema](https://json-schema.org/specification)

### ScanSource Sales Order API

The ScanSource Sales Order API enables partners to create, track, and manage purchase orders programmatically. Supports synchronous and asynchronous order creation, order status queries, shipping quotes, order cancellation, and serial number tracking.

- **Human URL:** [https://services.scansource.com/api/Help](https://services.scansource.com/api/Help)
- **Base URL:** `https://services.scansource.com/api`

#### Tags

- Orders
- Sales
- Commerce
- Fulfillment

#### Properties

- [Documentation](https://services.scansource.com/api/Help)
- [OpenAPI](openapi/scansource-sales-order-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scansource-sales-order.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scansource-sales-order.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/scansource-order-schema.json) — [JSON Schema](https://json-schema.org/specification)

### ScanSource Invoice API

The ScanSource Invoice API provides access to invoicing data including invoice summaries, detailed invoice lists, individual invoice details, and PDF exports. Supports filtering by date range, sales order number, invoice number, and purchase order number.

- **Human URL:** [https://services.scansource.com/api/Help](https://services.scansource.com/api/Help)
- **Base URL:** `https://services.scansource.com/api`

#### Tags

- Invoices
- Billing
- Finance
- Accounting

#### Properties

- [Documentation](https://services.scansource.com/api/Help)
- [OpenAPI](openapi/scansource-invoice-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scansource-invoice.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scansource-invoice.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/scansource)
- [Website](https://www.scansource.com)
- [Developer Portal](https://partnerportal.scansource.com)
- [Documentation](https://services.scansource.com/api/Help)
- [Getting Started](https://partnerportal.scansource.com/getstarted)
- [Partner Portal](https://partnerdevportal.scansource.com)
- [Spectral Rules](rules/scansource-rules.yml)
- [JSON Structure](json-structure/scansource-product-structure.json)
- [J S O N L D Context](json-ld/scansource-context.jsonld)
- [Vocabulary](vocabulary/scansource-vocabulary.yml)
- [Capabilities](capabilities/partner-commerce.yaml)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
