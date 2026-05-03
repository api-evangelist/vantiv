# Vantiv

Vantiv was a leading American payment processing and technology provider that merged with Worldpay in 2018, forming Worldpay from FIS. Vantiv provided integrated payment processing solutions for merchants, financial institutions, and businesses across eCommerce, in-store, and omni-channel payment scenarios. Their cnpAPI (formerly litleAPI) supported credit card authorizations, captures, sales, refunds, voids, tokenization, chargebacks, and recurring billing.

**Website:** [https://www.vantiv.com](https://www.vantiv.com)
**Developer Community:** [https://developer.vantiv.com](https://developer.vantiv.com)
**Current Platform:** [Worldpay from FIS](https://developer.worldpay.com)

## APIs

### Vantiv CNP API
The Vantiv Card Not Present (CNP) API (formerly the Litle eCommerce API) enables online and mobile payment processing via XML over HTTPS POST.

- **Documentation:** [https://developer.vantiv.com/community/ecommerce](https://developer.vantiv.com/community/ecommerce)
- **OpenAPI Spec:** [openapi/vantiv-cnp-openapi.yml](openapi/vantiv-cnp-openapi.yml)

### Vantiv Chargeback API
Programmatic access to chargeback and dispute management for merchants.

- **OpenAPI Spec:** [openapi/vantiv-chargeback-openapi.yml](openapi/vantiv-chargeback-openapi.yml)

## Authentication

HTTP Basic Authentication using Vantiv-assigned merchant username and password credentials.

## SDKs

| Language | Repository |
|---|---|
| Java | [Vantiv/cnp-sdk-for-java](https://github.com/Vantiv/cnp-sdk-for-java) |
| Python | [Vantiv/vantiv-sdk-for-python](https://github.com/Vantiv/vantiv-sdk-for-python) |
| PHP | [Vantiv/cnp-sdk-for-php](https://github.com/Vantiv/cnp-sdk-for-php) |
| .NET | [Vantiv/cnp-sdk-for-dotnet](https://github.com/Vantiv/cnp-sdk-for-dotnet) |
| Ruby | [Vantiv/cnp-sdk-for-ruby](https://github.com/Vantiv/cnp-sdk-for-ruby) |

## Artifacts

### OpenAPI Specifications

- [openapi/vantiv-cnp-openapi.yml](openapi/vantiv-cnp-openapi.yml) - Vantiv CNP eCommerce API
- [openapi/vantiv-chargeback-openapi.yml](openapi/vantiv-chargeback-openapi.yml) - Vantiv Chargeback API

### Spectral Rules

- [rules/vantiv-rules.yml](rules/vantiv-rules.yml) - API linting rules for Vantiv conventions

### Naftiko Capabilities

- [capabilities/shared/vantiv-cnp.yaml](capabilities/shared/vantiv-cnp.yaml) - Shared per-API capability definition
- [capabilities/payment-processing.yaml](capabilities/payment-processing.yaml) - Payment processing workflow (8 tools)

### JSON Schema

- [json-schema/vantiv-transaction-schema.json](json-schema/vantiv-transaction-schema.json)

### JSON Structure

- [json-structure/vantiv-transaction-structure.json](json-structure/vantiv-transaction-structure.json)

### JSON-LD Context

- [json-ld/vantiv-context.jsonld](json-ld/vantiv-context.jsonld)

### Examples

- [examples/vantiv-create-sale-example.json](examples/vantiv-create-sale-example.json)
- [examples/vantiv-register-token-example.json](examples/vantiv-register-token-example.json)

### Vocabulary

- [vocabulary/vantiv-vocabulary.yml](vocabulary/vantiv-vocabulary.yml)

## Key Transaction Types

- **Authorization** - Verify funds and hold amount
- **Sale** - Authorize and capture in one step
- **Capture** - Settle a prior authorization
- **Credit** - Refund to cardholder
- **Void** - Cancel a pending transaction
- **Register Token** - Tokenize card via Vantiv Vault
- **Recurring Transaction** - Subscription billing against stored token
- **eCheck Sale** - ACH bank payment processing

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

---
*Profiled: 2026-05*
