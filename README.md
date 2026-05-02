# ScanSource

ScanSource is an international technology distributor founded in 1992, specializing in point-of-sale (POS), payments, barcode, physical security, unified communications, collaboration, telecom, and cloud services. ScanSource provides APIs that give partners real-time access to inventory, pricing, order management, and invoicing data to automate the full distribution sales cycle.

**URL:** [https://www.scansource.com](https://www.scansource.com)

## Tags

 - ScanSource, Distribution, Barcode, Point Of Sale, AIDC, Inventory, Order Management, E-Commerce

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs

### ScanSource Product API

The ScanSource Product API provides real-time product information, pricing, and availability checks for technology distribution partners. Supports single and batch queries (up to 40 items per request) for pricing lookups, availability checks, and product search.

**Human URL:** [https://services.scansource.com/api/Help](https://services.scansource.com/api/Help)

#### Tags

 - Products, Pricing, Availability, Inventory

#### Properties

- [Documentation](https://services.scansource.com/api/Help)
- [OpenAPI](openapi/scansource-product-openapi.yml)
- [JSON Schema](json-schema/scansource-product-schema.json)

### ScanSource Sales Order API

The ScanSource Sales Order API enables partners to create, track, and manage purchase orders programmatically. Supports synchronous and asynchronous order creation, order status queries, shipping quotes, order cancellation, and serial number tracking.

**Human URL:** [https://services.scansource.com/api/Help](https://services.scansource.com/api/Help)

#### Tags

 - Orders, Sales, Commerce, Fulfillment

#### Properties

- [Documentation](https://services.scansource.com/api/Help)
- [OpenAPI](openapi/scansource-sales-order-openapi.yml)
- [JSON Schema](json-schema/scansource-order-schema.json)

### ScanSource Invoice API

The ScanSource Invoice API provides access to invoicing data including invoice summaries, detailed invoice lists, individual invoice details, and PDF exports. Supports filtering by date range, sales order number, invoice number, and purchase order number.

**Human URL:** [https://services.scansource.com/api/Help](https://services.scansource.com/api/Help)

#### Tags

 - Invoices, Billing, Finance, Accounting

#### Properties

- [Documentation](https://services.scansource.com/api/Help)
- [OpenAPI](openapi/scansource-invoice-openapi.yml)

## Common Properties

- [Website](https://www.scansource.com)
- [Developer Portal](https://partnerportal.scansource.com)
- [Documentation](https://services.scansource.com/api/Help)
- [Getting Started](https://partnerportal.scansource.com/getstarted)
- [Partner Portal](https://partnerdevportal.scansource.com)

## OpenAPI Specifications

| Spec | Description |
|---|---|
| [scansource-product-openapi.yml](openapi/scansource-product-openapi.yml) | Product catalog, pricing, and availability API |
| [scansource-sales-order-openapi.yml](openapi/scansource-sales-order-openapi.yml) | Sales order creation, tracking, and management |
| [scansource-invoice-openapi.yml](openapi/scansource-invoice-openapi.yml) | Invoice retrieval, filtering, and PDF export |

## Spectral Rules

| Ruleset | Description |
|---|---|
| [scansource-rules.yml](rules/scansource-rules.yml) | Spectral ruleset enforcing ScanSource API conventions |

## Capabilities

### Shared Definitions

| Capability | Description |
|---|---|
| [shared/product.yaml](capabilities/shared/product.yaml) | ScanSource Product API consumed definition |
| [shared/sales-order.yaml](capabilities/shared/sales-order.yaml) | ScanSource Sales Order API consumed definition |
| [shared/invoice.yaml](capabilities/shared/invoice.yaml) | ScanSource Invoice API consumed definition |

### Workflow Capabilities

| Capability | APIs | Tools |
|---|---|---|
| [partner-commerce.yaml](capabilities/partner-commerce.yaml) | Product + Sales Order + Invoice | 12 tools |

## JSON Schema

| Schema | Description |
|---|---|
| [scansource-product-schema.json](json-schema/scansource-product-schema.json) | Product catalog entity schema |
| [scansource-order-schema.json](json-schema/scansource-order-schema.json) | Sales order entity schema |

## JSON Structure

| Structure | Description |
|---|---|
| [scansource-product-structure.json](json-structure/scansource-product-structure.json) | Product data structure documentation |

## JSON-LD

| Context | Description |
|---|---|
| [scansource-context.jsonld](json-ld/scansource-context.jsonld) | JSON-LD context mapping ScanSource terms to schema.org |

## Examples

| Example | Description |
|---|---|
| [scansource-product-availability-example.json](examples/scansource-product-availability-example.json) | Batch product availability check request/response |
| [scansource-create-order-example.json](examples/scansource-create-order-example.json) | Sales order creation request/response |

## Vocabulary

| Vocabulary | Description |
|---|---|
| [scansource-vocabulary.yml](vocabulary/scansource-vocabulary.yml) | ScanSource domain vocabulary and terminology |

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
