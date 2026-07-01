# Persona (withpersona)

Persona (withpersona.com) is a configurable identity platform for KYC, KYB, AML, and fraud prevention. Its JSON:API-style REST API lets organizations run identity Inquiries, collect Verifications (government ID, selfie, database, document, phone, and email), pull watchlist and adverse-media Reports, manage review Cases, score Transactions, and orchestrate Workflows, all under `api.withpersona.com/api/v1`. Requests are authenticated with a Bearer API key and can be pinned to a dated `Persona-Version` and shaped with a `Key-Inflection` header.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/withpersona/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/withpersona/refs/heads/main/apis.yml)

## Tags

- Identity
- Identity Verification
- KYC
- KYB
- AML
- Fraud
- Compliance

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Persona Inquiries API

An Inquiry represents a single instance of an individual attempting to verify their identity against a template. Create, retrieve, list, search, update, approve, decline, mark-for-review, expire, resume, redact, tag, print to PDF, and generate one-time links for Inquiries.

- **Human URL:** [https://docs.withpersona.com/api-reference/inquiries](https://docs.withpersona.com/api-reference/inquiries)
- **Base URL:** `https://api.withpersona.com/api/v1`

#### Tags

- Inquiries
- Identity Verification
- Onboarding

#### Properties

- [Documentation](https://docs.withpersona.com/api-reference/inquiries)
- [API Reference](https://docs.withpersona.com/api-reference/inquiries)
- [OpenAPI](openapi/withpersona-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/withpersona.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/withpersona.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Persona Inquiry Sessions API

Inquiry Sessions represent an individual session within an Inquiry, letting you create, list, retrieve, expire, and generate one-time links so a person can resume a verification flow on another device.

- **Human URL:** [https://docs.withpersona.com/api-reference/inquiry-sessions](https://docs.withpersona.com/api-reference/inquiry-sessions)
- **Base URL:** `https://api.withpersona.com/api/v1`

#### Tags

- Inquiry Sessions
- Sessions

#### Properties

- [Documentation](https://docs.withpersona.com/api-reference/inquiry-sessions)
- [OpenAPI](openapi/withpersona-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Persona Accounts API

An Account is the persistent record of an end user across Inquiries. Create, retrieve, list, search, update, consolidate, redact, tag, and manage relations between Accounts, and run configured account actions.

- **Human URL:** [https://docs.withpersona.com/api-reference/accounts](https://docs.withpersona.com/api-reference/accounts)
- **Base URL:** `https://api.withpersona.com/api/v1`

#### Tags

- Accounts
- Identity
- Records

#### Properties

- [Documentation](https://docs.withpersona.com/api-reference/accounts)
- [OpenAPI](openapi/withpersona-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Persona Verifications API

A Verification answers whether an individual is who they claim to be across many types — government ID, government ID NFC, selfie, document, phone number, email address, and database checks (AAMVA, eCBSV, TIN, phone carrier, business, standard). Retrieve, redact, and print Verifications to PDF.

- **Human URL:** [https://docs.withpersona.com/api-reference/verifications](https://docs.withpersona.com/api-reference/verifications)
- **Base URL:** `https://api.withpersona.com/api/v1`

#### Tags

- Verifications
- Government ID
- Selfie
- Database

#### Properties

- [Documentation](https://docs.withpersona.com/api-reference/verifications)
- [OpenAPI](openapi/withpersona-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Persona Reports API

Reports run watchlist, adverse-media, PEP, and business lookups against an individual or entity. Create, retrieve, list, redact, tag, dismiss matches, pause/resume continuous monitoring, re-run, list history, and print to PDF.

- **Human URL:** [https://docs.withpersona.com/api-reference/reports](https://docs.withpersona.com/api-reference/reports)
- **Base URL:** `https://api.withpersona.com/api/v1`

#### Tags

- Reports
- Watchlist
- Adverse Media
- AML

#### Properties

- [Documentation](https://docs.withpersona.com/api-reference/reports)
- [OpenAPI](openapi/withpersona-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Persona Cases API

Cases group Persona objects (Inquiries, Accounts, Reports) for manual review. Create, retrieve, list, search, update, assign, set status, add or remove objects, tag, and redact Cases.

- **Human URL:** [https://docs.withpersona.com/api-reference/cases](https://docs.withpersona.com/api-reference/cases)
- **Base URL:** `https://api.withpersona.com/api/v1`

#### Tags

- Cases
- Case Management
- Manual Review

#### Properties

- [Documentation](https://docs.withpersona.com/api-reference/cases)
- [OpenAPI](openapi/withpersona-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Persona Transactions API

Transactions represent risk-scored events tied to an Account for ongoing fraud monitoring. Create, retrieve, list, update, tag, label, manage relations, redact, and redact transaction biometrics.

- **Human URL:** [https://docs.withpersona.com/api-reference/transactions](https://docs.withpersona.com/api-reference/transactions)
- **Base URL:** `https://api.withpersona.com/api/v1`

#### Tags

- Transactions
- Risk
- Fraud

#### Properties

- [Documentation](https://docs.withpersona.com/api-reference/transactions)
- [OpenAPI](openapi/withpersona-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Persona Devices API

Devices capture device-intelligence signals observed during a flow. List and retrieve Device records collected across Inquiries and Transactions.

- **Human URL:** [https://docs.withpersona.com/api-reference/devices](https://docs.withpersona.com/api-reference/devices)
- **Base URL:** `https://api.withpersona.com/api/v1`

#### Tags

- Devices
- Device Intelligence
- Fraud

#### Properties

- [Documentation](https://docs.withpersona.com/api-reference/devices)
- [OpenAPI](openapi/withpersona-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Persona Documents API

Documents are files collected during verification. Retrieve a Document, a government-ID document, or a generic uploaded document by ID.

- **Human URL:** [https://docs.withpersona.com/api-reference/documents](https://docs.withpersona.com/api-reference/documents)
- **Base URL:** `https://api.withpersona.com/api/v1`

#### Tags

- Documents
- Files

#### Properties

- [Documentation](https://docs.withpersona.com/api-reference/documents)
- [OpenAPI](openapi/withpersona-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Persona Webhooks API

Manage webhook subscriptions that deliver Persona events to your endpoints. Create, retrieve, list, update, enable, disable, archive, clone, and rotate the signing secret of a Webhook.

- **Human URL:** [https://docs.withpersona.com/api-reference/webhooks](https://docs.withpersona.com/api-reference/webhooks)
- **Base URL:** `https://api.withpersona.com/api/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.withpersona.com/api-reference/webhooks)
- [OpenAPI](openapi/withpersona-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Persona Events API

Events are the immutable, queryable record of everything that happens in your Persona account. List and retrieve Events for audit and reconciliation with webhook payloads.

- **Human URL:** [https://docs.withpersona.com/api-reference/events](https://docs.withpersona.com/api-reference/events)
- **Base URL:** `https://api.withpersona.com/api/v1`

#### Tags

- Events
- Audit

#### Properties

- [Documentation](https://docs.withpersona.com/api-reference/events)
- [OpenAPI](openapi/withpersona-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Persona Importers API

Importers bulk-load data into Persona lists. List and retrieve Importers and import accounts, names, emails, phone numbers, government ID numbers, IP addresses, geolocations, and faces into list objects.

- **Human URL:** [https://docs.withpersona.com/api-reference/importers](https://docs.withpersona.com/api-reference/importers)
- **Base URL:** `https://api.withpersona.com/api/v1`

#### Tags

- Importer
- Lists
- Bulk Import

#### Properties

- [Documentation](https://docs.withpersona.com/api-reference/importers)
- [OpenAPI](openapi/withpersona-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Persona Workflows API

Workflows automate business logic by triggering actions based on verification results or other events. Create a Workflow Run, retrieve a run, and list all Workflow Runs.

- **Human URL:** [https://docs.withpersona.com/api-reference/workflows](https://docs.withpersona.com/api-reference/workflows)
- **Base URL:** `https://api.withpersona.com/api/v1`

#### Tags

- Workflows
- Automation
- Orchestration

#### Properties

- [Documentation](https://docs.withpersona.com/api-reference/workflows)
- [OpenAPI](openapi/withpersona-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [GitHub Organization](https://github.com/persona-id)
- [LinkedIn](https://www.linkedin.com/company/withpersona)
- [Website](https://withpersona.com)
- [Documentation](https://docs.withpersona.com)
- [Plans](plans/withpersona-plans-pricing.yml)
- [Rate Limits](rate-limits/withpersona-rate-limits.yml)
- [Fin Ops](finops/withpersona-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
