# CSG Systems (csg)

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

CSG is a global provider of customer engagement, revenue management, and payments solutions enabling communications, media, and entertainment companies to monetize and digitally enable customer experiences. CSG's developer surface includes the CSG Forte payments REST API, Forte.js client-side tokenization library, the Forte React Native SDK, and the Singleview convergent billing platform.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/csg/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/csg/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Billing
- Customer Engagement
- Payments
- Revenue Management
- Telecom

## Timestamps

- **Created:** 2026-03-18
- **Modified:** 2026-05-19

## APIs

### CSG Forte REST API

CSG Forte provides full-stack REST APIs for payment processing within a PCI-compliant architecture. The API enables merchants and partners to create and update credit card, echeck, and scheduled transactions, securely manage customer and payment data, and query settlement information. Authentication uses HTTP Basic with organization ID, location ID, and API key.

- **Human URL:** [https://developers.forte.net/](https://developers.forte.net/)
- **Base URL:** `https://api.forte.net/v3`

#### Tags

- ACH
- Billing
- Credit Card
- Payments
- PCI
- REST

#### Properties

- [Documentation](https://developers.forte.net/introduction-rest-api/)
- [Reference](https://restdocs.forte.net/)
- [Getting Started](https://developers.forte.net/getting-started/)
- [Sandbox](https://www.forte.net/test-account-setup/)
- [Changelog](https://releases.forte.net/)
- [Status Page](https://status.forte.net/)
- [Support](https://support.forte.net/)
- [Training](https://training.forte.net/)
- [OpenAPI](openapi/csg-forte-rest-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/csg-forte-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/csg-forte-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/csg-forte-transaction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/csg-context.jsonld)

### CSG Forte.js

Forte.js is a JavaScript library for secure browser-based payment tokenization. It enables web applications to collect and tokenize payment card data client-side before submitting to Forte's payment API, reducing PCI scope.

- **Human URL:** [https://developers.forte.net/forte-js/](https://developers.forte.net/forte-js/)
- **Base URL:** `https://api.forte.net`

#### Tags

- JavaScript
- Payments
- SDK
- Web

#### Properties

- [Documentation](https://developers.forte.net/forte-js/)
- [Postman Collection](collections/csg-forte-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/csg-forte-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CSG Forte React Native SDK

The Forte React Native SDK enables mobile application developers to integrate payment processing capabilities into iOS and Android apps built with React Native.

- **Human URL:** [https://developers.forte.net/forte-react-native/](https://developers.forte.net/forte-react-native/)
- **Base URL:** `https://api.forte.net`

#### Tags

- Mobile
- Payments
- React Native
- SDK

#### Properties

- [Documentation](https://developers.forte.net/forte-react-native/)
- [S D Ks](https://developers.forte.net/forte-react-native/)
- [Postman Collection](collections/csg-forte-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/csg-forte-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### CSG Singleview Billing API

CSG Singleview is a comprehensive convergent billing and revenue management platform designed for communication service providers. APIs enable subscriber billing, usage rating, invoice generation, and payment processing across converged 5G and IoT services.

- **Human URL:** [https://www.csgi.com/](https://www.csgi.com/)
- **Base URL:** `https://api.csgi.com`

#### Tags

- Billing
- BSS
- Revenue Management
- SOAP
- Telecom

#### Properties

- [Documentation](https://www.csgi.com/)
- [Postman Collection](collections/csg-forte-rest.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/csg-forte-rest.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/csg-i)
- [LinkedIn](https://www.linkedin.com/company/csg-)
- [Website](https://www.csgi.com/)
- [OpenAPI](openapi/csg-forte-rest-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/csg-forte-transaction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](json-ld/csg-context.jsonld)
- [Spectral Rules](rules/csg-forte-rules.yml)
- [Vocabulary](vocabulary/csg-forte-vocabulary.yml)
- [Portal](https://www.forte.net/developers/)
- [Documentation](https://developers.forte.net/)
- [Reference](https://restdocs.forte.net/)
- [Support](https://support.forte.net/)
- [Status Page](https://status.forte.net/)
- [Changelog](https://releases.forte.net/)
- [Getting Started](https://www.forte.net/test-account-setup/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
