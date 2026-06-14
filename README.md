
# Data Governance & Catalogue Framework

A practical framework for turning scattered datasets into governed, searchable and AI-ready data products.

## Overview

Many organisations have data spread across spreadsheets, CRM systems, public datasets, APIs and BI reports. The problem is not only where the data lives, but whether people understand what it means, who owns it, which KPIs are trusted and whether the data is ready for analytics or AI use cases.

This project provides a lightweight but practical framework for documenting datasets, defining ownership, managing business glossary terms, applying data quality rules and creating a foundation for trusted reporting, Microsoft Fabric data products and AI-enabled data discovery.

## Problem

Organisations often struggle with:

- Scattered datasets across teams, systems and spreadsheets
- Unclear ownership of data sources and reports
- Inconsistent KPI and metric definitions
- Limited visibility of which datasets feed which reports
- Weak documentation around data quality and refresh frequency
- Difficulty preparing data for AI and self-service analytics

## Solution

This framework introduces a simple governance and catalogue structure that helps organisations document, standardise and manage their data assets.

It covers:

- Data source registration
- Dataset catalogue design
- Business glossary management
- KPI and metric definitions
- Data ownership and stewardship
- Data quality rules
- Catalogue lifecycle process
- Source-to-report metadata structure

## Who This Is For

This project is designed for:

- Data and analytics teams
- BI and reporting teams
- Organisations starting their data governance journey
- Teams building Microsoft Fabric or lakehouse-style data products
- Consultants helping organisations improve data maturity
- Teams preparing metadata for AI-enabled analytics assistants


## Current MVP Scope

This first version focuses on creating a lightweight, reusable governance and catalogue framework that can be applied across multiple sectors.

The MVP includes:

- Governance operating model
- Catalogue management process
- Data quality framework
- Dataset catalogue template
- Business glossary template
- KPI definition template
- Data quality rules template
- Sample catalogue records
- Source-to-report lineage example
- Case study explaining the problem, approach and impact

## Repository Structure

```text
data-governance-catalogue-framework/
│
├── docs/
│   ├── catalogue-process.md
│   ├── data-quality-framework.md
│   └── operating-model.md
│
├── sample_catalogue/
│   ├── data_sources.csv
│   ├── datasets.csv
│   ├── fields.csv
│   ├── kpis.csv
│   ├── lineage.csv
│   └── reports.csv
│
├── templates/
│   ├── business-glossary-template.csv
│   ├── data-quality-rules-template.csv
│   ├── dataset-catalogue-template.csv
│   └── kpi-definition-template.csv
│
├── case_study/
│   └── governance-catalogue-case-study.md
│
├── diagrams/
│   └── README.md
│
└── README.md
