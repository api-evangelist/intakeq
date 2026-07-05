# IntakeQ (intakeq)

IntakeQ is a HIPAA-compliant practice management platform for health and wellness practitioners - therapists, chiropractors, counselors, dietitians, and other small practices. It provides secure electronic intake forms, e-signatures, and document sharing, and through its PracticeQ tier adds appointment scheduling, a booking widget, a secure client portal, payments and invoicing, treatment notes, telehealth, and insurance billing. IntakeQ publishes a documented REST API under `https://intakeq.com/api/v1` authenticated with an `X-Auth-Key` header, covering clients, appointments, intake questionnaires, treatment notes, invoices, and file attachments, plus webhooks for intake completion, note locking, and invoice events.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/intakeq/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/intakeq/refs/heads/main/apis.yml)

## Tags

- Practice Management
- Intake Forms
- Scheduling
- Health and Wellness
- EHR
- Telehealth
- HIPAA

## Timestamps

- **Created:** 2026-07-05
- **Modified:** 2026-07-05

## APIs

### IntakeQ Clients API

Query, create, and update clients (patients) in an IntakeQ account, search by name, email, client ID, custom fields, external ID, or created/updated date ranges, add and remove client tags, and retrieve a client's diagnoses.

- **Human URL:** [https://support.intakeq.com/article/251-intakeq-client-api](https://support.intakeq.com/article/251-intakeq-client-api)
- **Base URL:** `https://intakeq.com/api/v1`

#### Tags

- Clients
- Patients
- CRM

#### Properties

- [API Reference](https://support.intakeq.com/article/251-intakeq-client-api)
- [Documentation](https://support.intakeq.com/category/560-api)
- [OpenAPI](openapi/intakeq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/intakeq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/intakeq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IntakeQ Appointments API

Query appointments by client, date range, status, or practitioner, retrieve a single appointment, read booking settings (services, locations, practitioners), and create, update, or cancel appointments in the PracticeQ scheduler.

- **Human URL:** [https://support.intakeq.com/article/204-intakeq-appointments-api](https://support.intakeq.com/article/204-intakeq-appointments-api)
- **Base URL:** `https://intakeq.com/api/v1`

#### Tags

- Appointments
- Scheduling
- Booking

#### Properties

- [API Reference](https://support.intakeq.com/article/204-intakeq-appointments-api)
- [Documentation](https://support.intakeq.com/category/560-api)
- [OpenAPI](openapi/intakeq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/intakeq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/intakeq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IntakeQ Intake Forms API

Query intake form summaries, retrieve a completed intake as JSON or download it as a PDF (including individual consent forms), send or resend a questionnaire to a client, update office-use-only answers, and list available questionnaire templates and account practitioners.

- **Human URL:** [https://support.intakeq.com/article/31-intakeq-api](https://support.intakeq.com/article/31-intakeq-api)
- **Base URL:** `https://intakeq.com/api/v1`

#### Tags

- Intake Forms
- Questionnaires
- Consent Forms

#### Properties

- [API Reference](https://support.intakeq.com/article/31-intakeq-api)
- [Documentation](https://support.intakeq.com/category/560-api)
- [OpenAPI](openapi/intakeq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/intakeq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/intakeq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IntakeQ Treatment Notes API

Query treatment note summaries by client, status, or date range, retrieve the full JSON of a locked treatment note, and download a treatment note as a PDF. A note-locked webhook notifies external systems when staff lock a note.

- **Human URL:** [https://support.intakeq.com/article/342-intakeq-notes-api](https://support.intakeq.com/article/342-intakeq-notes-api)
- **Base URL:** `https://intakeq.com/api/v1`

#### Tags

- Treatment Notes
- Clinical Documentation
- SOAP Notes

#### Properties

- [API Reference](https://support.intakeq.com/article/342-intakeq-notes-api)
- [Documentation](https://support.intakeq.com/category/560-api)
- [OpenAPI](openapi/intakeq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/intakeq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/intakeq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IntakeQ Invoices API

Query invoices by client, date range, status, practitioner, or invoice number, and retrieve a single invoice by ID. An invoice-events webhook fires on issue, payment, refund, cancellation, and failed auto-charge or payment-plan charge events.

- **Human URL:** [https://support.intakeq.com/article/385-intakeq-invoice-api](https://support.intakeq.com/article/385-intakeq-invoice-api)
- **Base URL:** `https://intakeq.com/api/v1`

#### Tags

- Invoices
- Billing
- Payments

#### Properties

- [API Reference](https://support.intakeq.com/article/385-intakeq-invoice-api)
- [Documentation](https://support.intakeq.com/category/560-api)
- [OpenAPI](openapi/intakeq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/intakeq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/intakeq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IntakeQ Files API

List a client's files and the account's folders, download a file by ID, upload a new file to a client's record, and delete a file. Used to move documents and attachments in and out of a client's secure file repository.

- **Human URL:** [https://support.intakeq.com/article/430-intakeq-files-api](https://support.intakeq.com/article/430-intakeq-files-api)
- **Base URL:** `https://intakeq.com/api/v1`

#### Tags

- Files
- Attachments
- Documents

#### Properties

- [API Reference](https://support.intakeq.com/article/430-intakeq-files-api)
- [Documentation](https://support.intakeq.com/category/560-api)
- [OpenAPI](openapi/intakeq-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/intakeq.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/intakeq.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/intakeq)
- [Website](https://intakeq.com)
- [Documentation](https://support.intakeq.com/category/560-api)
- [Plans](plans/intakeq-plans-pricing.yml)
- [Rate Limits](rate-limits/intakeq-rate-limits.yml)
- [Fin Ops](finops/intakeq-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
