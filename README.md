# Qgiv (qgiv)

Qgiv (now Bloomerang Fundraising) is an online donation, event registration, peer-to-peer fundraising, and payment processing platform for nonprofits, faith-based organizations, and schools. Qgiv was acquired by Bloomerang in January 2024 and now operates as Bloomerang's giving platform; the legacy Qgiv API documentation lives at qgiv.com/api and remains the documented programmatic surface for existing Qgiv forms and accounts. The API is a token-authenticated, form-scoped REST-style service at secure.qgiv.com/admin/api that accepts XML or JSON input and returns XML or JSON based on the URL extension, covering transactions, recurring donations, refunds, peer-to-peer registrations, events, account settings, custom fields, custom amounts, statements, and report mappings.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/qgiv/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/qgiv/refs/heads/main/apis.yml)

## Tags

- Nonprofit
- Fundraising
- Donations
- Payments
- Peer to Peer
- Events
- Bloomerang

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## APIs

### Qgiv Transactions API

Read-only reporting on Transactions for the current form or organization - the last N transactions, transactions after a given ID, transactions within a date range, and single transactions by ID, returned as XML or JSON.

- **Human URL:** [https://www.qgiv.com/api/reporting-transactions.php](https://www.qgiv.com/api/reporting-transactions.php)
- **Base URL:** `https://secure.qgiv.com/admin/api`

#### Properties

- [Documentation](https://www.qgiv.com/api/)
- [API Reference](https://www.qgiv.com/api/reporting-transactions.php)
- [OpenAPI](openapi/qgiv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/qgiv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qgiv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qgiv Recurring Donations API

Read-only reporting on recurring donation schedules - list all recurring transactions, filter by status (active, paused, expired, deleted), retrieve a single recurring transaction, and view an upcoming billing forecast by month.

- **Human URL:** [https://www.qgiv.com/api/reporting-recurring.php](https://www.qgiv.com/api/reporting-recurring.php)
- **Base URL:** `https://secure.qgiv.com/admin/api`

#### Properties

- [Documentation](https://www.qgiv.com/api/)
- [API Reference](https://www.qgiv.com/api/reporting-recurring.php)
- [OpenAPI](openapi/qgiv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/qgiv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qgiv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qgiv Refunds API

Read-only reporting on refunds associated with a form or organization - the last N refunds, refunds after a given ID, refunds within a date range, and a single refund by ID.

- **Human URL:** [https://www.qgiv.com/api/reporting-refunds.php](https://www.qgiv.com/api/reporting-refunds.php)
- **Base URL:** `https://secure.qgiv.com/admin/api`

#### Properties

- [Documentation](https://www.qgiv.com/api/)
- [API Reference](https://www.qgiv.com/api/reporting-refunds.php)
- [OpenAPI](openapi/qgiv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/qgiv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qgiv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qgiv Peer-to-Peer Registrations API

Read-only reporting on peer-to-peer fundraising event registrations - registrant details, team and fundraising-goal data, promo codes, and online/offline totals, listed by count, date range, or individual registration ID.

- **Human URL:** [https://www.qgiv.com/api/reporting-registrations.php](https://www.qgiv.com/api/reporting-registrations.php)
- **Base URL:** `https://secure.qgiv.com/admin/api`

#### Properties

- [Documentation](https://www.qgiv.com/api/)
- [API Reference](https://www.qgiv.com/api/reporting-registrations.php)
- [OpenAPI](openapi/qgiv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/qgiv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qgiv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qgiv Events API

List, retrieve, and update fundraising events configured on a Qgiv form - pricing tiers, ticket packages, custom fields, promo codes, start/end dates, address, and receipt settings.

- **Human URL:** [https://www.qgiv.com/api/events.php](https://www.qgiv.com/api/events.php)
- **Base URL:** `https://secure.qgiv.com/admin/api`

#### Properties

- [Documentation](https://www.qgiv.com/api/)
- [API Reference](https://www.qgiv.com/api/events.php)
- [OpenAPI](openapi/qgiv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/qgiv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qgiv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qgiv Account Settings API

Read and update organization and form-level account settings - organization title and contact information, and per-form settings such as active donation state and restriction class.

- **Human URL:** [https://www.qgiv.com/api/account-settings.php](https://www.qgiv.com/api/account-settings.php)
- **Base URL:** `https://secure.qgiv.com/admin/api`

#### Properties

- [Documentation](https://www.qgiv.com/api/)
- [API Reference](https://www.qgiv.com/api/account-settings.php)
- [OpenAPI](openapi/qgiv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/qgiv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qgiv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qgiv Custom Fields API

List, retrieve, create, and update custom fields on a donation form - labels, prompt content, input type, required/display rules across frontend, virtual terminal, kiosk, and mobile.

- **Human URL:** [https://www.qgiv.com/api/fields.php](https://www.qgiv.com/api/fields.php)
- **Base URL:** `https://secure.qgiv.com/admin/api`

#### Properties

- [Documentation](https://www.qgiv.com/api/)
- [API Reference](https://www.qgiv.com/api/fields.php)
- [OpenAPI](openapi/qgiv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/qgiv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qgiv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qgiv Custom Amounts API

List, retrieve, create, and update preset suggested-giving amounts (e.g. Bronze/Silver/Gold tiers) shown on a donation form.

- **Human URL:** [https://www.qgiv.com/api/amounts.php](https://www.qgiv.com/api/amounts.php)
- **Base URL:** `https://secure.qgiv.com/admin/api`

#### Properties

- [Documentation](https://www.qgiv.com/api/)
- [API Reference](https://www.qgiv.com/api/amounts.php)
- [OpenAPI](openapi/qgiv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/qgiv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qgiv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qgiv Statements API

Read-only reporting on monthly processing statements - amount contributed, processing percentage and fees, and the underlying transaction summary - listed in full, by ID, or the latest statement.

- **Human URL:** [https://www.qgiv.com/api/reporting-statements.php](https://www.qgiv.com/api/reporting-statements.php)
- **Base URL:** `https://secure.qgiv.com/admin/api`

#### Properties

- [Documentation](https://www.qgiv.com/api/)
- [API Reference](https://www.qgiv.com/api/reporting-statements.php)
- [OpenAPI](openapi/qgiv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/qgiv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qgiv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Qgiv Report Mappings API

List, retrieve, create, and update export/report mappings that link Qgiv identifiers (e.g. recurring frequency codes) to external reporting or export-service systems.

- **Human URL:** [https://www.qgiv.com/api/reporting-mappings.php](https://www.qgiv.com/api/reporting-mappings.php)
- **Base URL:** `https://secure.qgiv.com/admin/api`

#### Properties

- [Documentation](https://www.qgiv.com/api/)
- [API Reference](https://www.qgiv.com/api/reporting-mappings.php)
- [OpenAPI](openapi/qgiv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/qgiv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/qgiv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/qgiv)
- [Website](https://www.qgiv.com/)
- [Documentation](https://www.qgiv.com/api/)
- [Plans](plans/qgiv-plans-pricing.yml)
- [Rate Limits](rate-limits/qgiv-rate-limits.yml)
- [Fin Ops](finops/qgiv-finops.yml)

## Notes

- Qgiv was acquired by Bloomerang in January 2024 and now operates as Bloomerang Fundraising; `qgiv.com/pricing` redirects to `bloomerang.com/pricing`, but the legacy API documented at `qgiv.com/api` remains live and unchanged for existing Qgiv accounts.
- Authentication is a form-scoped API `token` passed as POST data - there is no OAuth or bearer-token layer, and no documented API versioning scheme.
- Input accepts XML or JSON via a `package` field on write operations; output format (XML vs JSON) is selected purely by the URL file extension.
- No documented public WebSocket API and no documented first-party webhook/push subscription endpoint exist - see [review.yml](review.yml) for the full assessment. Real-time-adjacent use cases are handled today via polling the reporting endpoints or third-party Zapier triggers.
- Numeric rate limits are not published for any endpoint (see [rate-limits/qgiv-rate-limits.yml](rate-limits/qgiv-rate-limits.yml)).

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
