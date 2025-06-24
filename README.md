# Air Pollution Analysis by Settlement Type (Python)

## Overview
This project analyzes differences in air pollution levels across various types of settlements in Israel (e.g., urban, rural, suburban). Due to non-normal data distribution, non-parametric statistical methods were applied.

## Goals
- Classify air pollution data by settlement type
- Examine pollution patterns using statistical analysis and visualization
- Evaluate group differences using non-parametric hypothesis testing
- Estimate p-values using resampling techniques

## Tools & Libraries
- Python
- Pandas
- Matplotlib, Seaborn
- Scipy, Statsmodels
- Jupyter Notebook

## Methodology
- Normality was assessed using the Shapiro-Wilk test (p < 0.05 → non-normal)
- ANOVA and t-tests were excluded
- Kruskal-Wallis test was used to evaluate group differences
- Bootstrapping with 10,000 iterations was applied for p-value estimation
- Wilcoxon rank-sum test (non-paired) served as a post-hoc method

## Results
- Air pollution levels differ significantly across settlement types
- Urban areas showed higher pollution levels than rural areas
- Bootstrapping validated the significance of the observed differences

## Files
- `air_pollution_by_settlement_type.ipynb`: Main notebook with code and analysis
