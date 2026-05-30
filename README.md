# Mediastack (mediastack)

Mediastack is a free and paid REST API by apilayer for live, historical, and blog news articles aggregated from more than 7,500 publishers across 50+ countries and 13 languages. It exposes a `/v1/news` endpoint for keyword-, source-, country-, language-, category-, and date-filtered search, and a `/v1/sources` endpoint for browsing the underlying publisher catalog.

**URL:** [Visit APIs.json URL](https://mediastack.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- News, News Aggregation, Media, Apilayer, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-30

## APIs

### Mediastack News API

Live, historical, and blog news search plus publisher source discovery. Returns JSON with a pagination + data envelope, secured by an `access_key` query parameter.

**Human URL:** [https://mediastack.com/documentation](https://mediastack.com/documentation)

**Base URL:** `https://api.mediastack.com/v1`

#### Tags

- News, Sources

#### Properties

- [Documentation](https://docs.apilayer.com/mediastack/docs/api-documentation)
- [APIReference](https://mediastack.com/documentation)
- [Quickstart](https://mediastack.com/documentation#quickstart)
- [Authentication](https://mediastack.com/documentation#authentication)
- [OpenAPI](openapi/mediastack-openapi.yml)
- [JSONSchema — News Article](json-schema/mediastack-news-article-schema.json)
- [JSONSchema — Source](json-schema/mediastack-source-schema.json)
- [JSONSchema — Pagination](json-schema/mediastack-pagination-schema.json)
- [JSONSchema — Error](json-schema/mediastack-error-schema.json)
- [JSONStructure — News Article](json-structure/mediastack-news-article-structure.json)
- [JSONStructure — Source](json-structure/mediastack-source-structure.json)
- [Example — Search News](examples/mediastack-search-news-example.json)
- [Example — List Sources](examples/mediastack-list-sources-example.json)
- [Example — Historical News](examples/mediastack-historical-news-example.json)
- [NaftikoCapability — News](capabilities/mediastack-news.yaml)
- [NaftikoCapability — Sources](capabilities/mediastack-sources.yaml)

## Common Properties

- [Website](https://mediastack.com)
- [Portal](https://mediastack.com/dashboard)
- [SignUp](https://mediastack.com/signup/free)
- [Pricing](https://mediastack.com/product)
- [TermsOfService](https://mediastack.com/terms)
- [PrivacyPolicy](https://mediastack.com/privacy)
- [Support](https://mediastack.com/contact)
- [FAQ](https://mediastack.com/documentation#faq)
- [GitHubRepository](https://github.com/apilayer/mediastack)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- [JSON-LD](json-ld/mediastack-context.jsonld)
- [SpectralRules](rules/mediastack-rules.yml)
- [Vocabulary](vocabulary/mediastack-vocabulary.yml)
- [Plans](plans/mediastack-plans-pricing.yml)
- [RateLimits](rate-limits/mediastack-rate-limits.yml)
- [FinOps](finops/mediastack-finops.yml)

## Features

| Name | Description |
|------|-------------|
| Live News Data | Real-time aggregation of articles from 7,500+ global news publishers. |
| Historical News | Date-bounded lookups of past articles via the date query parameter (paid plans). |
| Multi-Language Coverage | Articles indexed across 13 languages including English, German, Spanish, French, Chinese, and Arabic. |
| Multi-Country Coverage | Filter by 50+ country codes using ISO 3166-1 alpha-2. |
| Category Filtering | Restrict to general, business, entertainment, health, science, sports, or technology. |
| Source Filtering | Include/exclude lists of specific publishers via comma-separated IDs. |
| Keyword Search | Full-text search across article title, description, and body. |
| Publisher Catalog | Browse the /sources catalog by country, language, or category. |
| HTTPS Encryption | Encrypted transport on Standard plan and above. |
| Commercial Use License | Permitted on Standard plan and above. |

## Use Cases

| Name | Description |
|------|-------------|
| News Aggregator Apps | Power consumer-facing news readers with category- and language-filtered feeds. |
| Media Monitoring | Track brand, executive, product, or competitor mentions across global press. |
| Investor Research | Stream business-tagged headlines into trading dashboards. |
| AI Training Corpora | Sample current-events text for fine-tuning and retrieval-augmented generation. |
| Trend Analysis | Tally publication volume and sentiment around recurring keywords. |
| Newsletter Curation | Auto-generate daily digests by country, language, or topic. |

## Integrations

| Name | Description |
|------|-------------|
| apilayer Marketplace | Mediastack is one of several APIs in the apilayer marketplace alongside marketstack, currencylayer, weatherstack, and ipapi. |
| REST + JSON | Standard HTTPS+JSON makes it trivial to integrate with any HTTP client library. |
| Postman / Insomnia | Manual import of the OpenAPI spec into common API clients. |

## Solutions

| Name | Description |
|------|-------------|
| Free Plan | Evaluation tier, 100 requests/month, HTTP only, no historical data, no commercial use. |
| Standard Plan | $24.99/month, 10k requests, HTTPS, historical data, commercial use. |
| Professional Plan | $99.99/month, 50k requests, lower overage rate. |
| Business Plan | $249.99/month, 250k requests, lowest published overage rate. |
| Enterprise Plan | Custom volume, platinum support, custom solutions. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [mediastack-openapi.yml](openapi/mediastack-openapi.yml) — Mediastack News API v1 (2 operations: searchNews, listSources)

### JSON Schema

- [mediastack-news-article-schema.json](json-schema/mediastack-news-article-schema.json)
- [mediastack-source-schema.json](json-schema/mediastack-source-schema.json)
- [mediastack-pagination-schema.json](json-schema/mediastack-pagination-schema.json)
- [mediastack-error-schema.json](json-schema/mediastack-error-schema.json)

### JSON Structure

- [mediastack-news-article-structure.json](json-structure/mediastack-news-article-structure.json)
- [mediastack-source-structure.json](json-structure/mediastack-source-structure.json)

### JSON-LD

- [mediastack-context.jsonld](json-ld/mediastack-context.jsonld)

### Examples

- [mediastack-search-news-example.json](examples/mediastack-search-news-example.json)
- [mediastack-list-sources-example.json](examples/mediastack-list-sources-example.json)
- [mediastack-historical-news-example.json](examples/mediastack-historical-news-example.json)

## Capabilities

Naftiko capabilities — self-contained per-tag files, each declaring an inline `consumes` block plus both REST and MCP exposers.

### Mediastack News API

- [mediastack-news.yaml](capabilities/mediastack-news.yaml) — News surface, 1 operation (searchNews) exposed as REST `/v1/news` and MCP tool `search-news`.
- [mediastack-sources.yaml](capabilities/mediastack-sources.yaml) — Sources surface, 1 operation (listSources) exposed as REST `/v1/sources` and MCP tool `list-sources`.

## Spectral Rules

- [mediastack-rules.yml](rules/mediastack-rules.yml) — 9 rules enforcing Mediastack conventions: contact required, canonical base URL, access_key auth, title-case summaries, allowed tags (News, Sources), pagination envelope shape, error envelope shape, snake_case field names.

## Vocabulary

- [mediastack-vocabulary.yml](vocabulary/mediastack-vocabulary.yml) — Controlled vocabulary covering News, Sources, Categories, Languages, Geography, operational dimensions, capabilities, and FinOps dimensions.

## Commercial Surface

- [Plans & Pricing](plans/mediastack-plans-pricing.yml) — 5 plans (Free, Standard, Professional, Business, Enterprise) modeled in API Commons Plans 0.1.
- [Rate Limits](rate-limits/mediastack-rate-limits.yml) — Per-key monthly quotas + feature gates modeled in API Commons Rate Limits 0.1.
- [FinOps](finops/mediastack-finops.yml) — FOCUS 1.3-aligned FinOps model: tiered subscription + pay-as-you-go overage, 5 meters, 4 FinOps principles.

## Maintainers

- Kin Lane — kin@apievangelist.com
