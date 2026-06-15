# Kalshi (kalshi)

Kalshi is a CFTC-regulated US exchange for binary event contracts on real-world outcomes - elections, economics, weather, sports, and more. The platform exposes a public REST trading API and WebSocket streams for market data, orders, positions, and portfolio actions, with a published OpenAPI 3 specification and AsyncAPI definition for the streaming surface. A demo environment mirrors production for safe development. Official Python and community SDKs are provided.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/kalshi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/kalshi/refs/heads/main/apis.yml)

## Tags

- Prediction Markets
- Event Contracts
- Exchange
- CFTC
- Trading
- Markets

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-29

## APIs

### Kalshi Trade API (REST)

Public REST API for trading on Kalshi - browse markets, events, and series, place and cancel orders, manage portfolio and positions, fund and withdraw, and pull historical trades. Authenticated with API keys and Ed25519 request signatures.

- **Human URL:** [https://docs.kalshi.com/api-reference](https://docs.kalshi.com/api-reference)
- **Base URL:** `https://api.elections.kalshi.com/trade-api/v2`

#### Tags

- REST
- Trading
- Markets
- Orders

#### Properties

- [Documentation](https://docs.kalshi.com/api-reference)
- [OpenAPI](https://docs.kalshi.com/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kalshi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kalshi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kalshi Trade API (external-api host)

Alternate production host for the Kalshi Trade API, used by external integrators. Same API surface and authentication as the primary host.

- **Human URL:** [https://docs.kalshi.com/api-reference](https://docs.kalshi.com/api-reference)
- **Base URL:** `https://external-api.kalshi.com/trade-api/v2`

#### Tags

- REST
- Trading
- External

#### Properties

- [Documentation](https://docs.kalshi.com/api-reference)
- [OpenAPI](https://docs.kalshi.com/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kalshi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kalshi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kalshi Trade API (Demo)

Demo / sandbox environment for the Kalshi Trade API - mirrors production semantics with simulated balances and markets for safe development and automated testing.

- **Human URL:** [https://docs.kalshi.com/api-reference](https://docs.kalshi.com/api-reference)
- **Base URL:** `https://demo-api.kalshi.co/trade-api/v2`

#### Tags

- REST
- Demo
- Sandbox
- Testing

#### Properties

- [Documentation](https://docs.kalshi.com/api-reference)
- [Postman Collection](collections/kalshi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kalshi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kalshi WebSocket Streaming API

Real-time streaming feed for market data, order book updates, fills, and portfolio events on Kalshi. Documented as an AsyncAPI spec alongside the OpenAPI REST surface.

- **Human URL:** [https://docs.kalshi.com/api-reference](https://docs.kalshi.com/api-reference)
- **Base URL:** `wss://api.elections.kalshi.com/trade-api/ws/v2`

#### Tags

- WebSocket
- Streaming
- Market Data

#### Properties

- [Documentation](https://docs.kalshi.com/api-reference)
- [AsyncAPI](https://docs.kalshi.com/asyncapi.yaml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/kalshi/refs/heads/main/asyncapi/kalshi-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/kalshi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kalshi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kalshi OpenAPI Specification

Machine-readable OpenAPI 3 description of the Kalshi Trade REST API. Suitable for generating clients, mocks, and contract tests.

- **Human URL:** [https://docs.kalshi.com/](https://docs.kalshi.com/)
- **Base URL:** `https://docs.kalshi.com/openapi.yaml`

#### Tags

- OpenAPI
- Specification

#### Properties

- [OpenAPI](https://docs.kalshi.com/openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/kalshi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kalshi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kalshi AsyncAPI Specification

Machine-readable AsyncAPI description of the Kalshi WebSocket streaming API. Suitable for generating async clients and documenting message schemas.

- **Human URL:** [https://docs.kalshi.com/](https://docs.kalshi.com/)
- **Base URL:** `https://docs.kalshi.com/asyncapi.yaml`

#### Tags

- AsyncAPI
- Specification
- WebSocket

#### Properties

- [AsyncAPI](https://docs.kalshi.com/asyncapi.yaml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/kalshi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kalshi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Kalshi Python Starter Kit

Official Python starter / SDK published by Kalshi for connecting to the Trade REST API and WebSocket streams. Includes request signing, authentication helpers, and example trading flows.

- **Human URL:** [https://github.com/Kalshi/kalshi-starter-code-python](https://github.com/Kalshi/kalshi-starter-code-python)
- **Base URL:** `https://github.com/Kalshi/kalshi-starter-code-python`

#### Tags

- SDK
- Python
- Starter

#### Properties

- [Repository](https://github.com/Kalshi/kalshi-starter-code-python)
- [Postman Collection](collections/kalshi.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/kalshi.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://kalshi.com/)
- [Documentation](https://docs.kalshi.com/)
- [A P I  Reference](https://docs.kalshi.com/api-reference)
- [Help](https://help.kalshi.com/)
- [Git Hub](https://github.com/Kalshi)
- [Developer  Agreement](https://kalshi.com/developer-agreement)
- [LinkedIn](https://www.linkedin.com/company/kalshi/)
- [L L Ms Txt](https://docs.kalshi.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
