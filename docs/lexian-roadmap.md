# Lexian Roadmap

Lexian is a fictional fintech engineering ecosystem used to organize a long-term public portfolio. It uses synthetic data only and does not represent a real company, customer base, or production system.

## Current And Near-Term

| Product | Status | Purpose |
| --- | --- | --- |
| Lexian Transaction Engine | Active / V1 | Process synthetic transactions, validate input data, calculate balances, generate reports, and document the first public product baseline |
| Lexian Operational Observability | In Progress / V2 | Track pipeline executions, structured logs, lifecycle events, and operational context |

## Planned Portfolio Milestones

| Product / Capability | Status | Purpose |
| --- | --- | --- |
| SQL + Warehouse Foundations | Planned | Add local analytical storage, fact/dim modeling, and advanced SQL practice |
| Lexian Reconciliation Engine | Planned | Compare internal transactions against external payment or settlement records |
| Lexian Graph Auditability | Planned | Model reconciliation lineage and investigation trails with Neo4j/Cypher |
| Lexian Data Platform | Planned | Create warehouse, transformation, orchestration, and data quality foundations |
| Lexian Cloud Data Platform | Planned | Prototype AWS-oriented data workflows with S3, Glue, Athena, Lambda, and Redshift |
| Lexian ML / Risk Platform | Planned | Build feature pipelines, evaluation workflows, and risk/fraud foundations |
| Lexian AI Investigation Assistant | Planned | Explore RAG, AI evaluation, and operations-focused assistant workflows |

## Repository Boundary

Lexian should not become a giant monorepo. Each major product should be independently understandable, independently testable, and clearly scoped.
