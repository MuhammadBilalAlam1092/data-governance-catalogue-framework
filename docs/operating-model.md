

# Governance Operating Model

This document defines the roles, responsibilities and decision-making structure for a practical data governance and catalogue framework.

## Purpose

The purpose of the governance operating model is to make sure data assets are clearly owned, documented, trusted and maintained over time.

A data catalogue is only useful if the organisation has clear responsibilities for who owns the data, who maintains the definitions, who manages the technical implementation and who uses the data for decision-making.

## Governance Principles

The framework is based on the following principles:

- Every important dataset should have a named owner
- Every dataset should have clear business definitions
- Key fields and KPIs should be documented
- Data quality rules should be visible and monitored
- Users should be able to understand where data comes from and how it is used
- Metadata should support reporting, analytics, data products and AI-enabled discovery

## Roles and Responsibilities

| Role | Responsibility |
|---|---|
| Data Owner | Accountable for the meaning, usage, access and business value of a dataset |
| Data Steward | Maintains definitions, metadata, quality rules and documentation |
| Technical Owner | Manages pipelines, storage, refreshes, transformations and technical implementation |
| Report Owner | Owns dashboard usage, report interpretation and adoption |
| Data Consumer | Uses data products, reports and insights for decisions |
| Governance Lead | Coordinates standards, policies, issue resolution and catalogue adoption |

## Example RACI Model

| Activity | Data Owner | Data Steward | Technical Owner | Report Owner | Governance Lead |
|---|---|---|---|---|---|
| Register new dataset | A | R | C | C | C |
| Define business terms | A | R | C | C | C |
| Define KPI logic | A | R | C | R | C |
| Create data quality rules | A | R | C | C | C |
| Build pipeline or model | C | C | R | C | C |
| Approve dataset for reporting | A | R | C | C | C |
| Monitor catalogue completeness | C | R | C | C | A |
| Resolve data quality issue | A | R | R | C | C |

R = Responsible  
A = Accountable  
C = Consulted

## Decision-Making Structure

The operating model can work with a lightweight governance structure:

```text
Data Governance Lead
        ↓
Data Owners
        ↓
Data Stewards
        ↓
Technical Owners
        ↓
Report Owners and Data Consumers
