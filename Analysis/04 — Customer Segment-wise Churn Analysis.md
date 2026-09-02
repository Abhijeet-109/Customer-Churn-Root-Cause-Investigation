# 04 — Customer Segment-wise Churn Analysis

## Objective

The customer base was segmented across key demographic, subscription, pricing, usage, and service-related attributes to identify groups with higher churn and determine where the increase in churn was concentrated.

---

## Segments Analyzed

The analysis covers relevant customer segments such as:

- Contract type
- Tenure group
- Monthly charges
- Payment method
- Service / product type
- Customer demographics
- Support and service usage
- Competitive indicators

Only segments with meaningful variation in customer count and churn rate were considered for comparison.

---

## Segment Churn Analysis

For each segment, churn was evaluated using:

```text
Segment Churn Rate =
Churned Customers in Segment / Total Customers in Segment × 100
```

The analysis compares both **churn rate** and **number of churned customers**.

This distinction is important because a small segment can have a high churn rate while contributing relatively few churned customers, whereas a larger segment may have a lower rate but a much larger overall impact.

---

## High-Risk Segments

The segment analysis focuses on identifying:

- Segments with the highest churn rate
- Segments with the largest number of churned customers
- Segments where churn increased most during the affected period
- High-value segments with elevated churn
- Combinations of characteristics associated with higher churn

These segments are used as the primary focus for the root cause investigation.

---

## Segment Comparison

The following comparisons are particularly relevant to the assessment:

| Area | Comparison |
|---|---|
| Contract | Short-term vs long-term customers |
| Tenure | Newer vs established customers |
| Pricing | Lower vs higher charge groups |
| Service | Customers with vs without service issues |
| Support | Different levels of support interaction |
| Competition | Customers exposed vs not exposed to competitive pressure |
| Product | Different product/service groups |

---

## Key Findings

The segment analysis identified differences in churn across customer groups rather than a uniform increase across the entire customer base.

The highest-risk groups were evaluated using both their **churn rate and customer volume** to avoid ranking segments solely by percentage.

The results from this analysis are used in the root cause investigation to determine whether the characteristics of high-churn segments are connected to pricing, product issues, competition, or service quality.

---

## Business Interpretation

Segment-level analysis helps answer an important business question:

> **Who is leaving at the highest rate, and where should retention efforts be focused?**

The findings provide the basis for testing whether the observed segment differences are linked to specific underlying factors and whether those factors contributed to the overall increase in churn.