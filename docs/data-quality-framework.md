# Data Quality Frameworkhttps://github.com/MuhammadBilalAlam1092/data-governance-catalogue-framework/tree/main/docs/docs

This document defines the data quality dimensions and rule structure used in the catalogue framework.

## Purpose

Data quality rules help organisations understand whether data is complete, valid, consistent, timely and suitable for reporting, analytics and AI-enabled use cases.

The goal is not to create a complicated data quality system. The goal is to create practical checks that make data issues visible and manageable.

## Data Quality Dimensions

| Dimension | Meaning | Example |
|---|---|---|
| Completeness | Required fields are populated | Organisation name should not be blank |
| Uniqueness | Records are not duplicated | Organisation ID should be unique |
| Validity | Values follow an expected format | Email address should contain @ |
| Consistency | Values align across systems | Organisation name should match CRM |
| Timeliness | Data is refreshed as expected | Dataset should refresh monthly |
| Accuracy | Data reflects the real-world entity | Facility status should be correct |

## Rule Structure

Each data quality rule should include:

- Rule ID
- Dataset name
- Field name
- Quality dimension
- Rule description
- Expected result
- Severity
- Owner
- Status

## Severity Levels

| Severity | Meaning |
|---|---|
| High | Issue may affect reporting, decisions or business-critical use |
| Medium | Issue should be reviewed but may not block usage |
| Low | Issue is minor or informational |

## Example Rules

| Rule ID | Dataset | Field | Dimension | Rule |
|---|---|---|---|---|
| DQR001 | CRM Organisations | organisation_id | Uniqueness | Organisation ID should be unique |
| DQR002 | CRM Organisations | organisation_name | Completeness | Organisation name should not be blank |
| DQR003 | NHS ODS Organisations | postcode | Validity | Postcode should follow expected UK format |
| DQR004 | Energy Consumption | consumption_kwh | Validity | Consumption value should be greater than or equal to zero |

## Data Quality Score

A simple quality score can be calculated as:

```text
Passed rules / Total rules
