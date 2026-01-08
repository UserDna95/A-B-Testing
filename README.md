# A/B Testing

## Overview
This project evaluates the performance of a marketing test campaign using a formal control vs test experimental design. The analysis focuses on measuring lift across funnel metrics, assessing statistical reliability, and providing evidence-based support for informed decision-making.

## Objectives
Did the campaign differences produce a real, meaningful improvement, enough to justify rolling it out?
- Determine whether the test campaign improves conversion outcomes
- Assess cost efficiency impacts
- Quantify uncertainty and effect size
- Present results in an executive-ready dashboard

## Tools & Workflow
| Data cleaning & feature engineering -> Excel Power Query |
| Aggregation & modeling -> Excel |
| Statistical testing & confidence intervals -> Python |
| Visualization & dashboard -> Excel |


## Metrics Analyzed
- Click-through rate (CTR)
- Purchase rate per click
- Purchase rate per impression
- Cost per purchase

## Statistical Methodology
Due to moderate right-skewness and small sample sizes, both parametric and nonparametric methods were applied:
- Welch’s t-test for robust mean comparison
- Mann-Whitney U test for distributional validation
- Cohen’s d for practical significance
- 95% confidence intervals for decision reliability

## Key Results
- CTR increased by ~101% (p < 0.001, large effect)
- Purchase rate per impression increased by ~68% (p < 0.01)
- No statistically reliable change in post-click conversion or cost per purchase

## Conclusion
The test campaign significantly improved engagement and end-to-end conversion without statistically reliable cost increases. Results support rollout with monitoring of downstream efficiency metrics.

### 📌 Dataset

Source: A/B Testing DataSet -> https://www.kaggle.com/datasets/amirmotefaker/ab-testing-dataset
