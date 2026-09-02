# 02 — Data Quality Assessment

## Purpose

Before starting the churn analysis, the dataset was reviewed to understand its structure, quality, and suitability for the investigation.

The audit focuses on missing values, duplicates, data types, inconsistent values, outliers, and other issues that could affect the analysis.

---

## Dataset Overview

| Item            | Details                |
| --------------- | ---------------------- |
| Source          | Customer Churn Dataset |
| Records         | To be determined       |
| Columns         | To be determined       |
| Target Variable | Churn                  |
| Analysis Period | Six months             |
| Tool            | Power BI / Power Query |

---

## Quality Checks

The following checks will be performed:

### 1. Missing Values

Check columns for:

- Null values
- Blank values
- Unexpected missing records

Missing values will be handled based on the meaning of each column rather than applying one method to all fields.

### 2. Duplicate Records

Customer identifiers will be checked for duplicate records.

Duplicates will be removed only where they represent repeated records and are not legitimate multiple entries.

### 3. Data Types

Column types will be reviewed for:

- Dates
- Numeric fields
- Currency/charges
- Categorical fields
- Boolean fields

Incorrect data types will be corrected before analysis.

### 4. Categorical Values

Categories will be checked for inconsistencies such as:

```text
"Yes" / "yes"
"Monthly" / "monthly"
"Male" / "M"
```

Where appropriate, these values will be standardized.

### 5. Numerical Values and Outliers

Numerical fields such as charges, tenure, usage, and revenue will be checked for:

- Negative values where not applicable
- Unrealistic values
- Extreme observations
- Incorrect units

Outliers will not automatically be removed. They will be reviewed based on business meaning.

### 6. Date Validation

Date fields will be checked for:

- Invalid dates
- Future dates where inappropriate
- Incorrect date formats
- Records outside the analysis period

This is particularly important because the assessment requires analysis of the churn increase over time.

---

## Data Preparation Rules

The following principles will be followed during preprocessing:

| Issue                     | Treatment                              |
| ------------------------- | -------------------------------------- |
| Missing categorical value | Appropriate category or null treatment |
| Missing numerical value   | Context-dependent treatment            |
| Duplicate record          | Remove if confirmed duplicate          |
| Incorrect data type       | Convert to appropriate type            |
| Inconsistent category     | Standardize                            |
| Invalid value             | Correct or exclude where justified     |
| Outlier                   | Investigate before deciding            |
| Invalid date              | Correct or exclude if necessary        |

All significant transformations will be performed in **Power Query** and documented where they affect the analysis.

---

## Data Suitability

The dataset needs to contain sufficient information to investigate:

- Churn over time
- Customer segments
- Pricing
- Product/service factors
- Competition
- Service quality
- Revenue impact

If any required information is unavailable, that limitation will be clearly mentioned in the final analysis rather than making unsupported conclusions.

---

## Audit Summary

The detailed results of the quality checks will be added after the raw dataset has been audited.

Key issues identified:

- **Missing values:** To be determined
- **Duplicate records:** To be determined
- **Data-type issues:** To be determined
- **Inconsistent categories:** To be determined
- **Outliers:** To be determined
- **Date issues:** To be determined
