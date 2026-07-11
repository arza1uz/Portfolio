# Lexian Roadmap

Lexian is a fictional fintech engineering ecosystem used to organize a long-term public portfolio. It uses synthetic data only and does not represent a real company, customer base, or production system.

## Current And Near-Term

| Product | Status | Purpose |
| --- | --- | --- |
| Lexian Transaction Engine | Released / v1.0.0 | Process synthetic transactions, validate input data, calculate balances, generate reports, and document the first public product baseline |
| Lexian Operational Observability | Released / v1.0.0 | Track pipeline executions, structured logs, lifecycle events, and operational context |
| Lexian Local Analytical Warehouse | Released / v1.1.0 | Add DuckDB warehouse foundations, schema design, raw/fact tables, SQL queryability, and execution metadata |
| Lexian Warehouse Analytics Queries | In Progress / on main | Add SQL queries for balances, execution health, transaction volume, data quality, and validation |

## Planned Portfolio Milestones

| Product / Capability | Status | Purpose |
| --- | --- | --- |
| Lexian Reconciliation Engine | Planned | Compare internal transactions against external payment or settlement records |
| Lexian Graph Auditability | Planned | Model reconciliation lineage and investigation trails with Neo4j/Cypher |
| Lexian Analytics Engineering Layer | Planned | Add dbt-style models, marts, tests, documentation, KPI definitions, and BI readiness |
| Lexian Cloud Data Platform | Planned | Prototype AWS-oriented data workflows with S3, Glue, Athena, Lambda, and Redshift |
| Lexian ML / Risk Platform | Planned | Build feature pipelines, evaluation workflows, and risk/fraud foundations |
| Lexian AI Investigation Assistant | Planned | Explore RAG, AI evaluation, and operations-focused assistant workflows |

## Repository Boundary

Lexian should not become a giant monorepo. Each major product should be independently understandable, independently testable, and clearly scoped.
