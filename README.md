# IntakeQ (intakeq)

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
