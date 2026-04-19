# Amazon Incident Manager (amazon-incident-manager)
AWS Systems Manager Incident Manager is an incident management console designed to help users mitigate and recover from incidents affecting their AWS-hosted applications. It enables faster incident resolution by automating response plans and engaging responders across notification channels.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-incident-manager/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Automation, AWS, DevOps, Incident Management, Operations

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### AWS Systems Manager Incident Manager API
The AWS Systems Manager Incident Manager API provides programmatic access to create and manage response plans, incidents, timelines, related items, and replication sets for automated incident response.

**Human URL:** [https://aws.amazon.com/systems-manager/features/#Incident_Manager](https://aws.amazon.com/systems-manager/features/#Incident_Manager)

#### Tags:

 - DevOps, Incident Management, Operations

#### Properties

- [Documentation](https://docs.aws.amazon.com/incident-manager/latest/APIReference/Welcome.html)
- [OpenAPI](openapi/amazon-incident-manager-openapi-original.yml)
- [GettingStarted](https://docs.aws.amazon.com/incident-manager/latest/userguide/getting-started.html)
- [Pricing](https://aws.amazon.com/systems-manager/pricing/)
- [FAQ](https://aws.amazon.com/systems-manager/faq/)

## Common Properties

- [Portal](https://aws.amazon.com/systems-manager/features/#Incident_Manager)
- [Website](https://aws.amazon.com/systems-manager/)
- [Documentation](https://docs.aws.amazon.com/incident-manager/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Blog](https://aws.amazon.com/blogs/mt/tag/aws-systems-manager-incident-manager/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/systems-manager/incidents/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)

## Features

| Name | Description |
|------|-------------|
| Automated Response Plans | Create response plans that automatically engage responders and execute runbooks when incidents occur. |
| Incident Tracking | Track incident status, severity, and timeline in real time from a centralized console. |
| Multi-Channel Notifications | Notify responders via SMS, email, voice, and PagerDuty through contact channels. |
| Runbook Automation | Automatically run Systems Manager Automation runbooks as part of incident response. |
| Post-Incident Analysis | Generate analysis reports with timeline events to identify root causes and improve future response. |
| Multi-Region Replication | Replicate incident data across multiple AWS regions for global incident management. |

## Use Cases

| Name | Description |
|------|-------------|
| On-Call Management | Define escalation policies and on-call schedules to ensure the right responders are engaged. |
| Automated Incident Detection | Integrate with CloudWatch alarms and EventBridge to automatically trigger response plans. |
| Cross-Team Coordination | Coordinate incident response across multiple teams with shared incident channels. |
| Compliance and Audit | Maintain incident timelines and analysis reports for regulatory compliance and audits. |

## Integrations

| Name | Description |
|------|-------------|
| Amazon CloudWatch | Trigger incident response plans automatically from CloudWatch alarms. |
| AWS Systems Manager Automation | Run automation runbooks as part of incident response workflows. |
| PagerDuty | Integrate with PagerDuty for on-call management and notification. |
| AWS Chatbot | Receive incident notifications and updates in Slack or Microsoft Teams. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [AWS Systems Manager Incident Manager API](openapi/amazon-incident-manager-openapi-original.yml)

### JSON Schema

125 schema files covering incidents, response plans, timeline events, and replication sets.

### JSON Structure

125 JSON Structure files converted from JSON Schema.

### JSON-LD

- [Amazon Incident Manager Context](json-ld/amazon-incident-manager-context.jsonld)

### Examples

125 example JSON files generated from schemas.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [SSM Incidents API](capabilities/shared/ssm-incidents.yaml) — operations for response plans and incidents

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Incident Response](capabilities/incident-response.yaml) | SSM Incidents | 7 | Operations Engineer, Site Reliability Engineer |

## Vocabulary

- [Amazon Incident Manager Vocabulary](vocabulary/amazon-incident-manager-vocabulary.yaml) — Unified taxonomy mapping 5 resources, 5 actions, 1 workflow, and 2 personas

## Rules

- [Amazon Incident Manager Spectral Rules](rules/amazon-incident-manager-spectral-rules.yml) — 14 rules across 6 categories enforcing Amazon Incident Manager API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
