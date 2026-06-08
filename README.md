# databricks-dbt-cost-quality-scorecard

Databricks dbt Cost Quality Scorecard is a Kinetic Gain portfolio proof repo for **Databricks, dbt** across Data Engineering.

It turns notebook cost pressure, dbt model quality, transformation debt, and warehouse savings posture into a small board-readable intelligence packet: where risk is building, where money is leaking, what deserves investment, and what story leaders can tell with evidence.

## Platform and company signals

- Databricks
- dbt

## What it includes

- runnable Node CLI for summarizing synthetic control-plane lanes
- JSON fixture with exposure, savings, and investment lanes
- static proof page in site/index.html
- lightweight CI using Node's built-in test runner
- no production credentials, no customer data, no external API calls

## Local run

`powershell
npm test
npm run demo
npm run build
`

## Output shape

`json
{
  "product": "Databricks dbt Cost Quality Scorecard",
  "signals": ["Databricks", "dbt"],
  "averageScore": 82,
  "priorityLane": "investment"
}
`

## Kinetic Gain fit

This repo supports the Platform and Company Signals layer of the portfolio atlas. It is intentionally small, readable, and evidence-oriented so executives can see the operating pattern without requiring access to live enterprise systems.