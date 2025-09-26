# FinCrime EDA

## Project Overview

This repository provides a best-practices template for conducting Exploratory Data Analysis (EDA) in a fully managed, cloud-only environment. It is tailored for financial crime (FinCrime) analytics, supporting transparency, collaboration, and reproducibility.

## Repository Structure

See [EDA-Repository-Best-Practices.md](EDA-Repository-Best-Practices.md) for a detailed explanation.

### Key Directories

- `notebooks/` – Jupyter/Databricks notebooks organized by activity
- `queries/` – SQL/Spark queries for data extraction and transformation
- `src/` – Utility code, helpers, or modules
- `outputs/` – Exported plots, tables, reports, and results
- `data/raw/` – Unprocessed, original datasets
- `data/processed/` – Cleaned and transformed datasets
- `docs/` – Documentation, workflows, infra requests, and collaboration notes

## Cloud Workflow

- All data processing and analysis is performed on managed cloud environments (e.g., EMR, Databricks).
- No local execution is expected; notebooks, queries, and outputs are exported and versioned here.
- Collaboration with infra teams is tracked via docs.

## How to Use

1. Organize your notebooks by activity using the `notebooks/` subfolders.
2. Store queries and code snippets in `queries/` and `src/`.
3. Document all analysis steps, findings, and infra requests in `docs/`.
4. Export and store key plots, tables, and reports in `outputs/`.
5. Reference or link to sensitive findings in Confluence or secure locations if needed.

## Contact & Collaboration

- For infra issues or cloud access, see `docs/infra_requests.md`.
- For sensitive or internal notes, see the links in `docs/README.md`.