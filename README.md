# SAML (saml)

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
