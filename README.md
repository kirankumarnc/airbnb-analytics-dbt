# Airbnb Analytics Engineering with dbt and Snowflake

## Project Overview

This project focuses on building an analytics engineering workflow using dbt Core and Snowflake to transform Airbnb data into structured, reliable, and analytics-ready datasets.

The objective is to develop modular SQL transformations, establish data quality checks, document data models, and prepare datasets for downstream analytics and business intelligence.

## Business Objectives

- Transform raw Airbnb data into clean and structured datasets.
- Build modular and reusable SQL transformations using dbt.
- Organize transformations into logical data modeling layers.
- Implement data quality checks to improve data reliability.
- Document data models and transformation dependencies.
- Prepare analytics-ready datasets for reporting and business analysis.

## Technology Stack

| Technology | Purpose |
|---|---|
| Snowflake | Cloud data warehouse |
| dbt Core | Data transformation, testing, and documentation |
| SQL | Data transformation and modeling |
| Python | Local development environment for dbt |
| Git | Version control |
| GitHub | Source code management and documentation |
| VS Code | Development environment |


## Data Modeling Approach

### 1. Staging Layer

- Standardize column names and data types.
- Apply basic data cleaning and transformations.
- Establish consistent representations of source data.

### 2. Intermediate Layer

- Apply reusable business logic.
- Combine staging models where required.
- Prepare transformed data for analytical models.

### 3. Marts Layer

- Build business-oriented datasets for analytical consumption.
- Organize data into appropriate models.
- Prepare datasets for reporting and business intelligence.

These layers will be developed as the project progresses.

## Data Quality and Testing

Data quality is an important part of the transformation workflow. The project will incorporate appropriate dbt tests to validate model assumptions and improve data reliability.

Planned areas include:

- Uniqueness and non-null checks.
- Referential integrity checks where applicable.
- Model documentation.
- Validation of transformation logic.

## Repository Structure

```text
airbnb-analytics-dbt/
├── README.md
├── .gitignore
├── .venv/
└── dbt_airbnb/
    ├── dbt_project.yml
    ├── models/
    ├── macros/
    ├── seeds/
    ├── snapshots/
    ├── tests/
    └── analyses/
```

The `.venv` directory is local to the development environment and should be excluded from version control. The repository structure may evolve as additional dbt resources are implemented.

## Development Environment

The project is developed using VS Code and a Python virtual environment, with dbt Core configured to connect to Snowflake.

Git and GitHub are used to track changes, maintain project history, and document the development process.

## Current Status

**In Progress**

- Local development environment configured.
- dbt Core and the Snowflake adapter installed.
- Snowflake connection successfully validated.
- Project repository created on GitHub.
- Data transformation models and testing workflows are being developed.

## Future Enhancements

- Complete staging, intermediate, and marts models.
- Add model-level documentation and data quality tests.
- Review model dependencies and transformation lineage.
- Evaluate incremental processing where appropriate.
- Generate dbt documentation.
- Identify analytical use cases supported by the resulting datasets.

## Key Learnings

This project provides practical experience in analytics engineering, SQL-based transformations, data modeling, cloud data warehousing, data quality, documentation, and version control.

---
