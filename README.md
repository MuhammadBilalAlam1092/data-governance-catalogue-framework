
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

## Repository Structure

```text
data-governance-catalogue-framework/
│
├── docs/
│   └── operating-model.md
│
├── templates/
│   └── dataset-catalogue-template.csv
│
├── sample_catalogue/
│   └── datasets.csv
│
├── diagrams/
│   └── README.md
│
├── case_study/
│   └── governance-catalogue-case-study.md
│
└── README.md
