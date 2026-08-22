# Mediastack (mediastack)

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

Mediastack is a free and paid REST API by apilayer for live, historical, and blog news articles aggregated from more than 7,500 publishers across 50+ countries and 13 languages. It exposes a /v1/news endpoint for keyword-, source-, country-, language-, category-, and date-filtered search, and a /v1/sources endpoint for browsing the underlying publisher catalog.

**APIs.json:** [https://mediastack.com](https://mediastack.com)

## Tags

- News
- News Aggregation
- Media
- Apilayer
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Mediastack News API

Live, historical, and blog news search plus publisher source discovery. Returns JSON with a pagination + data envelope, secured by an access_key query parameter.

- **Human URL:** [https://mediastack.com/documentation](https://mediastack.com/documentation)
- **Base URL:** `https://api.mediastack.com/v1`

#### Tags

- News
- Sources

#### Properties

- [Documentation](https://docs.apilayer.com/mediastack/docs/api-documentation)
- [API Reference](https://mediastack.com/documentation)
- [Quickstart](https://mediastack.com/documentation#quickstart)
- [Authentication](https://mediastack.com/documentation#authentication)
- [OpenAPI](openapi/mediastack-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mediastack.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mediastack.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/mediastack-news-article-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/mediastack-source-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/mediastack-pagination-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/mediastack-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/mediastack-news-article-structure.json)
- [JSON Structure](json-structure/mediastack-source-structure.json)
- [Example](examples/mediastack-search-news-example.json)
- [Example](examples/mediastack-list-sources-example.json)
- [Example](examples/mediastack-historical-news-example.json)

## Common Properties

- [Website](https://mediastack.com)
- [Portal](https://mediastack.com/dashboard)
- [Sign Up](https://mediastack.com/signup/free)
- [Pricing](https://mediastack.com/product)
- [Terms of Service](https://mediastack.com/terms)
- [Privacy Policy](https://mediastack.com/privacy)
- [Support](https://mediastack.com/contact)
- [F A Q](https://mediastack.com/documentation#faq)
- [GitHub Repository](https://github.com/apilayer/mediastack)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [J S O N- L D](json-ld/mediastack-context.jsonld)
- [Spectral Rules](rules/mediastack-rules.yml)
- [Vocabulary](vocabulary/mediastack-vocabulary.yml)
- [Plans](plans/mediastack-plans-pricing.yml)
- [Rate Limits](rate-limits/mediastack-rate-limits.yml)
- [Fin Ops](finops/mediastack-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
