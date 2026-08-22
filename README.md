# Application Research (application-research)

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

Application Research is a topic collection focused on specifications for declaring application service integration dependencies. It covers five specification formats: Score (platform-agnostic workload specs), Cloud Native Application Bundle (CNAB), Open Component Model (OCM), Open Resource Discovery (ORD), and Radius — all aimed at enabling deployment teams to understand what services (APIs, databases, caches, message buses, blob stores) an application requires.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/application-research/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/application-research/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Application Dependencies
- Cloud Native
- Integration
- Research
- Specifications
- Workload Specifications

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Score Workload Specification API

Score is a platform-agnostic workload specification that enables developers to define their workloads once and deploy them across multiple platforms including Kubernetes, Docker, and Helm. The API manages workload spec lifecycle and platform translations.

- **Human URL:** [https://score.dev](https://score.dev)
- **Base URL:** `https://api.score.dev/v1`

#### Tags

- Platform Agnostic
- Score
- Workload Specification

#### Properties

- [Documentation](https://docs.score.dev)
- [OpenAPI](openapi/score-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/score.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/score.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/score.yml) — [JSON Schema](https://json-schema.org/specification)
- [Code Examples](examples/score-ecommerce.yml)
- [Code Examples](examples/score-ai-ml-inference-platform.yml)
- [Code Examples](examples/score-data-processing-pipeline.yml)

### Cloud Native Application Bundle API

CNAB (Cloud Native Application Bundle) is a specification for packaging and distributing cloud-native applications. The API manages bundle lifecycle including installation, upgrading, and uninstalling bundled applications across cloud environments.

- **Human URL:** [https://cnab.io](https://cnab.io)
- **Base URL:** `https://api.cnab.io/v1`

#### Tags

- Application Bundles
- Cloud Native
- Distribution

#### Properties

- [Documentation](https://cnab.io/docs)
- [OpenAPI](openapi/cloud-native-application-bundle-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/cloud-native-application-bundle.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cloud-native-application-bundle.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/cloud-native-application-bundle-schema.yml) — [JSON Schema](https://json-schema.org/specification)
- [Code Examples](examples/cloud-native-application-bundle-example-wordpress.yml)
- [Code Examples](examples/cloud-native-application-bundle-example-cassandra-cluster.yml)

### Open Component Model API

Open Component Model (OCM) provides a standard for describing software components in a supply chain, enabling teams to track, reference, and verify software artifacts.

- **Human URL:** [https://ocm.software](https://ocm.software)
- **Base URL:** `https://ocm.software/api/v1`

#### Tags

- Component Model
- Software Supply Chain
- Software Components

#### Properties

- [Documentation](https://ocm.software/docs)
- [OpenAPI](openapi/open-component-model-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/open-component-model.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/open-component-model.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/open-component-model.yml) — [JSON Schema](https://json-schema.org/specification)
- [Code Examples](examples/open-component-model-example-web-application.yml)

### Open Resource Discovery API

Open Resource Discovery (ORD) is a protocol for machine-readable resource and capability discovery, enabling API management platforms to automatically discover what services and APIs an application exposes.

- **Human URL:** [https://sap.github.io/open-resource-discovery/](https://sap.github.io/open-resource-discovery/)
- **Base URL:** `https://api.open-resource-discovery.org/v1`

#### Tags

- API Discovery
- Metadata
- Resource Discovery

#### Properties

- [Documentation](https://sap.github.io/open-resource-discovery/)
- [OpenAPI](openapi/open-resource-discovery-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/open-resource-discovery.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/open-resource-discovery.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/open-resource-discovery.yml) — [JSON Schema](https://json-schema.org/specification)
- [Code Examples](examples/open-resource-discovery-ecommerce.yml)

### Radius Application Platform API

Radius is an open-source, cloud-agnostic application platform that enables developers to define and deploy applications with their dependencies in a portable, declarative way across cloud providers.

- **Human URL:** [https://radapp.io](https://radapp.io)
- **Base URL:** `https://api.radapp.io/v1`

#### Tags

- Application Platform
- Cloud Agnostic
- Radius

#### Properties

- [Documentation](https://docs.radapp.io)
- [OpenAPI](openapi/radius-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/radius.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/radius.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/radius.yml) — [JSON Schema](https://json-schema.org/specification)
- [Code Examples](examples/radius-ecommerce-microservice.yml)

## Common Properties

- [GitHub Organization](https://github.com/api-evangelist)
- [JSON-LD](json-ld/application-research-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/application-research-spectral-rules.yml)
- [Vocabulary](vocabulary/application-research-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
