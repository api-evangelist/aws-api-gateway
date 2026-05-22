# Amazon API Gateway (aws-api-gateway)
Amazon API Gateway is a fully managed service that makes it easy to create, publish, maintain, monitor, and secure APIs at any scale. It acts as the front door for applications to access backend services, supporting REST APIs, HTTP APIs, and WebSocket APIs with built-in traffic management, authorization, monitoring, and API version management. API Gateway integrates natively with AWS Lambda, CloudWatch, CloudFront, IAM, and Cognito, and (as of December 2025) can expose REST APIs as MCP-compatible tools for Amazon Bedrock AgentCore Gateway for agent-driven API consumption.

**URL:** [https://aws.amazon.com/api-gateway/](https://aws.amazon.com/api-gateway/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Gateway, AWS, Cloud, REST, HTTP, WebSocket, Serverless, MCP, AgentCore, Developer Portal

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-05-22

## APIs

### Amazon API Gateway V1 (REST)
The API Gateway V1 control plane API is used to create, deploy, and manage REST APIs in Amazon API Gateway. It exposes resources for RestApis, Resources, Methods, Stages, Deployments, Authorizers, API keys, usage plans, and related configuration.

**Human URL:** [https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html](https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html)

#### Tags:

 - API Gateway, AWS, REST

#### Properties

- [Documentation](https://docs.aws.amazon.com/apigateway/latest/developerguide/)
- [APIReference](https://docs.aws.amazon.com/apigateway/latest/api/Welcome.html)
- [GettingStarted](https://docs.aws.amazon.com/apigateway/latest/developerguide/getting-started.html)
- [Authentication](https://docs.aws.amazon.com/apigateway/latest/developerguide/permissions.html)
- [API Gateway Portals (Nov 2025)](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-portals.html)
- [REST API as Bedrock AgentCore Gateway MCP Target (Dec 2025)](https://docs.aws.amazon.com/apigateway/latest/developerguide/mcp-server.html)
- [REST API Response Streaming (Nov 2025)](https://docs.aws.amazon.com/apigateway/latest/developerguide/response-transfer-mode.html)
- [Private Integration with Application Load Balancer (Nov 2025)](https://docs.aws.amazon.com/apigateway/latest/developerguide/private-integration.html)
- [OpenAPI](openapi/aws-api-gateway-v1-openapi.yml)

### Amazon API Gateway V2 (HTTP and WebSocket)
The API Gateway V2 control plane API is used to create, deploy, and manage HTTP APIs and WebSocket APIs in Amazon API Gateway. It provides resources for Apis, Routes, Integrations, Stages, Deployments, and Authorizers for the newer HTTP and WebSocket API types.

**Human URL:** [https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api.html](https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api.html)

#### Tags:

 - API Gateway, AWS, HTTP, WebSocket

#### Properties

- [Documentation](https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api.html)
- [APIReference](https://docs.aws.amazon.com/apigatewayv2/latest/api-reference/Welcome.html)
- [GettingStarted](https://docs.aws.amazon.com/apigateway/latest/developerguide/http-api-develop.html)
- [WebSocket API Guide](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-websocket-api.html)
- [OpenAPI](openapi/aws-api-gateway-v2-openapi.yml)

### Amazon API Gateway Management API
The API Gateway Management API allows backend services to send messages to connected clients of a deployed WebSocket API and to disconnect clients. Requests are made against the deployed stage's callback URL.

**Human URL:** [https://docs.aws.amazon.com/apigatewaymanagementapi/latest/reference/Welcome.html](https://docs.aws.amazon.com/apigatewaymanagementapi/latest/reference/Welcome.html)

#### Tags:

 - API Gateway, AWS, Callback, WebSocket

#### Properties

- [Documentation](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-how-to-call-websocket-api-connections.html)
- [APIReference](https://docs.aws.amazon.com/apigatewayv2/latest/api-reference/Welcome.html)
- [OpenAPI](openapi/aws-api-gateway-management-openapi.yml)

### Amazon API Gateway Portals
The API Gateway Portals control plane (introduced November 19, 2025) lets you create branded developer portals that catalog REST APIs. A portal contains PortalProducts (logical groupings of REST APIs) and Product REST Endpoint Pages that publish path/method/stage-level documentation. Portals are Region-scoped, shareable across AWS accounts, and access-controlled via Amazon Cognito user pools.

**Human URL:** [https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-portals.html](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-portals.html)

#### Tags:

 - API Gateway, AWS, Developer Portal, REST

#### Properties

- [Documentation](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-portals.html)
- [APIReference](https://docs.aws.amazon.com/apigateway/latest/api/Welcome.html)
- [RateLimits](https://docs.aws.amazon.com/apigateway/latest/developerguide/limits.html)

## Common Properties

- [Website](https://aws.amazon.com/api-gateway/)
- [Documentation](https://docs.aws.amazon.com/apigateway/)
- [GettingStarted](https://docs.aws.amazon.com/apigateway/latest/developerguide/getting-started.html)
- [Pricing](https://aws.amazon.com/api-gateway/pricing/)
- [RateLimits](https://docs.aws.amazon.com/apigateway/latest/developerguide/limits.html)
- [AWS SDKs](https://aws.amazon.com/tools/)
- [CLI](https://docs.aws.amazon.com/cli/latest/reference/apigateway/)
- [ChangeLog](https://docs.aws.amazon.com/apigateway/latest/developerguide/history.html)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/compute/category/compute/amazon-api-gateway/)
- [Console](https://console.aws.amazon.com/apigateway/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [GitHubOrganization](https://github.com/aws)
- [AWS Samples (121+ API Gateway sample repos)](https://github.com/aws-samples)
- [StackOverflow](https://stackoverflow.com/questions/tagged/aws-api-gateway)
- [Plans](plans/aws-api-gateway-plans-pricing.yml)
- [RateLimitsArtifact](rate-limits/aws-api-gateway-rate-limits.yml)
- [FinOps](finops/aws-api-gateway-finops.yml)

## Features

| Name | Description |
|------|-------------|
| REST API Management | Create, deploy, and manage REST APIs with full lifecycle control including stages, deployments, and versioning. |
| HTTP API Support | Build lightweight HTTP APIs optimized for serverless workloads at up to 71% lower cost than REST APIs. |
| WebSocket APIs | Enable real-time bidirectional communication for chat platforms, streaming dashboards, and live applications. |
| Traffic Management | Handle hundreds of thousands of concurrent API calls with built-in throttling and request validation. |
| Authorization and Security | Supports IAM policies, Lambda authorizers, Amazon Cognito user pools, and OAuth2/OIDC for API access control. |
| Monitoring and Logging | Integration with CloudWatch metrics, access logging, and CloudTrail for full API observability. |
| Custom Domain Names | Map APIs to branded custom domains with TLS certificates managed through AWS Certificate Manager. |
| Canary Releases | Safely roll out API changes using canary deployment stages with configurable traffic splitting. |
| AWS WAF Integration | Protect APIs against common web exploits and DDoS attacks using AWS Web Application Firewall. |
| SDK Generation | Automatically generate client SDKs for deployed APIs in multiple programming languages. |
| API Caching | Reduce backend load and improve response times with configurable response caching at the stage level. |
| CloudFront Edge Distribution | Leverage Amazon CloudFront edge locations for global low-latency API distribution. |
| Bedrock AgentCore Gateway MCP Target | Expose REST API stages as Model Context Protocol (MCP) tools for AI agents via Bedrock AgentCore Gateway. Launched December 2, 2025. |
| Developer Portals | Native API Gateway Portals (Nov 19, 2025) publish PortalProducts of REST APIs with per-endpoint documentation, Cognito-gated access, and cross-account sharing. |
| REST API Response Streaming | REST APIs can progressively stream response payloads to clients (Nov 19, 2025). |
| Private Integration with Application Load Balancer | REST APIs support private integration with ALBs (Nov 21, 2025), beyond the existing NLB and Cloud Map options. |
| SIGv4a Authentication for REST APIs | AWS Signature Version 4a support for REST APIs (Aug 19, 2025). |
| Enhanced TLS Security Policies | Configurable TLS policies for REST APIs and custom domain names (Nov 19, 2025). |
| Dual-Stack IPv4/IPv6 Endpoints | Dual-stack endpoints for REST, HTTP, WebSocket APIs and custom domains (Mar 28, 2025). |

## Use Cases

| Name | Description |
|------|-------------|
| Serverless API Backend | Build fully serverless APIs with API Gateway as the front door and AWS Lambda as the backend compute layer. |
| Microservices Gateway | Consolidate access to multiple microservices behind a single API endpoint with routing and load balancing. |
| Real-Time Applications | Enable chat apps, collaborative tools, and live dashboards using WebSocket APIs for persistent bidirectional connections. |
| Mobile and Web Application APIs | Create secure, scalable REST and HTTP APIs for mobile and web front-ends with Cognito authentication. |
| Legacy API Modernization | Expose existing on-premises or EC2-hosted services as modern REST APIs without rewriting backend logic. |
| Third-Party API Integration | Aggregate and normalize third-party APIs behind a consistent API surface with transformation and mapping. |
| MCP Tool Server for AI Agents | Expose REST APIs as MCP-compatible tool catalogs via Bedrock AgentCore Gateway. |
| Developer Portal for Partner APIs | Publish partner-facing REST APIs with branded portals, Cognito gating, and self-service key issuance. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Lambda | Invoke Lambda functions as API backends for fully serverless request handling. |
| Amazon Cognito | Authenticate and authorize API requests using Cognito user pools and identity pools. Also gates access to API Gateway Portals. |
| Amazon CloudWatch | Monitor API performance metrics, error rates, and latency with CloudWatch dashboards and alarms. |
| AWS CloudTrail | Audit all API Gateway management API calls for compliance and security monitoring. |
| Amazon CloudFront | Distribute APIs globally through CloudFront edge locations for reduced latency. |
| AWS WAF | Apply web application firewall rules to protect APIs from malicious traffic. |
| AWS X-Ray | Trace requests end-to-end through API Gateway and backend services for performance analysis. |
| AWS IAM | Control API access using IAM policies and resource-based policies for fine-grained authorization. |
| AWS Certificate Manager | Provision and manage TLS certificates for custom domain names on API Gateway. |
| Amazon VPC | Create private APIs accessible only within a VPC using VPC endpoint integration. |
| Amazon Bedrock AgentCore Gateway | Expose API Gateway REST API stages as MCP-compatible tools. AgentCore translates tools/list and tools/call into HTTP requests. |
| Amazon EventBridge | Drive event-driven backends and trigger workflows from API events. |
| AWS AppSync | Pair API Gateway HTTP/WebSocket APIs with AppSync GraphQL APIs over shared backends. |
| Application Load Balancer | Private integration target for REST APIs (Nov 21, 2025). |
| AWS Lambda Authorizers | Token and request authorizers for REST and HTTP APIs that delegate to Lambda. |
| AWS PrivateLink | Underlies Private REST APIs via Interface VPC endpoints. |
| Amazon Data Firehose | Stream access logs to S3, Redshift, or OpenSearch for analysis. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon API Gateway V1 (REST)](openapi/aws-api-gateway-v1-openapi.yml)
- [Amazon API Gateway V2 (HTTP and WebSocket)](openapi/aws-api-gateway-v2-openapi.yml)
- [Amazon API Gateway Management API](openapi/aws-api-gateway-management-openapi.yml)

### JSON Schema

41 schema files covering RestApi, Resource, Method, Stage, Deployment, ApiKey, UsagePlan, Authorizer, Connection, and more.

### JSON Structure

41 JSON Structure files converted from JSON Schema using json-structure.org/meta/core/v0.

### JSON-LD

30 JSON-LD context files mapping API Gateway resource types and properties to linked data semantics.

### Examples

41 example JSON files generated from JSON Schema definitions.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon API Gateway V1](capabilities/shared/api-gateway-v1.yaml) — 9 operations for REST API lifecycle management
- [Amazon API Gateway V2](capabilities/shared/api-gateway-v2.yaml) — 5 operations for HTTP and WebSocket API management
- [Amazon API Gateway Management API](capabilities/shared/api-gateway-management.yaml) — 3 operations for WebSocket connection management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [API Management Workflow](capabilities/api-management-workflow.yaml) | V1, V2, Management | 18 | API Platform Engineer, Backend Developer |

## Vocabulary

- [Amazon API Gateway Vocabulary](vocabulary/aws-api-gateway-vocabulary.yaml) — Unified taxonomy mapping 12 resources, 6 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Amazon API Gateway Spectral Rules](rules/aws-api-gateway-spectral-rules.yml) — 30 rules across 8 categories enforcing Amazon API Gateway API conventions

## Commercial Surface

- [Plans / Pricing](plans/aws-api-gateway-plans-pricing.yml) — API Commons Plans 0.1 capture of REST, HTTP, WebSocket, Private REST, Portals, and Free Tier
- [Rate Limits](rate-limits/aws-api-gateway-rate-limits.yml) — Account-level, control-plane, and per-stage throttle quotas
- [FinOps](finops/aws-api-gateway-finops.yml) — FOCUS-aligned billing surface

## Recent Releases (2025-2026)

| Date | Change |
|------|--------|
| 2025-12-02 | REST API as a target for Amazon Bedrock AgentCore Gateway |
| 2025-11-21 | Private integration with Application Load Balancer (REST APIs) |
| 2025-11-19 | Security policies for REST APIs and custom domain names |
| 2025-11-19 | Response streaming for REST APIs |
| 2025-11-19 | Developer portals |
| 2025-08-19 | SIGv4a for REST APIs |
| 2025-06-03 | Routing rules for REST APIs (custom domains) |
| 2025-03-28 | Dual-stack (IPv4 + IPv6) endpoints |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
