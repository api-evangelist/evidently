# Evidently AI (evidently)

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
