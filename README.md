# SAML (saml)

SAML (Security Assertion Markup Language) is an XML-based open standard for exchanging authentication and authorization data between identity providers and service providers. Ratified as an OASIS Standard in March 2005, SAML 2.0 enables single sign-on (SSO) across different applications and domains, reducing the need for users to manage multiple sets of credentials. It uses XML digital signatures and encryption to secure assertions exchanged between Identity Providers (IdP) and Service Providers (SP).

**APIs.json:** [https://www.oasis-open.org/standard/saml/](https://www.oasis-open.org/standard/saml/)

## Tags

- Authentication
- Authorization
- Federation
- Identity Management
- Open Standard
- Security
- Single Sign-On
- SSO
- XML

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### SAML 2.0 SSO HTTP Bindings API

API specification for SAML 2.0 Single Sign-On HTTP bindings including the HTTP Redirect Binding and HTTP POST Binding for AuthnRequest and Response exchange, Assertion Consumer Service, Single Logout, and metadata retrieval as defined in the OASIS SAML 2.0 Bindings specification (saml-bindings-2.0-os).

#### Tags

- Authentication
- Bindings
- HTTP
- Identity Provider
- Service Provider
- Single Sign-On
- SSO

#### Properties

- [OpenAPI](openapi/saml-sso-bindings.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/saml-sso-bindings.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/saml-sso-bindings.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.oasis-open.org/security/saml/v2.0/saml-bindings-2.0-os.pdf)

## Common Properties

- [Documentation](https://www.oasis-open.org/standard/saml/)
- [Documentation](https://docs.oasis-open.org/security/saml/Post2.0/sstc-saml-tech-overview-2.0.html)
- [Documentation](https://docs.oasis-open.org/security/saml/v2.0/saml-core-2.0-os.pdf)
- [Documentation](https://docs.oasis-open.org/security/saml/v2.0/saml-bindings-2.0-os.pdf)
- [Documentation](https://docs.oasis-open.org/security/saml/v2.0/saml-profiles-2.0-os.pdf)
- [JSON Schema](json-schema/saml-entity-descriptor.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/saml-authn-request.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/saml-assertion.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/saml-context.jsonld)
- [JSON Structure](json-structure/saml-assertion-structure.json)
- [Spectral Rules](rules/saml-rules.yml)
- [Example](examples/saml-sso-redirect-example.json)
- [Vocabulary](vocabulary/saml-vocabulary.yml)
