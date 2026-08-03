# Amazon Incident Manager (amazon-incident-manager)

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
