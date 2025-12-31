# inflation_distributional_analysis
Distributional analysis of U.S. inflation using income-specific consumption baskets and CPI data.

# Who Bears the Cost of Inflation?  
## A Distributional Analysis of Consumer Price Changes in the U.S.

## Overview
Inflation is typically reported as a single national statistic, yet households differ widely in how they allocate their spending.
This project examines whether headline inflation accurately reflects the price changes experienced by different income groups.

Using publicly available data, I construct income-specific inflation indices by reweighting CPI components based on household
expenditure patterns. The goal is not to forecast inflation, but to understand its distributional impact.

---

## Motivation
Inflation plays a central role in monetary and fiscal policy decisions. However, a single aggregate inflation measure may mask
important differences in how price changes affect households at different income levels.

Understanding these differences is especially relevant for evaluating policies such as cost-of-living adjustments, targeted
subsidies, and interest rate decisions.

---

## Data
The analysis combines two primary sources:
- Consumer Price Index (CPI) inflation by expenditure category
- Consumer Expenditure Survey (CES) data on household spending shares by income group

Both datasets are produced by the U.S. Bureau of Labor Statistics and are nationally representative.

---

## Methodology
1. Group households into income brackets
2. Compute average expenditure shares by category for each group
3. Reweight CPI inflation components using group-specific consumption baskets
4. Construct income-specific inflation indices
5. Compare trends across income groups and against headline CPI

The emphasis is on transparency and interpretability rather than model complexity.

---

## Results
The analysis shows that effective inflation rates can differ meaningfully across income groups.
Households that spend a larger share of income on necessities such as housing, food, and energy
often experience higher effective inflation during certain periods.

These findings suggest that aggregate inflation measures may understate cost-of-living pressures
for specific populations.

---

## Limitations
- The analysis is descriptive and does not establish causality
- Expenditure shares are averaged within income groups
- Substitution effects are not fully captured

Results should be interpreted as illustrative rather than definitive.

---

## Future Work
- Incorporate regional price variation
- Examine substitution behavior over time
- Extend analysis to demographic subgroups

---

## Technologies
- Python (pandas, numpy)
- matplotlib / seaborn
- Jupyter notebooks
