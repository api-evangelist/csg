# CSG Systems (csg)

CSG is a global provider of customer engagement, revenue management, and payments solutions enabling communications, media, and entertainment companies to monetize and digitally enable customer experiences. CSG's developer surface includes the CSG Forte payments REST API, the Forte.js client-side tokenization library, the Forte React Native SDK, and the Singleview convergent billing platform.

**APIs.yml URL:** https://raw.githubusercontent.com/api-evangelist/csg/refs/heads/main/apis.yml

## Tags

Billing, Customer Engagement, Payments, Revenue Management, Telecom

## APIs

### CSG Forte REST API

PCI-compliant REST API for credit card, echeck, and scheduled payments. Supports customer and payment-method management plus settlement queries.

- Base URL: https://api.forte.net/v3
- Documentation: https://developers.forte.net/introduction-rest-api/
- Reference: https://restdocs.forte.net/
- OpenAPI: [openapi/csg-forte-rest-openapi.yml](openapi/csg-forte-rest-openapi.yml)

### CSG Forte.js

JavaScript library for browser-based card tokenization, reducing PCI scope on merchant servers.

- Documentation: https://developers.forte.net/forte-js/

### CSG Forte React Native SDK

Mobile SDK for integrating Forte payments into React Native iOS and Android apps.

- Documentation: https://developers.forte.net/forte-react-native/

### CSG Singleview Billing API

Convergent billing and revenue management platform for communication service providers covering subscriber billing, usage rating, invoicing, and payments across 5G and IoT.

- Documentation: https://www.csgi.com/

## Features

- PCI-scoped payment processing (credit card, echeck, scheduled)
- Customer and tokenized payment-method management
- Settlement and reconciliation queries
- Browser-side tokenization with Forte.js
- React Native mobile SDK
- Convergent telecom billing via CSG Singleview
- Sandbox environment for development

## Use Cases

- Merchant credit card and ACH payment acceptance
- Recurring/subscription billing
- Mobile checkout with tokenization
- Telecom subscriber billing across 5G and IoT
- Marketplace payouts and reconciliation

## Artifacts

- OpenAPI: [openapi/csg-forte-rest-openapi.yml](openapi/csg-forte-rest-openapi.yml)
- JSON Schema: [json-schema/csg-forte-transaction-schema.json](json-schema/csg-forte-transaction-schema.json)
- JSON-LD Context: [json-ld/csg-context.jsonld](json-ld/csg-context.jsonld)
- Vocabulary: [vocabulary/csg-forte-vocabulary.yml](vocabulary/csg-forte-vocabulary.yml)
- Spectral Rules: [rules/csg-forte-rules.yml](rules/csg-forte-rules.yml)
- Naftiko Capabilities: [capabilities/](capabilities/)

## Maintainers

- Kin Lane (kin@apievangelist.com)
