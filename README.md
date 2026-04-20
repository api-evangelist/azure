# Microsoft Azure (azure)
Microsoft Azure is a comprehensive cloud computing platform offering IaaS, PaaS, and SaaS solutions through a global network of datacenters with REST APIs for all services.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/azure/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Cloud Computing, Databases, Infrastructure, Machine Learning, Networking, Platform as a Service, Storage

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-19

## APIs

### Microsoft Azure
Microsoft Azure is a comprehensive cloud computing platform offering IaaS, PaaS, and SaaS solutions through a global network of datacenters with REST APIs for all services.

**Human URL:** [https://learn.microsoft.com/en-us/rest/api/azure/](https://learn.microsoft.com/en-us/rest/api/azure/)

#### Tags:

 - Management, Resources, Subscriptions

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/rest/api/azure/)
- [OpenAPI](openapi/azure-management-openapi.yaml)

## Common Properties


## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Management](openapi/azure-management-openapi.yaml)

### JSON Schema

- [Subscription List Result](json-schema/azure-subscription-list-result-schema.json)
- [Resource Group](json-schema/azure-resource-group-schema.json)
- [Generic Resource](json-schema/azure-generic-resource-schema.json)
- [Resource List Result](json-schema/azure-resource-list-result-schema.json)
- [Subscription](json-schema/azure-subscription-schema.json)
- [Resource Group List Result](json-schema/azure-resource-group-list-result-schema.json)

### JSON-LD

- [Azure Context](json-ld/azure-context.jsonld)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Azure](capabilities/shared/azure.yaml)

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|----------|
| [Azure Management](capabilities/azure-management.yaml) | Microsoft Azure | 5 | Cloud Engineer |

## Vocabulary

- [Azure Vocabulary](vocabulary/azure-vocabulary.yaml)

## Rules

- [Azure Spectral Rules](rules/azure-spectral-rules.yml) — 15 rules enforcing Microsoft Azure API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
