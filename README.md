# Amazon API Gateway (aws-api-gateway)

Amazon API Gateway is a fully managed service that makes it easy to create, publish, maintain, monitor, and secure APIs at any scale. It acts as the front door for applications to access backend services, supporting REST APIs, HTTP APIs, and WebSocket APIs with built-in traffic management, authorization, monitoring, and API version management. API Gateway integrates natively with AWS Lambda, CloudWatch, CloudFront, IAM, and Cognito, and (as of December 2025) can expose REST APIs as MCP-compatible tools for Amazon Bedrock AgentCore Gateway for agent-driven API consumption.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/aws-api-gateway/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- API Gateway
- AWS
- Cloud
- REST
- HTTP
- WebSocket
- Serverless
- MCP
- AgentCore
- Developer Portal

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-29

## APIs

### Amazon API Gateway V1 (REST)

The API Gateway V1 control plane API is used to create, deploy, and manage REST APIs in Amazon API Gateway. It exposes resources for RestApis, Resources, Methods, Stages, Deployments, Authorizers, API keys, usage plans, and related configuration.

- **Human URL:** [https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html](https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html)
- **Base URL:** `https://apigateway.{region}.amazonaws.com`

#### Tags

- API Gateway
- AWS
- REST

#### Properties

- [Documentation](https://docs.aws.amazon.com/apigateway/latest/developerguide/)
- [API Reference](https://docs.aws.amazon.com/apigateway/latest/api/Welcome.html)
- [Getting Started](https://docs.aws.amazon.com/apigateway/latest/developerguide/getting-started.html)
- [Authentication](https://docs.aws.amazon.com/apigateway/latest/developerguide/permissions.html)
- [Documentation](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-portals.html)
- [Documentation](https://docs.aws.amazon.com/apigateway/latest/developerguide/mcp-server.html)
- [Documentation](https://docs.aws.amazon.com/apigateway/latest/developerguide/response-transfer-mode.html)
- [Documentation](https://docs.aws.amazon.com/apigateway/latest/developerguide/private-integration.html)
- [OpenAPI](openapi/aws-api-gateway-v1-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aws-api-gateway-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aws-api-gateway-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amazon API Gateway V2 (HTTP and WebSocket)

The API Gateway V2 control plane API is used to create, deploy, and manage HTTP APIs and WebSocket APIs in Amazon API Gateway. It provides resources for Apis, Routes, Integrations, Stages, Deployments, and Authorizers for the newer HTTP and WebSocket API types.

- **Human URL:** [https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api.html](https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api.html)
- **Base URL:** `https://apigateway.{region}.amazonaws.com`

#### Tags

- API Gateway
- AWS
- HTTP
- WebSocket

#### Properties

- [Documentation](https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api.html)
- [API Reference](https://docs.aws.amazon.com/apigatewayv2/latest/api-reference/Welcome.html)
- [Getting Started](https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api-develop.html)
- [Documentation](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-websocket-api.html)
- [OpenAPI](openapi/aws-api-gateway-v2-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aws-api-gateway-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aws-api-gateway-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/aws-api-gateway-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Amazon API Gateway Management API

The API Gateway Management API allows backend services to send messages to connected clients of a deployed WebSocket API and to disconnect clients. Requests are made against the deployed stage's callback URL.

- **Human URL:** [https://docs.aws.amazon.com/apigatewaymanagementapi/latest/reference/Welcome.html](https://docs.aws.amazon.com/apigatewaymanagementapi/latest/reference/Welcome.html)
- **Base URL:** `https://{api-id}.execute-api.{region}.amazonaws.com/{stage}`

#### Tags

- API Gateway
- AWS
- Callback
- WebSocket

#### Properties

- [Documentation](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-how-to-call-websocket-api-connections.html)
- [API Reference](https://docs.aws.amazon.com/apigatewaymanagementapi/latest/reference/Welcome.html)
- [OpenAPI](openapi/aws-api-gateway-management-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/aws-api-gateway-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aws-api-gateway-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Amazon API Gateway Portals

The API Gateway Portals control plane (introduced November 19, 2025) lets you create branded developer portals that catalog REST APIs. A portal contains PortalProducts (logical groupings of REST APIs) and Product REST Endpoint Pages that publish path/method/stage-level documentation. Portals are Region-scoped, shareable across AWS accounts, and access-controlled via Amazon Cognito user pools.

- **Human URL:** [https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-portals.html](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-portals.html)
- **Base URL:** `https://apigateway.{region}.amazonaws.com`

#### Tags

- API Gateway
- AWS
- Developer Portal
- REST

#### Properties

- [Documentation](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-portals.html)
- [API Reference](https://docs.aws.amazon.com/apigateway/latest/api/Welcome.html)
- [Rate Limits](https://docs.aws.amazon.com/apigateway/latest/developerguide/limits.html)
- [Postman Collection](collections/aws-api-gateway-management.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aws-api-gateway-management.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/aws-api-gateway-v1.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aws-api-gateway-v1.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/aws-api-gateway-v2.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/aws-api-gateway-v2.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Website](https://aws.amazon.com/api-gateway/)
- [Documentation](https://docs.aws.amazon.com/apigateway/)
- [Getting Started](https://docs.aws.amazon.com/apigateway/latest/developerguide/getting-started.html)
- [Pricing](https://aws.amazon.com/api-gateway/pricing/)
- [Rate Limits](https://docs.aws.amazon.com/apigateway/latest/developerguide/limits.html)
- [SDK](https://aws.amazon.com/tools/)
- [C L I](https://docs.aws.amazon.com/cli/latest/reference/apigateway/)
- [Changelog](https://docs.aws.amazon.com/apigateway/latest/developerguide/history.html)
- [Status Page](https://health.aws.amazon.com/health/status)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/compute/category/compute/amazon-api-gateway/)
- [Console](https://console.aws.amazon.com/apigateway/)
- [Terms of Service](https://aws.amazon.com/service-terms/)
- [Privacy Policy](https://aws.amazon.com/privacy/)
- [GitHub Organization](https://github.com/aws)
- [GitHub Organization](https://github.com/aws-samples)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/aws-api-gateway)
- [Spectral Rules](rules/aws-api-gateway-spectral-rules.yml)
- [Vocabulary](vocabulary/aws-api-gateway-vocabulary.yaml)
- [Plans](plans/aws-api-gateway-plans-pricing.yml)
- [Rate Limits Artifact](rate-limits/aws-api-gateway-rate-limits.yml)
- [Fin Ops](finops/aws-api-gateway-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://aws.amazon.com/marketplace)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
