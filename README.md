# Vantiv (vantiv)

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

Vantiv was a leading American payment processing and technology provider that merged with Worldpay in 2018, forming Worldpay from FIS. Vantiv provided integrated payment processing solutions for merchants, financial institutions, and businesses across eCommerce, in-store, and omni-channel payment scenarios. Their cnpAPI (formerly litleAPI) supported credit card authorizations, captures, sales, refunds, voids, tokenization, chargebacks, and recurring billing.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vantiv/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vantiv/refs/heads/main/apis.yml)

## Scope

- **Access:** 3rd-Party

## Tags

- Payments
- Payment Processing
- eCommerce
- Finance
- FinTech

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-19

## APIs

### Vantiv CNP API

The Vantiv Card Not Present (CNP) API, formerly known as the Litle eCommerce API, enables online and mobile payment processing. Supports authorizations, sales, captures, credits, voids, tokenization, chargebacks, and recurring billing through XML-based HTTPS POST requests.

- **Human URL:** [https://developer.vantiv.com/community/ecommerce](https://developer.vantiv.com/community/ecommerce)
- **Base URL:** `https://payments.vantivprelive.com/vap/communicator/online`

#### Tags

- Payments
- Payment Processing
- eCommerce
- Finance
- Card-Not-Present

#### Properties

- [Documentation](https://developer.vantiv.com/community/ecommerce/pages/sdks)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/vantiv/refs/heads/main/openapi/vantiv-cnp-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vantiv-chargeback.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vantiv-chargeback.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/vantiv-cnp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vantiv-cnp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vantiv Express API

The Vantiv Integrated Payments Express API provides a REST/XML interface for point-of-sale and in-person payment processing. Supports credit, debit, EBT, gift card, and check transactions with EMV chip support.

- **Human URL:** [https://developer.vantiv.com/community/point-of-sale/pages/documentation](https://developer.vantiv.com/community/point-of-sale/pages/documentation)
- **Base URL:** `https://api.vantivintegrationtest.com/express/v1`

#### Tags

- Payments
- Payment Processing
- Point Of Sale
- Finance

#### Properties

- [Documentation](https://developer.vantiv.com/community/point-of-sale/pages/documentation)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/vantiv/refs/heads/main/openapi/vantiv-express-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vantiv-chargeback.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vantiv-chargeback.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/vantiv-cnp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vantiv-cnp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vantiv Chargeback API

The Vantiv Chargeback API provides programmatic access to chargeback and dispute management, allowing merchants to retrieve chargeback details, upload evidence, and respond to disputes.

- **Human URL:** [https://developer.vantiv.com/community/ecommerce](https://developer.vantiv.com/community/ecommerce)
- **Base URL:** `https://services.vantivprelive.com/services/chargebacks`

#### Tags

- Payments
- Chargebacks
- Finance
- Dispute Management

#### Properties

- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/vantiv/refs/heads/main/openapi/vantiv-chargeback-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vantiv-chargeback.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vantiv-chargeback.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/vantiv-cnp.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vantiv-cnp.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/vantiv)
- [Portal](https://developer.vantiv.com/community/ecommerce)
- [SDK](https://developer.vantiv.com/community/ecommerce/pages/sdks)
- [Sandbox](https://developer.vantiv.com/docs/DOC-1347)
- [SDK](https://github.com/Vantiv)
- [SDK](https://github.com/Vantiv/cnp-sdk-for-java)
- [SDK](https://github.com/Vantiv/vantiv-sdk-for-python)
- [SDK](https://github.com/Vantiv/cnp-sdk-for-php)
- [SDK](https://github.com/Vantiv/cnp-sdk-for-dotnet)
- [SDK](https://github.com/Vantiv/cnp-sdk-for-ruby)
- [SDK](https://github.com/Vantiv/cnp-chargeback-sdk-java)
- [Documentation](https://developer.worldpay.com)
- [Website](https://www.vantiv.com)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
