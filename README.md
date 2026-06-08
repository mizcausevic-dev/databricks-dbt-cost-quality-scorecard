# Databricks dbt Cost Quality Scorecard

Databricks dbt Cost Quality Scorecard turns Databricks, dbt operating evidence into board-ready exposure, savings, investment, and narrative decisions.

## What it answers

Can leadership explain where Databricks, dbt creates exposure, savings opportunity, investment priority, or board-visible execution risk?

## Decision lanes

- **Exposure** (82) — Unowned notebook cost pressure, dbt model quality, transformation debt, and warehouse savings posture Next: Assign an accountable owner and evidence path
- **Savings** (76) — Duplicated tooling and stale workflow evidence Next: Quantify recoverable spend and remove duplicated handoffs
- **Investment** (88) — Critical control plane needs clearer funding priority Next: Package the strongest board-ready investment narrative

## Operating workflow

- **Ingest:** Collect Databricks + dbt operating evidence without exposing credentials or raw customer data.
- **Score:** Translate exceptions into exposure, savings, investment, and narrative confidence lanes.
- **Route:** Assign each lane to one accountable owner with a next action and review window.
- **Package:** Produce a board-ready packet with decisions, tradeoffs, and proof links.

## Board pack outputs

- One-page Data Engineering decision brief
- Databricks / dbt exposure and ownership map
- Priority lane: Investment
- Savings, remediation, and investment narrative
- Public-demo boundary and evidence-source notes

## Local run

```bash
npm install
npm test
npm run build
```

## Links

- [Portfolio atlas](https://portfolio.kineticgain.com/)
- [Kinetic Gain](https://kineticgain.com/)
- [GitHub repo](https://github.com/mizcausevic-dev/databricks-dbt-cost-quality-scorecard)
- [Databricks surface](https://databricks.kineticgain.com/)
- [dbt surface](https://dbt.kineticgain.com/)

## Public-demo boundary

No production credentials, customer records, private contracts, or admin-console exports belong in this repo. Fixtures are synthetic and intended to prove the decision shape only.
