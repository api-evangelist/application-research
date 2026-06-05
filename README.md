# Application Research (application-research)

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
