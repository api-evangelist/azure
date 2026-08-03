# Microsoft Azure (azure)

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
