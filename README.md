# Smartcar (smartcar)

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

Smartcar is a connected vehicle platform that provides a standardized REST API for accessing vehicle data and sending commands to connected cars. The API enables developers to retrieve battery levels, odometer readings, location, lock/unlock doors, start/stop charging, and access vehicle attributes across multiple vehicle brands through a single integration. Smartcar supports OAuth 2.0 authorization and covers EVs and ICE vehicles from dozens of OEMs including Tesla, Ford, BMW, Honda, and more.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/smartcar/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/smartcar/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Automotive
- Connected Vehicles
- IoT
- Mobility
- Fleet Management
- EV Management
- Telematics

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Smartcar Vehicles API

The Smartcar Vehicles API lets you access standardized vehicle data and send commands to connected vehicles. Retrieve signals such as battery level, odometer, location, fuel, engine oil, and diagnostic codes, as well as issue commands like lock/unlock doors, start/stop charging, set charge limit, and set navigation destinations across multiple vehicle brands. Uses OAuth 2.0 bearer token authentication.

- **Human URL:** [https://smartcar.com/docs/api/](https://smartcar.com/docs/api/)

#### Tags

- Connected Cars
- Telematics
- Vehicles
- Fleet
- EV

#### Properties

- [Documentation](https://smartcar.com/docs/api/)
- [Reference](https://smartcar.com/docs/api-reference/intro)
- [Authentication](https://smartcar.com/docs/api-reference/intro)
- [OpenAPI](openapi/smartcar-vehicles-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/smartcar-vehicles.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/smartcar-vehicles.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman](https://www.postman.com/smartcar/smartcar-api/documentation/fqmwehs/smartcar-api) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/smartcar)
- [Portal](https://smartcar.com/)
- [Documentation](https://smartcar.com/docs/api/)
- [Website](https://smartcar.com/)
- [GitHub Organization](https://github.com/smartcar)
- [Pricing](https://smartcar.com/pricing/)
- [OpenAPI](openapi/smartcar-vehicles-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Rules](rules/smartcar-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [Capabilities](capabilities/connected-vehicle-management.yaml)
- [JSON Schema](json-schema/smartcar-vehicle-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/smartcar-battery-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/smartcar-vehicles-structure.json)
- [JSON-LD](json-ld/smartcar-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/smartcar-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
