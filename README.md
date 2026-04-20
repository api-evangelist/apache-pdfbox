# Apache PDFBox (apache-pdfbox)
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
