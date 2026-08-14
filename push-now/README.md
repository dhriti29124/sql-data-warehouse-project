# SQL Data Warehouse Project (in progress)

Following along with Data with Baraa's SQL course, building a Medallion-architecture
(Bronze / Silver / Gold) data warehouse in SQL Server / T-SQL.

## Structure
- `datasets/` — raw source CSVs (CRM + ERP)
- `scripts/bronze` — raw ingestion DDL + load procedure
- `scripts/silver` — cleansing/transformation DDL + load procedure
- `scripts/gold` — star schema views (dim_customers, dim_products, fact_sales)
- `tests/` — data quality validation checks
- `docs/` — naming conventions and data catalog

## Status
Scaffold in place. Next: adapt scripts to run against Postgres locally, execute
the pipeline end-to-end, and validate with the quality checks.

_Work in progress — committing early to keep momentum going._
