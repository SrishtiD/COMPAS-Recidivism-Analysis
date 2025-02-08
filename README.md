# COMPAS-Recidivism-Analysis
Master's Project (Data Science) - Analysis of COMPAS algorithm fairness using R with focus on racial bias detection in recidivism predictions

# COMPAS Algorithm Fairness Analysis

## Project Overview
Analysis of racial bias in recidivism predictions using R ([View Full Analysis](docs/analysis.html))

## Key Findings
- **42.3%** False Positive Rate for African-Americans vs **22.0%** for Caucasians
- **65.8%** Overall Accuracy ([Confusion Matrix](scripts/analysis.R))

## Reproduction Steps
1. Install dependencies:
install.packages(c("tidyverse", "dplyr", "margins"))

2. Run analysis:
Rscript scripts/analysis.R


## Ethical Considerations
[View Bias Mitigation Recommendations](docs/ethical_impact.md)

## Judicial System Impact
This analysis demonstrates how algorithmic bias can:
- Lead to 92% higher false accusations for minorities
- Reduce trust in automated sentencing tools

