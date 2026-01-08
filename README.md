# A/B Test Analysis for Marketing Optimization

## Overview
This project analyzes an A/B test to determine whether a new variant improves conversion performance compared to a control version. The goal is to support data-driven decision making using statistical testing and clear business interpretation.

---

## Business Objective
Evaluate whether Variant B delivers a statistically significant improvement in conversion rate compared to Variant A and provide a clear go/no-go recommendation.

---

## Experiment Setup
- Two variants: Control (A) and Test (B)
- Metric: Conversion rate
- Equal traffic allocation between variants
- Dataset: Simulated experiment data representing a real-world marketing test

---

## Methodology

### Exploratory Analysis
- Calculated conversion rates for each variant
- Verified sample balance between A and B

### Hypothesis Testing
- **Null hypothesis (H0):** Conversion rate of Variant B equals Variant A  
- **Alternative hypothesis (H1):** Conversion rate of Variant B is different from Variant A  

### Statistical Test
- Two-sample proportion z-test
- 95% confidence level
- Confidence intervals calculated for each variant

---

## Results
- Variant B showed a higher conversion rate than Variant A
- The observed uplift was statistically significant (p-value < 0.05)

---

## Recommendation
**Ship Variant B.**  
The improvement in conversion rate is statistically significant and represents a positive business impact with low implementation risk.

---

## Business Impact
- Increased conversions without additional traffic costs
- Data-backed decision instead of intuition-based rollout
- Scalable approach applicable to landing pages, pricing tests, and messaging experiments

---

## Tools & Technologies
- Python  
- pandas, NumPy  
- scipy, statsmodels  
- matplotlib  

---

## Next Steps
- Extend analysis to revenue or average order value
- Run follow-up tests to validate long-term impact
- Segment results by user type or traffic source

---

## Author
Mikayil Badalov  
GitHub: [https://github.com/yourusername
](https://github.com/Dasirak8)
