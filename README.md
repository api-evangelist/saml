# SAML

SAML (Security Assertion Markup Language) is an XML-based open standard for exchanging authentication and authorization data between identity providers and service providers. Ratified as an OASIS Standard in March 2005, SAML 2.0 enables single sign-on (SSO) across different applications and domains, reducing the need for users to manage multiple sets of credentials. It uses XML digital signatures and encryption to secure assertions exchanged between Identity Providers (IdP) and Service Providers (SP).

**URL:** [SAML 2.0 OASIS Standard](https://www.oasis-open.org/standard/saml/)

## Tags

Authentication, Authorization, Federation, Identity Management, Open Standard, Security, Single Sign-On, SSO, XML

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-02

## APIs

### SAML 2.0 SSO HTTP Bindings API

API specification for SAML 2.0 Single Sign-On HTTP bindings including the HTTP Redirect Binding and HTTP POST Binding for AuthnRequest and Response exchange, Assertion Consumer Service, Single Logout, and metadata retrieval as defined in the OASIS SAML 2.0 Bindings specification.

#### Tags

Authentication, Bindings, HTTP, Identity Provider, Service Provider, Single Sign-On, SSO

#### Properties

- [OpenAPI](openapi/saml-sso-bindings.yml)
- [Documentation](https://docs.oasis-open.org/security/saml/v2.0/saml-bindings-2.0-os.pdf)

## Common Properties

- [Documentation](https://www.oasis-open.org/standard/saml/) — SAML 2.0 OASIS Standard
- [Documentation](https://docs.oasis-open.org/security/saml/Post2.0/sstc-saml-tech-overview-2.0.html) — SAML 2.0 Technical Overview
- [Documentation](https://docs.oasis-open.org/security/saml/v2.0/saml-core-2.0-os.pdf) — SAML 2.0 Core Specification
- [Documentation](https://docs.oasis-open.org/security/saml/v2.0/saml-bindings-2.0-os.pdf) — SAML 2.0 Bindings Specification
- [Documentation](https://docs.oasis-open.org/security/saml/v2.0/saml-profiles-2.0-os.pdf) — SAML 2.0 Profiles Specification

## JSON Schema

- [json-schema/saml-entity-descriptor.json](json-schema/saml-entity-descriptor.json) — SAML 2.0 EntityDescriptor Metadata
- [json-schema/saml-authn-request.json](json-schema/saml-authn-request.json) — SAML 2.0 AuthnRequest
- [json-schema/saml-assertion.json](json-schema/saml-assertion.json) — SAML 2.0 Assertion

## JSON Structure

- [json-structure/saml-assertion-structure.json](json-structure/saml-assertion-structure.json) — SAML 2.0 Assertion Structure

## JSON-LD

- [json-ld/saml-context.jsonld](json-ld/saml-context.jsonld) — SAML 2.0 JSON-LD Context

## Rules

- [rules/saml-rules.yml](rules/saml-rules.yml) — SAML API Spectral Rules

## Capabilities

### Shared Definitions

- [capabilities/shared/saml-sso-bindings.yaml](capabilities/shared/saml-sso-bindings.yaml) — SAML 2.0 SSO HTTP Bindings

### Workflow Capabilities

- [capabilities/single-sign-on.yaml](capabilities/single-sign-on.yaml) — SAML 2.0 Single Sign-On (SSO + SLO + Metadata)

## Examples

- [examples/saml-sso-redirect-example.json](examples/saml-sso-redirect-example.json) — SAML SSO HTTP Redirect Binding Example

## Vocabulary

- [vocabulary/saml-vocabulary.yml](vocabulary/saml-vocabulary.yml) — SAML 2.0 Vocabulary
