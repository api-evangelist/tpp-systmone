# TPP (SystmOne) (tpp-systmone)

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
