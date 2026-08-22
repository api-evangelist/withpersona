# Persona (withpersona)

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
