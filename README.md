# Targon (targon)

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

Targon is a decentralized AI inference platform operated as Bittensor Subnet 4 by Manifold Labs. It serves popular open models through an OpenAI-compatible REST API at https://api.targon.com/v1, where a marketplace of miners runs the inference and validators verify responses, giving developers chat, completions, image, and search endpoints over confidential, decentralized compute.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/targon/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/targon/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Inference
- Decentralized
- Bittensor

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Targon Chat Completions API

OpenAI-compatible chat completions across open models (Llama, DeepSeek, and other community-added models) served by Bittensor Subnet 4 miners, with streaming, temperature, and max_tokens controls.

- **Human URL:** [https://docs.targon.com](https://docs.targon.com)
- **Base URL:** `https://api.targon.com/v1`

#### Tags

- Chat
- Completions
- LLM

#### Properties

- [Documentation](https://docs.targon.com)
- [API Reference](https://docs.targon.com)
- [OpenAPI](openapi/targon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/targon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/targon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/targon-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Targon Completions API

OpenAI-compatible legacy text completion endpoint that takes a prompt string and returns generated text from decentralized miner inference.

- **Human URL:** [https://docs.targon.com](https://docs.targon.com)
- **Base URL:** `https://api.targon.com/v1`

#### Tags

- Completions
- Text Generation

#### Properties

- [Documentation](https://docs.targon.com)
- [OpenAPI](openapi/targon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/targon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/targon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Targon Models API

Lists the open models currently live on Targon, which can be extended permissionlessly by the community, with OpenAI-compatible model metadata.

- **Human URL:** [https://docs.targon.com](https://docs.targon.com)
- **Base URL:** `https://api.targon.com/v1`

#### Tags

- Models
- Catalog

#### Properties

- [Documentation](https://docs.targon.com)
- [OpenAPI](openapi/targon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/targon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/targon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Targon Images API

OpenAI-compatible image generation endpoint that returns images from a text prompt using image models served across the Subnet 4 miner marketplace.

- **Human URL:** [https://docs.targon.com](https://docs.targon.com)
- **Base URL:** `https://api.targon.com/v1`

#### Tags

- Images
- Image Generation
- Multimodal

#### Properties

- [Documentation](https://docs.targon.com)
- [OpenAPI](openapi/targon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/targon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/targon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Targon Search API

Search endpoint that returns relevant results for a query string, usable to ground model responses with retrieved context.

- **Human URL:** [https://docs.targon.com](https://docs.targon.com)
- **Base URL:** `https://api.targon.com/v1`

#### Tags

- Search
- Retrieval

#### Properties

- [Documentation](https://docs.targon.com)
- [OpenAPI](openapi/targon-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/targon.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/targon.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/manifold-inc)
- [LinkedIn](https://www.linkedin.com/company/manifold-labs)
- [Website](https://targon.com)
- [Documentation](https://docs.targon.com)
- [Plans](plans/targon-plans-pricing.yml)
- [Rate Limits](rate-limits/targon-rate-limits.yml)
- [Fin Ops](finops/targon-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

## Notes

Targon runs on the Bittensor network as Subnet 4. Unlike a single-vendor cloud, inference is produced by a decentralized marketplace of miners running OpenAI-compliant endpoints, with validators applying deterministic verification to incentivize honest, high-quality responses. The public surface developers consume is a standard OpenAI-compatible REST API at `https://api.targon.com/v1` authenticated with a Bearer API key.
