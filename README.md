# Targon (targon)

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
