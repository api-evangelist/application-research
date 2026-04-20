# Application Research (application-research)
Application Research is a topic collection focused on specifications for declaring application service integration dependencies. It covers five specification formats: Score (platform-agnostic workload specs), Cloud Native Application Bundle (CNAB), Open Component Model (OCM), Open Resource Discovery (ORD), and Radius — all aimed at enabling deployment teams to understand what services (APIs, databases, caches, message buses, blob stores) an application requires.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/application-research/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Application Dependencies, Cloud Native, Integration, Research, Specifications, Workload Specifications

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Score Workload Specification API
Score is a platform-agnostic workload specification that enables developers to define their workloads once and deploy them across multiple platforms including Kubernetes, Docker, and Helm.

**Human URL:** [https://score.dev](https://score.dev)

#### Tags:

 - Platform Agnostic, Score, Workload Specification

#### Properties

- [Documentation](https://docs.score.dev)
- [OpenAPI](openapi/score-openapi.yml)
- [JSONSchema](json-schema/score.yml)
- [CodeExamples - E-Commerce Example](examples/score-ecommerce.yml)
- [CodeExamples - AI/ML Inference Example](examples/score-ai-ml-inference-platform.yml)
- [CodeExamples - Data Processing Example](examples/score-data-processing-pipeline.yml)

### Cloud Native Application Bundle API
CNAB (Cloud Native Application Bundle) is a specification for packaging and distributing cloud-native applications with full lifecycle management.

**Human URL:** [https://cnab.io](https://cnab.io)

#### Tags:

 - Application Bundles, Cloud Native, Distribution

#### Properties

- [Documentation](https://cnab.io/docs)
- [OpenAPI](openapi/cloud-native-application-bundle-openapi.yml)
- [JSONSchema](json-schema/cloud-native-application-bundle-schema.yml)
- [CodeExamples - WordPress Bundle Example](examples/cloud-native-application-bundle-example-wordpress.yml)
- [CodeExamples - Cassandra Cluster Example](examples/cloud-native-application-bundle-example-cassandra-cluster.yml)

### Open Component Model API
Open Component Model (OCM) provides a standard for describing software components in a supply chain.

**Human URL:** [https://ocm.software](https://ocm.software)

#### Tags:

 - Component Model, Software Supply Chain, Software Components

#### Properties

- [Documentation](https://ocm.software/docs)
- [OpenAPI](openapi/open-component-model-openapi.yml)
- [JSONSchema](json-schema/open-component-model.yml)
- [CodeExamples - Web Application Example](examples/open-component-model-example-web-application.yml)

### Open Resource Discovery API
Open Resource Discovery (ORD) is a protocol for machine-readable resource and capability discovery.

**Human URL:** [https://sap.github.io/open-resource-discovery/](https://sap.github.io/open-resource-discovery/)

#### Tags:

 - API Discovery, Metadata, Resource Discovery

#### Properties

- [Documentation](https://sap.github.io/open-resource-discovery/)
- [OpenAPI](openapi/open-resource-discovery-openapi.yml)
- [JSONSchema](json-schema/open-resource-discovery.yml)
- [CodeExamples - E-Commerce Discovery Example](examples/open-resource-discovery-ecommerce.yml)

### Radius Application Platform API
Radius is an open-source, cloud-agnostic application platform for defining and deploying applications with their dependencies portably across cloud providers.

**Human URL:** [https://radapp.io](https://radapp.io)

#### Tags:

 - Application Platform, Cloud Agnostic, Radius

#### Properties

- [Documentation](https://docs.radapp.io)
- [OpenAPI](openapi/radius-openapi.yml)
- [JSONSchema](json-schema/radius.yml)
- [CodeExamples - E-Commerce Microservice Example](examples/radius-ecommerce-microservice.yml)

## Common Properties

- [GitHubOrganization](https://github.com/api-evangelist)

## Features

| Name | Description |
|------|-------------|
| Platform-Agnostic Workload Specs | Score enables defining workloads once and deploying across multiple platforms |
| Application Bundle Packaging | CNAB provides standardized packaging and distribution of cloud-native applications |
| Software Supply Chain Tracking | OCM enables tracking and verifying software components through delivery pipelines |
| Automatic API Discovery | ORD enables machines to discover what resources and APIs an application exposes |
| Cloud-Agnostic Dependency Declarations | Radius enables portable application definitions with dependency declarations across clouds |

## Use Cases

| Name | Description |
|------|-------------|
| Multi-Platform Deployment | Define an application once and deploy it across Kubernetes, Docker, or cloud platforms |
| Dependency Documentation | Explicitly declare all required services (databases, caches, queues) for an application |
| Software Supply Chain Security | Track and verify software component provenance and integrity |
| API Landscape Discovery | Enable API management platforms to automatically discover application capabilities |
| Cloud Migration | Move applications between cloud providers without rewriting configuration |

## Integrations

| Name | Description |
|------|-------------|
| Kubernetes | Primary deployment target for Score, CNAB, OCM, and Radius specs |
| Helm | Score and CNAB support Helm-based deployment and chart generation |
| Docker | Score workloads can be compiled to Docker Compose files |
| Terraform | Radius integrates with Terraform for infrastructure provisioning |
| ArgoCD | GitOps-based deployment of Score and CNAB bundles via ArgoCD |
| Backstage | ORD integrations enable Backstage service catalog population |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Score Workload Specification API](openapi/score-openapi.yml)
- [Cloud Native Application Bundle API](openapi/cloud-native-application-bundle-openapi.yml)
- [Open Component Model API](openapi/open-component-model-openapi.yml)
- [Open Resource Discovery API](openapi/open-resource-discovery-openapi.yml)
- [Radius Application Platform API](openapi/radius-openapi.yml)

### JSON Schema

- [Score Schema](json-schema/score.yml)
- [Cloud Native Application Bundle Schema](json-schema/cloud-native-application-bundle-schema.yml)
- [Open Component Model Schema](json-schema/open-component-model.yml)
- [Open Resource Discovery Schema](json-schema/open-resource-discovery.yml)
- [Radius Schema](json-schema/radius.yml)

### JSON Structure

- [Score Structure](json-structure/score-structure.json)
- [Cloud Native Application Bundle Structure](json-structure/cloud-native-application-bundle-schema-structure.json)
- [Open Component Model Structure](json-structure/open-component-model-structure.json)
- [Open Resource Discovery Structure](json-structure/open-resource-discovery-structure.json)
- [Radius Structure](json-structure/radius-structure.json)

### JSON-LD

- [Application Research Context](json-ld/application-research-context.jsonld)

## Vocabulary

- [Application Research Vocabulary](vocabulary/application-research-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 8 actions, and 3 domains across 5 application dependency specification formats

## Rules

- [Application Research Spectral Rules](rules/application-research-spectral-rules.yml) — 20 rules across 7 categories enforcing application research API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
