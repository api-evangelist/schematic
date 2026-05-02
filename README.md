# Schematic

Schematic is a feature and entitlement management platform for SaaS companies, providing pricing, packaging, and metering capabilities. It enables engineering and product teams to manage feature flags, define subscription plans, track feature usage, and control customer entitlements without code changes. Schematic raised $6.5M in April 2026 and launched an official Stripe App for entitlement management as a first-class billing primitive.

**Human URL:** [https://schematichq.com/](https://schematichq.com/)

## Resources

- [Documentation](https://docs.schematichq.com/)
- [API Reference](https://docs.schematichq.com/api-reference)
- [Pricing](https://schematichq.com/pricing)
- [Blog](https://schematichq.com/blog)
- [Changelog](https://schematichq.com/changelog)
- [GitHub Organization](https://github.com/SchematicHQ)
- [LinkedIn](https://www.linkedin.com/company/schematichq)

## SDKs

| Language | Repository |
|---|---|
| Python | [schematic-python](https://github.com/SchematicHQ/schematic-python) |
| Node.js | [schematic-node](https://github.com/SchematicHQ/schematic-node) |
| Go | [schematic-go](https://github.com/SchematicHQ/schematic-go) |
| Ruby | [schematic-ruby](https://github.com/SchematicHQ/schematic-ruby) |
| Java | [schematic-java](https://github.com/SchematicHQ/schematic-java) |
| PHP | [schematic-php](https://github.com/SchematicHQ/schematic-php) |
| C# | [schematic-csharp](https://github.com/SchematicHQ/schematic-csharp) |

## Artifacts

### OpenAPI

- [schematic-openapi.yml](openapi/schematic-openapi.yml) — Full Schematic REST API specification (OpenAPI 3.0)

### Rules

- [schematic-rules.yml](rules/schematic-rules.yml) — Spectral ruleset for Schematic API conventions

### Capabilities

**Workflow Capabilities:**
- [feature-management.yaml](capabilities/feature-management.yaml) — Feature flags, features, plans, and entitlements management
- [customer-management.yaml](capabilities/customer-management.yaml) — Companies, users, event tracking, and analytics

**Shared Definitions:**
- [capabilities/shared/schematic-api.yaml](capabilities/shared/schematic-api.yaml) — Full Schematic API consumed definition

### JSON Schema

- [schematic-company-schema.json](json-schema/schematic-company-schema.json) — Company resource schema
- [schematic-feature-schema.json](json-schema/schematic-feature-schema.json) — Feature resource schema
- [schematic-plan-schema.json](json-schema/schematic-plan-schema.json) — Plan resource schema

### JSON Structure

- [schematic-api-structure.json](json-structure/schematic-api-structure.json) — API resource group structure

### JSON-LD

- [schematic-context.jsonld](json-ld/schematic-context.jsonld) — Linked data context for Schematic vocabulary

### Examples

- [schematic-check-flag-example.json](examples/schematic-check-flag-example.json) — Check a feature flag
- [schematic-upsert-company-example.json](examples/schematic-upsert-company-example.json) — Upsert a company
- [schematic-create-plan-example.json](examples/schematic-create-plan-example.json) — Create a subscription plan
- [schematic-track-event-example.json](examples/schematic-track-event-example.json) — Track a usage event

### Vocabulary

- [schematic-vocabulary.yml](vocabulary/schematic-vocabulary.yml) — Domain vocabulary for Schematic concepts

## Maintainers

**Kin Lane** — kin@apievangelist.com
