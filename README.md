# Better Stack (better-stack)
Better Stack is a comprehensive infrastructure monitoring and observability platform that combines uptime monitoring, log management, incident management, status pages, and AI-powered site reliability tools. It helps teams identify and resolve website and server issues quickly by providing real-time alerting, detailed diagnostics, on-call scheduling, and public/private status pages.

**URL:** [https://betterstack.com/docs/uptime/api/getting-started/](https://betterstack.com/docs/uptime/api/getting-started/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Incidents, Logs, Monitoring, Platform, Status, Uptime, Observability, On-Call, Heartbeats

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-04-19

## APIs

### Better Stack API
The Better Stack API provides programmatic access to uptime monitoring, heartbeat monitoring, incident management, status pages, escalation policies, and team management. It follows the JSON:API specification and uses Bearer token authentication.

**Human URL:** [https://betterstack.com/docs/uptime/api/getting-started/](https://betterstack.com/docs/uptime/api/getting-started/)

#### Tags:

 - Monitoring, Incidents, Uptime, Heartbeats, Status Pages

#### Properties

- [Documentation](https://betterstack.com/docs/uptime/api/getting-started/)
- [APIReference](https://betterstack.com/docs/uptime/api/monitors/)
- [OpenAPI](openapi/better-stack-openapi.yml)

## Common Properties

- [Portal](https://betterstack.com/docs/)
- [GettingStarted](https://betterstack.com/docs/uptime/api/getting-started/)
- [Authentication](https://betterstack.com/docs/uptime/api/getting-started/)
- [Pricing](https://betterstack.com/pricing)
- [StatusPage](https://status.betterstack.com/)
- [Blog](https://betterstack.com/community/blog)
- [ChangeLog](https://betterstack.com/tag/changelog)
- [GitHubOrganization](https://github.com/BetterStackHQ)

## Features

| Name | Description |
|------|-------------|
| Uptime Monitoring | Monitor URLs, APIs, and services for availability with checks from multiple global regions every 30 seconds. |
| Heartbeat Monitoring | Monitor scheduled jobs, cron tasks, and background workers by pinging a unique URL on each run. |
| Incident Management | Automatically create and manage incidents when monitors detect downtime, with acknowledgement and resolution workflows. |
| On-Call Scheduling | Configure escalation policies with multi-step notification sequences via phone, SMS, email, and push. |
| Status Pages | Create public and private status pages with custom domains, branding, and real-time component status. |
| Log Management | Collect, search, and visualize logs across your entire infrastructure stack. |
| AI SRE | AI-powered root cause analysis that automatically investigates incidents and suggests resolutions. |
| Infrastructure Monitoring | OpenTelemetry-native monitoring with dashboards for metrics and infrastructure health. |
| Terraform Provider | Manage Better Stack resources as code using the official Terraform provider. |
| MCP Server | Model Context Protocol server for integrating Better Stack with AI tools and agents. |

## Use Cases

| Name | Description |
|------|-------------|
| Website Uptime Monitoring | Monitor public websites and APIs for availability and alert on-call engineers when they go down. |
| API Health Checking | Continuously verify that REST APIs return expected status codes and response times. |
| Cron Job Monitoring | Use heartbeats to ensure scheduled tasks run on time and alert when they fail to check in. |
| Incident Response Automation | Automate incident creation, on-call notifications, and resolution workflows to reduce MTTR. |
| Customer-Facing Status Communication | Publish status pages that automatically reflect the real-time health of monitored services. |
| Infrastructure Observability | Aggregate logs, metrics, and traces in a single platform for full-stack observability. |

## Integrations

| Name | Description |
|------|-------------|
| Slack | Receive incident alerts and status updates directly in Slack channels. |
| PagerDuty | Forward incidents to PagerDuty for existing on-call workflows. |
| Terraform | Manage monitors, status pages, and escalation policies as infrastructure as code. |
| OpenTelemetry | Send metrics, logs, and traces using OpenTelemetry-compatible exporters. |
| Sentry | Compatible with Sentry SDK for error tracking integration. |
| New Relic | Connect Better Stack monitoring data with New Relic dashboards. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Better Stack API](openapi/better-stack-openapi.yml)

### JSON Schema

- [better-stack-availability-response-schema.json](json-schema/better-stack-availability-response-schema.json)
- [better-stack-heartbeat-attributes-schema.json](json-schema/better-stack-heartbeat-attributes-schema.json)
- [better-stack-heartbeat-create-request-schema.json](json-schema/better-stack-heartbeat-create-request-schema.json)
- [better-stack-heartbeat-list-response-schema.json](json-schema/better-stack-heartbeat-list-response-schema.json)
- [better-stack-heartbeat-object-schema.json](json-schema/better-stack-heartbeat-object-schema.json)
- [better-stack-heartbeat-single-response-schema.json](json-schema/better-stack-heartbeat-single-response-schema.json)
- [better-stack-heartbeat-update-request-schema.json](json-schema/better-stack-heartbeat-update-request-schema.json)
- [better-stack-incident-attributes-schema.json](json-schema/better-stack-incident-attributes-schema.json)
- [better-stack-incident-create-request-schema.json](json-schema/better-stack-incident-create-request-schema.json)
- [better-stack-incident-list-response-schema.json](json-schema/better-stack-incident-list-response-schema.json)
- [better-stack-incident-object-schema.json](json-schema/better-stack-incident-object-schema.json)
- [better-stack-incident-single-response-schema.json](json-schema/better-stack-incident-single-response-schema.json)
- [better-stack-monitor-attributes-schema.json](json-schema/better-stack-monitor-attributes-schema.json)
- [better-stack-monitor-create-request-schema.json](json-schema/better-stack-monitor-create-request-schema.json)
- [better-stack-monitor-list-response-schema.json](json-schema/better-stack-monitor-list-response-schema.json)
- [better-stack-monitor-object-schema.json](json-schema/better-stack-monitor-object-schema.json)
- [better-stack-monitor-single-response-schema.json](json-schema/better-stack-monitor-single-response-schema.json)
- [better-stack-monitor-update-request-schema.json](json-schema/better-stack-monitor-update-request-schema.json)
- [better-stack-pagination-schema.json](json-schema/better-stack-pagination-schema.json)
- [better-stack-policy-attributes-schema.json](json-schema/better-stack-policy-attributes-schema.json)
- [better-stack-policy-create-request-schema.json](json-schema/better-stack-policy-create-request-schema.json)
- [better-stack-policy-list-response-schema.json](json-schema/better-stack-policy-list-response-schema.json)
- [better-stack-policy-object-schema.json](json-schema/better-stack-policy-object-schema.json)
- [better-stack-policy-single-response-schema.json](json-schema/better-stack-policy-single-response-schema.json)
- [better-stack-policy-step-schema.json](json-schema/better-stack-policy-step-schema.json)
- [better-stack-policy-update-request-schema.json](json-schema/better-stack-policy-update-request-schema.json)
- [better-stack-response-times-response-schema.json](json-schema/better-stack-response-times-response-schema.json)
- [better-stack-status-page-attributes-schema.json](json-schema/better-stack-status-page-attributes-schema.json)
- [better-stack-status-page-create-request-schema.json](json-schema/better-stack-status-page-create-request-schema.json)
- [better-stack-status-page-list-response-schema.json](json-schema/better-stack-status-page-list-response-schema.json)
- [better-stack-status-page-object-schema.json](json-schema/better-stack-status-page-object-schema.json)
- [better-stack-status-page-single-response-schema.json](json-schema/better-stack-status-page-single-response-schema.json)
- [better-stack-status-page-update-request-schema.json](json-schema/better-stack-status-page-update-request-schema.json)
- [better-stack-team-member-attributes-schema.json](json-schema/better-stack-team-member-attributes-schema.json)
- [better-stack-team-member-invite-request-schema.json](json-schema/better-stack-team-member-invite-request-schema.json)
- [better-stack-team-member-list-response-schema.json](json-schema/better-stack-team-member-list-response-schema.json)
- [better-stack-team-member-object-schema.json](json-schema/better-stack-team-member-object-schema.json)
- [better-stack-team-member-single-response-schema.json](json-schema/better-stack-team-member-single-response-schema.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Better Stack API](capabilities/shared/better-stack.yaml) — 24 operations for uptime monitoring, heartbeats, incidents, status pages, escalation policies, and team management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Incident Response](capabilities/incident-response.yaml) | Better Stack | 11 | SRE Engineer, On-Call Engineer |

## Vocabulary

- [Better Stack Vocabulary](vocabulary/better-stack-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 8 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Better Stack Spectral Rules](rules/better-stack-spectral-rules.yml) — 38 rules across 13 categories enforcing Better Stack API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
