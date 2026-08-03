# Apache PDFBox (apache-pdfbox)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Apache PDFBox is an open-source Java library for working with PDF documents. It allows creation of new PDF documents, manipulation of existing documents, and the ability to extract content from documents with support for digital signatures.

**URL:** [https://raw.githubusercontent.com/api-evangelist/apache-pdfbox/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/apache-pdfbox/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Document Processing, Java, PDF, Text Extraction, Apache, Open Source

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache PDFBox
PDFBox provides a Java API for creating, manipulating, rendering, and extracting text and images from PDF documents, with support for digital signatures, form filling, PDF/A validation, and font handling.

**Human URL:** [https://pdfbox.apache.org/2.0/getting-started.html](https://pdfbox.apache.org/2.0/getting-started.html)

#### Tags:

 - Document Processing, Java, PDF, Apache, Open Source

#### Properties

- [Documentation](https://pdfbox.apache.org/2.0/getting-started.html)
- [OpenAPI](openapi/apache-pdfbox-api.yaml)

## Common Properties

- [GitHubOrganization](https://github.com/apache/pdfbox)
- [Documentation](https://pdfbox.apache.org/)
- [SpectralRules](rules/apache-pdfbox-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-pdfbox-vocabulary.yaml)
- [NaftikoCapability](capabilities/pdfbox-workflow.yaml)
- [JSON-LD](json-ld/apache-pdfbox-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| PDF Text Extraction | Extract plain text and structured content from PDF documents |
| PDF Creation | Create new PDF documents programmatically with Java API |
| PDF Manipulation | Merge, split, rotate, and resize pages in existing PDFs |
| Digital Signatures | Apply and verify digital signatures for document authenticity |
| Form Filling | Read and fill interactive PDF forms (AcroForms) |
| PDF/A Validation | Validate and create PDF/A documents for archiving |
| Font Handling | Embed and extract fonts, handle Type 1, TrueType, and OpenType |

## Use Cases

| Name | Description |
|------|-------------|
| Invoice Processing | Extract data from PDF invoices for automated processing |
| Document Generation | Generate PDF reports, contracts, and certificates programmatically |
| Legal Document Management | Digitally sign and verify legal documents |
| Form Data Collection | Fill PDF forms and extract submitted data |
| Archive Management | Convert documents to PDF/A for long-term archiving |

## Integrations

| Name | Description |
|------|-------------|
| Apache Tika | Content detection and text extraction integration |
| Spring Boot | Spring Boot starter for PDF processing in web applications |
| Maven Central | Available as org.apache.pdfbox on Maven Central |
| iText/OpenPDF | Complementary PDF library for advanced PDF generation |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache PDFBox API](openapi/apache-pdfbox-api.yaml)

### JSON Schema

- [Document Info](json-schema/apache-pdfbox-document-info-schema.json)
- [Page Info](json-schema/apache-pdfbox-page-info-schema.json)
- [Document Metadata](json-schema/apache-pdfbox-document-metadata-schema.json)
- [Form Field](json-schema/apache-pdfbox-form-field-schema.json)
- [And more...](json-schema/)

### JSON Structure

- [Apache PDFBox JSON Structures](json-structure/)

### JSON-LD

- [Apache PDFBox Context](json-ld/apache-pdfbox-context.jsonld)

### Examples

- [Apache PDFBox Examples](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Document Processing Workflow](capabilities/pdfbox-workflow.yaml) | Apache PDFBox | 8 | Document Manager, Application Developer |

## Vocabulary

- [Apache PDFBox Vocabulary](vocabulary/apache-pdfbox-vocabulary.yaml) — Unified taxonomy mapping PDF processing resources, actions, workflows, and personas

## Rules

- [Apache PDFBox Spectral Rules](rules/apache-pdfbox-spectral-rules.yml) — Rules enforcing Apache PDFBox API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
