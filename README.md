# Evidently AI (evidently)

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

Evidently AI is an open-source ML and LLM observability framework licensed under Apache 2.0 that enables teams to evaluate, test, and monitor AI-powered systems and data pipelines in production. The platform provides over 100 built-in metrics for tracking data drift, data quality, and model performance across both tabular data and generative AI workloads. Developers can integrate evaluations programmatically via the Python SDK or through the Evidently Platform REST API, which exposes endpoints for managing projects, uploading traces, running evaluations, and storing results. Evidently supports self-hosted deployments and previously offered Evidently Cloud (now discontinued as SaaS), so teams can run the full platform within their own infrastructure.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/evidently/refs/heads/main/apis.yml

**Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=evidently-api-evangelist&utm_content=repo

---

## Tags

- ML Monitoring
- LLM Observability
- Data Drift
- Model Performance
- AI Evaluation
- Data Quality
- Open Source
- MLOps
- LLMOps
- Generative AI

---

## APIs

### Evidently Platform REST API

The Evidently Platform REST API provides programmatic access to the observability platform for managing projects, uploading evaluation results, storing traces, running scheduled evaluations, and querying monitoring dashboards. Authentication uses bearer token (API key) via the `EVIDENTLY_API_KEY` environment variable or the `CloudWorkspace` Python client. Base URL: `https://app.evidently.cloud`.

- **Documentation:** https://docs.evidentlyai.com/
- **OpenAPI Spec:** https://docs.evidentlyai.com/api-reference/openapi.json
- **Python SDK:** https://pypi.org/project/evidently/
- **GitHub:** https://github.com/evidentlyai/evidently

---

## Plans, Rate Limits, and FinOps

| Resource | File |
|---|---|
| Plans and Pricing | [plans/evidently-plans-pricing.yml](plans/evidently-plans-pricing.yml) |
| Rate Limits | [rate-limits/evidently-rate-limits.yml](rate-limits/evidently-rate-limits.yml) |
| FinOps Framework | [finops/evidently-finops.yml](finops/evidently-finops.yml) |

**Pricing summary:** The OSS library and self-hosted platform are free (Apache 2.0). The commercial Expert tier starts at approximately $500/month with per-data-volume overages. Enterprise is custom-quoted. Evidently Cloud SaaS is no longer available; all commercial deployments are self-hosted.

---

## Timestamps

| Field | Value |
|---|---|
| Created | 2026-06-13 |
| Modified | 2026-06-13 |

---

## Common Resources

| Type | URL |
|---|---|
| Website | https://www.evidentlyai.com/ |
| Documentation | https://docs.evidentlyai.com/ |
| GitHub Org | https://github.com/evidentlyai |
| LinkedIn | https://www.linkedin.com/company/evidently-ai/ |
| Blog | https://www.evidentlyai.com/blog |
| Pricing | https://www.evidentlyai.com/pricing |
| X (Twitter) | https://twitter.com/EvidentlyAI |

---

## Maintainers

**Kin Lane** — kin@apievangelist.com
