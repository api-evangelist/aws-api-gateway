# Amazon API Gateway (aws-api-gateway)
Amazon API Gateway is a fully managed service that makes it easy to create, publish, maintain, monitor, and secure APIs at any scale. It acts as the front door for applications to access backend services, supporting REST APIs, HTTP APIs, and WebSocket APIs with built-in traffic management, authorization, monitoring, and API version management. API Gateway integrates natively with AWS Lambda, CloudWatch, CloudFront, IAM, and Cognito for comprehensive serverless and secure API deployment.

**URL:** [https://aws.amazon.com/api-gateway/](https://aws.amazon.com/api-gateway/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Gateway, AWS, Cloud, REST, WebSocket, Serverless

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-04-19

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
- [APIReference](https://docs.aws.amazon.com/apigatewaymanagementapi/latest/reference/Welcome.html)
- [OpenAPI](openapi/aws-api-gateway-management-openapi.yml)

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
- [StackOverflow](https://stackoverflow.com/questions/tagged/aws-api-gateway)

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

## Use Cases

| Name | Description |
|------|-------------|
| Serverless API Backend | Build fully serverless APIs with API Gateway as the front door and AWS Lambda as the backend compute layer. |
| Microservices Gateway | Consolidate access to multiple microservices behind a single API endpoint with routing and load balancing. |
| Real-Time Applications | Enable chat apps, collaborative tools, and live dashboards using WebSocket APIs for persistent bidirectional connections. |
| Mobile and Web Application APIs | Create secure, scalable REST and HTTP APIs for mobile and web front-ends with Cognito authentication. |
| Legacy API Modernization | Expose existing on-premises or EC2-hosted services as modern REST APIs without rewriting backend logic. |
| Third-Party API Integration | Aggregate and normalize third-party APIs behind a consistent API surface with transformation and mapping. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Lambda | Invoke Lambda functions as API backends for fully serverless request handling. |
| Amazon Cognito | Authenticate and authorize API requests using Cognito user pools and identity pools. |
| Amazon CloudWatch | Monitor API performance metrics, error rates, and latency with CloudWatch dashboards and alarms. |
| AWS CloudTrail | Audit all API Gateway management API calls for compliance and security monitoring. |
| Amazon CloudFront | Distribute APIs globally through CloudFront edge locations for reduced latency. |
| AWS WAF | Apply web application firewall rules to protect APIs from malicious traffic. |
| AWS X-Ray | Trace requests end-to-end through API Gateway and backend services for performance analysis. |
| AWS IAM | Control API access using IAM policies and resource-based policies for fine-grained authorization. |
| AWS Certificate Manager | Provision and manage TLS certificates for custom domain names on API Gateway. |
| Amazon VPC | Create private APIs accessible only within a VPC using VPC endpoint integration. |

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

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
