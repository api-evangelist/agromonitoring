# Agromonitoring (agromonitoring)

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

Agromonitoring is a technology company specializing in satellite-based agricultural monitoring. Using Sentinel-2 and Landsat imagery combined with weather and soil data, Agromonitoring provides vegetation index time series (NDVI, EVI, DSWI, LSWI), current weather, multi-day forecasts, and soil conditions for registered field polygons. The platform enables precision agriculture workflows including crop health assessment, irrigation optimization, yield prediction, and climate risk monitoring.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/agromonitoring/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/agromonitoring/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Agriculture
- Satellite Imagery
- Vegetation Indices
- Weather
- Precision Agriculture
- Remote Sensing

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-05-19

## APIs

### Agromonitoring

The Agromonitoring Agro API provides satellite imagery, vegetation index time series (NDVI, EVI, DSWI, LSWI), weather data, soil conditions, and UV index for registered agricultural field polygons. Enables precision agriculture workflows including crop health monitoring, irrigation decision support, and yield optimization.

- **Human URL:** [https://agromonitoring.com/](https://agromonitoring.com/)

#### Tags

- Agriculture
- Satellite Imagery
- Vegetation Indices
- Weather
- Precision Agriculture

#### Properties

- [Documentation](https://agromonitoring.com/)
- [API Reference](https://agromonitoring.com/api/)
- [Authentication](https://agromonitoring.com/api/agro/#auth)
- [Pricing](https://agromonitoring.com/subscriptions)
- [OpenAPI](openapi/agromonitoring-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/agromonitoring.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/agromonitoring.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/agromonitoring-polygon-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agromonitoring-geojson-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agromonitoring-satelliteimage-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agromonitoring-ndvirecord-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agromonitoring-vegetationstats-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agromonitoring-weatherdata-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agromonitoring-temperaturerange-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agromonitoring-soildata-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agromonitoring-uvindexdata-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agromonitoring-polygoncreaterequest-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/agromonitoring-errorresponse-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/agromonitoring-polygon-structure.json)
- [JSON Structure](json-structure/agromonitoring-geojson-structure.json)
- [JSON Structure](json-structure/agromonitoring-satelliteimage-structure.json)
- [JSON Structure](json-structure/agromonitoring-ndvirecord-structure.json)
- [JSON Structure](json-structure/agromonitoring-vegetationstats-structure.json)
- [JSON Structure](json-structure/agromonitoring-weatherdata-structure.json)
- [JSON Structure](json-structure/agromonitoring-temperaturerange-structure.json)
- [JSON Structure](json-structure/agromonitoring-soildata-structure.json)
- [JSON Structure](json-structure/agromonitoring-uvindexdata-structure.json)
- [JSON Structure](json-structure/agromonitoring-polygoncreaterequest-structure.json)
- [JSON Structure](json-structure/agromonitoring-errorresponse-structure.json)
- [Example](examples/agromonitoring-polygon-example.json)
- [Example](examples/agromonitoring-geojson-example.json)
- [Example](examples/agromonitoring-satelliteimage-example.json)
- [Example](examples/agromonitoring-ndvirecord-example.json)
- [Example](examples/agromonitoring-vegetationstats-example.json)
- [Example](examples/agromonitoring-weatherdata-example.json)
- [Example](examples/agromonitoring-temperaturerange-example.json)
- [Example](examples/agromonitoring-soildata-example.json)
- [Example](examples/agromonitoring-uvindexdata-example.json)
- [Example](examples/agromonitoring-polygoncreaterequest-example.json)
- [Example](examples/agromonitoring-errorresponse-example.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/agromonitoring)
- [Portal](https://agromonitoring.com/)
- [Documentation](https://agromonitoring.com/api/)
- [Getting Started](https://agromonitoring.com/api/agro/#auth)
- [Pricing](https://agromonitoring.com/subscriptions)
- [F A Q](https://agromonitoring.com/faq/)
- [Terms of Service](https://agromonitoring.com/terms/)
- [Privacy Policy](https://agromonitoring.com/privacy/)
- [JSON-LD](json-ld/agromonitoring-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/agromonitoring-spectral-rules.yml)
- [Vocabulary](vocabulary/agromonitoring-vocabulary.yaml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
