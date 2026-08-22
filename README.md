# TPP (SystmOne) (tpp-systmone)

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

TPP (The Phoenix Partnership) is a UK healthcare software company founded in 1997 and headquartered in Leeds, England. Its flagship clinical system, SystmOne, is one of the two dominant GP electronic health record platforms in England (alongside EMIS Web), holding 61M+ patient records shared across the NHS and serving 300,000+ users across 7,800+ organisations spanning general practice, hospitals, urgent care, mental health, community, and social care. Home market is the United Kingdom, exclusively within the NHS.

TPP does not run a public self-serve developer portal. API access is a gated, partner-conformance process: third parties integrate through NHS England's Interface Mechanism 1 (IM1) and the national GP Connect FHIR programme under the Digital Care Services framework and a Supplier Conformance Assessment List (SCAL), and/or via TPP's own Integration Request process and downloadable interface specifications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tpp-systmone/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tpp-systmone/refs/heads/main/apis.yml)

## Tags

- Healthcare
- United Kingdom
- EHR
- EMR
- FHIR
- HL7
- Interoperability
- GP Connect
- IM1
- National Health System

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

### SystmOne Client Integration API

Local client-integration interface for approved third-party applications to interact with a running SystmOne client, using XML documents (validated against published XSD schemas) over a TCP socket. Documented functions include PatientSearch, GetPatientRecord, UpdatePatientRecord, GetDocument, GetAppointmentSlots, GetDiary, DataExtract, and more.

- **Human URL:** [https://tpp-uk.com/resources/integration-request/](https://tpp-uk.com/resources/integration-request/)
- **Properties:** Specification (PDF v33.4), XSD Schemas, Example Messages — harvested verbatim into `schemas/`

### SystmOne Patient Facing Services (PFS) API

Patient-facing services API for appointment booking, prescription requests, and record access. Downloadable specification package.

- **Human URL:** [https://tpp-uk.com/resources/integration-request/](https://tpp-uk.com/resources/integration-request/)

### SystmOne Generic HTML API

Generic HTML API for embedding/launching third-party web content in context within the SystmOne client.

- **Human URL:** [https://tpp-uk.com/resources/integration-request/](https://tpp-uk.com/resources/integration-request/)

### SystmOne Telephony API

Telephony (CTI) integration for computer-telephony workflows such as inbound-call patient matching.

- **Human URL:** [https://tpp-uk.com/resources/integration-request/](https://tpp-uk.com/resources/integration-request/)

### Interface Mechanism 1 (IM1)

NHS England national route by which approved apps connect directly to SystmOne — Transaction API (real-time read/write), Bulk API (Strategic Reporting Extracts), and Patient Facing Services API. Onboarding via the Digital Care Services IM1 Pairing process and SCAL.

- **Human URL:** [https://digital.nhs.uk/developer/api-catalogue/interface-mechanism-1-standards](https://digital.nhs.uk/developer/api-catalogue/interface-mechanism-1-standards)

### GP Connect (FHIR)

NHS England's national FHIR-based interoperability programme. TPP SystmOne records are exposed through GP Connect's FHIR API for authorised record viewing and structured record access. Endpoints and CapabilityStatements are provisioned per-practice through the NHS Spine, secured with NHS-issued JWT — there is no single TPP-hosted FHIR base URL.

- **Human URL:** [https://digital.nhs.uk/services/gp-connect](https://digital.nhs.uk/services/gp-connect)

## Common Properties

- [Website](https://tpp-uk.com)
- [Developer Portal / Integration Request](https://tpp-uk.com/resources/integration-request/)
- [Getting Started (IM1 Pairing)](https://digital.nhs.uk/services/digital-services-for-integrated-care/im1-pairing-integration)
- [Blog / News & Insights](https://tpp-uk.com/news-insights/)
- [Support / Contact](https://tpp-uk.com/contact_us/)
- [Privacy Policy](https://tpp-uk.com/privacy-policy/)
- [Security (Cyber Essentials Plus)](https://tpp-uk.com/cyber-essentials-plus/)
- [Compliance (ISO 27001)](https://tpp-uk.com/iso-27001/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
