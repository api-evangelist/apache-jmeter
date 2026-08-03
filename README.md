# Apache JMeter (apache-jmeter)

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

Apache JMeter is an open-source Java application designed for load testing functional behavior and measuring performance. It supports web applications, REST APIs, databases, LDAP, FTP, and other protocols.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/apache-jmeter/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Testing, Java, Load Testing, Open Source, Performance Testing, Stress Testing

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Apache JMeter REST API
The JMeter REST API provides HTTP endpoints for remotely starting, stopping, and monitoring load tests, as well as retrieving test results.

**Human URL:** [https://jmeter.apache.org/usermanual/remote-test.html](https://jmeter.apache.org/usermanual/remote-test.html)

#### Tags:

 - Performance Testing, REST, Test Control

#### Properties

- [Documentation](https://jmeter.apache.org/usermanual/remote-test.html)
- [OpenAPI](openapi/apache-jmeter-rest-api.yaml)

### Apache JMeter CLI
JMeter command-line interface for running load tests in non-GUI mode for CI/CD integration.

**Human URL:** [https://jmeter.apache.org/usermanual/get-started.html#non_gui](https://jmeter.apache.org/usermanual/get-started.html#non_gui)

#### Tags:

 - CLI, Performance Testing

#### Properties

- [Documentation](https://jmeter.apache.org/usermanual/get-started.html#non_gui)

## Common Properties

- [GitHubOrganization](https://github.com/apache)
- [GitHubRepository](https://github.com/apache/jmeter)
- [Documentation](https://jmeter.apache.org/usermanual/)
- [GettingStarted](https://jmeter.apache.org/usermanual/get-started.html)
- [TermsOfService](https://www.apache.org/licenses/LICENSE-2.0)
- [Blog](https://blogs.apache.org/jmeter/)
- [Versioning](https://jmeter.apache.org/changes.html)
- [SpectralRules](rules/apache-jmeter-spectral-rules.yml)
- [Vocabulary](vocabulary/apache-jmeter-vocabulary.yaml)
- [NaftikoCapability](capabilities/load-test-management.yaml)

## Features

| Name | Description |
|------|-------------|
| HTTP Load Testing | Test web applications and REST APIs with configurable thread groups and ramp-up. |
| Protocol Support | Support for HTTP, HTTPS, FTP, JDBC, LDAP, SMTP, TCP, and JMS. |
| Distributed Testing | Distributed load generation using JMeter remote testing architecture. |
| Rich Reporting | Built-in listeners and HTML dashboard reporting for test results. |
| Plugin Ecosystem | Extensive plugin marketplace for additional samplers, listeners, and functions. |
| CI/CD Integration | Non-GUI mode and REST API for integration with Jenkins, GitHub Actions, and more. |
| Assertions | Response assertion engine for functional validation during load tests. |

## Use Cases

| Name | Description |
|------|-------------|
| API Performance Testing | Measure REST API response times and throughput under load. |
| Web Application Load Testing | Simulate concurrent users on web applications to find performance bottlenecks. |
| CI/CD Performance Gates | Integrate performance testing into CI/CD pipelines with automated pass/fail criteria. |
| Stress Testing | Determine system breaking points through progressive load increase. |

## Integrations

| Name | Description |
|------|-------------|
| Jenkins | JMeter Performance Plugin for integrating load tests in Jenkins pipelines. |
| GitHub Actions | Run JMeter tests via CLI in GitHub Actions workflows. |
| Grafana and InfluxDB | Stream JMeter results to InfluxDB for real-time Grafana dashboards. |
| Maven | JMeter Maven Plugin for running tests as part of Maven builds. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Apache JMeter REST API](openapi/apache-jmeter-rest-api.yaml)

### JSON Schema

4 schema files extracted from the REST API OpenAPI specification.

### JSON Structure

4 JSON Structure files converted from JSON Schema files.

### JSON-LD

- [Apache JMeter REST API Context](json-ld/apache-jmeter-rest-api-context.jsonld)

### Examples

4 example JSON files generated from JSON Schema definitions.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Apache JMeter REST API](capabilities/shared/jmeter-rest-api.yaml) — 3 operations for test execution and result retrieval

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Apache JMeter Load Test Management](capabilities/load-test-management.yaml) | Apache JMeter REST API | 4 | QA Engineer, Performance Engineer |

## Vocabulary

- [Apache JMeter Vocabulary](vocabulary/apache-jmeter-vocabulary.yaml) — Unified taxonomy mapping 2 resources, 4 actions, 1 workflow, and 2 personas

## Rules

- [Apache JMeter Spectral Rules](rules/apache-jmeter-spectral-rules.yml) — 12 rules across 7 categories enforcing Apache JMeter REST API conventions

## Maintainers

**FN:** Kin Lane

**Email:** info@apievangelist.com
