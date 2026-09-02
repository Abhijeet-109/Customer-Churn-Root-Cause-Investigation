# 05 — Hypothesis Validation

## Objective

The main potential causes of churn were evaluated using customer-level churn rates and supporting variables in the dataset.

The four primary hypotheses were **pricing, product issues, competition, and service quality**.

---

## H1 — Pricing

**Hypothesis:** Customers with higher monthly charges are more likely to churn.

### Evidence

| Monthly Charge Group | Churn Rate |
|---|---:|
| Lowest | 10.8% |
| Lower-Middle | 12.2% |
| Upper-Middle | 14.6% |
| Highest | 13.5% |

Customers in higher charge groups generally show higher churn than customers with lower charges. Churned customers also have a higher average monthly charge than retained customers.

**Average Monthly Charge**

- Retained: ₹697.24
- Churned: ₹714.35

### Conclusion

**Supported — Pricing is a contributing factor.**

The relationship is not completely linear at the highest charge level, so pricing alone does not explain the full increase in churn.

---

## H2 — Product Issues

**Hypothesis:** Customers experiencing more product issues are more likely to churn.

### Evidence

| Product Issues | Churn Rate |
|---|---:|
| None | 9.0% |
| 1 | 12.3% |
| 2 | 15.8% |
| 3+ | 23.7% |

Churn increases consistently as the number of product issues increases.

Customers who churned also had a higher average number of product issues:

- Retained: 0.96
- Churned: 1.35

### Conclusion

**Strongly Supported — Product issues are a major churn driver.**

The clear step-up in churn across issue levels makes this one of the strongest relationships identified in the analysis.

---

## H3 — Competition

**Hypothesis:** Higher competitive exposure contributes to increased customer churn.

### Evidence

| Competitor Exposure | Churn Rate |
|---|---:|
| Low | 11.6% |
| Medium | 11.8% |
| High | 19.4% |

Customers with high competitor exposure have substantially higher churn than customers with low or medium exposure.

### Conclusion

**Supported — Competitive pressure is a significant contributing factor.**

The increase is particularly visible among customers classified as having high competitive exposure.

---

## H4 — Service Quality

**Hypothesis:** Poor service quality contributes to higher customer churn.

### Evidence

Customer satisfaction and support performance show clear differences between churned and retained customers.

| Metric | Retained | Churned |
|---|---:|---:|
| Satisfaction Score | 6.81 | 6.36 |
| Support Tickets | 1.91 | 2.25 |
| Avg. Response Time | 13.30 hrs | 14.89 hrs |

Churn also increases as support response time becomes longer:

| Response Time | Churn Rate |
|---|---:|
| < 8 hours | 8.9% |
| 8–16 hours | 12.2% |
| 16–24 hours | 15.1% |
| 24+ hours | 22.5% |

### Conclusion

**Strongly Supported — Service quality is a major churn driver.**

Lower satisfaction, more support tickets, and slower response times are consistently associated with higher churn.

---

## Churn Reason Distribution

Among customers with a recorded churn reason, the distribution is:

| Churn Reason | Churned Customers | Share |
|---|---:|---:|
| Service Quality | 490 | 31.9% |
| Pricing | 436 | 28.4% |
| Product Issues | 424 | 27.6% |
| Competition | 185 | 12.1% |

Service quality has the largest share of recorded churn reasons, followed by pricing and product issues.

---

## Hypothesis Summary

| Hypothesis | Result | Assessment |
|---|---|---|
| Pricing | Supported | Contributing factor |
| Product Issues | Strongly Supported | Major driver |
| Competition | Supported | Significant driver at high exposure |
| Service Quality | Strongly Supported | Major driver |

---

## Overall Finding

The analysis indicates that the increase in churn is **not driven by a single factor**.

The strongest evidence is associated with **service quality and product issues**, while **pricing and high competitive exposure** also contribute to churn.

These findings are carried forward into the root cause analysis, where the factors are compared based on their overall customer and business impact.