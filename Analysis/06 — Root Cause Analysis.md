# 06 — Root Cause Analysis

## Objective

The hypothesis analysis identified several factors associated with customer churn. This section brings those findings together to determine the main reasons behind the increase in churn.

The analysis considers both the **strength of the relationship with churn** and the number of customers affected.

---

## 1. Service Quality

Service quality emerged as one of the strongest churn-related factors.

Churned customers show:

- Lower average satisfaction: **6.36 vs 6.81**
- More support tickets: **2.25 vs 1.91**
- Longer response time: **14.89 vs 13.30 hours**

The relationship becomes more visible as response time increases.

| Response Time | Churn Rate |
|---|---:|
| < 8 hours | 8.9% |
| 8–16 hours | 12.2% |
| 16–24 hours | 15.1% |
| 24+ hours | 22.5% |

Customers experiencing slower support are therefore substantially more likely to churn.

**Finding:** Service quality is a major contributor to churn.

---

## 2. Product Issues

Product issues show a strong relationship with churn.

| Product Issues | Churn Rate |
|---|---:|
| 0 | 9.0% |
| 1 | 12.3% |
| 2 | 15.8% |
| 3 | 21.1% |
| 4+ | Highest risk |

Churn rises consistently as the number of product issues increases.

The average number of product issues is also higher among churned customers:

- Retained: **0.96**
- Churned: **1.35**

**Finding:** Repeated product issues are a major churn driver and represent an important area for corrective action.

---

## 3. Pricing

Pricing also shows a relationship with churn.

Customers with higher monthly charges generally have higher churn than lower-charge customers.

| Charge Group | Churn Rate |
|---|---:|
| Lowest | 10.8% |
| Lower-Middle | 12.2% |
| Upper-Middle | 14.6% |
| Highest | 13.5% |

Churned customers have a slightly higher average monthly charge:

- Retained: **₹697.24**
- Churned: **₹714.35**

The relationship is positive but weaker than the patterns observed for service quality and product issues.

**Finding:** Pricing contributes to churn, but does not appear to be the sole explanation for the increase.

---

## 4. Competition

Competitive exposure shows a clear difference at the high-exposure level.

| Competitor Exposure | Churn Rate |
|---|---:|
| Low | 11.6% |
| Medium | 11.8% |
| High | 19.4% |

Customers with high competitor exposure have considerably higher churn than customers with low or medium exposure.

**Finding:** Competition is an important contributing factor, particularly for customers facing high competitive pressure.

---

## 5. Churn Reason Distribution

The recorded churn reasons provide additional evidence about why customers left.

| Churn Reason | Customers | Share |
|---|---:|---:|
| Service Quality | 490 | 31.9% |
| Pricing | 436 | 28.4% |
| Product Issues | 424 | 27.6% |
| Competition | 185 | 12.1% |

Service quality represents the largest recorded churn reason, followed by pricing and product issues.

---

## Root Cause Conclusion

The evidence indicates that the increase in churn is **multi-factor driven** rather than the result of a single issue.

The strongest recurring patterns are associated with:

1. **Service quality**
2. **Product issues**
3. **Pricing**
4. **Competitive pressure**

Service quality and product issues show the strongest behavioral relationship with churn, while pricing and competition add further pressure for specific customer groups.

The next step is to rank these factors based on their **overall customer and revenue impact**, rather than ranking them only by churn rate.