# Heart Failure Survival Analysis

## Introduction
This project aims to identify variables that are significantly associated with heart failure survival rates. We utilize statistical tests to explore this association and derive insights that could potentially inform medical interventions.

## Objective
To uncover and analyze the factors that contribute to the survival of heart failure patients.

## Methodology
We apply a variety of statistical tests such as the Chi-Squared Test, Wilcoxon Rank Test, and T-Test to ascertain the relationship between different variables and heart failure survival outcomes.

## Dataset Overview
- Source: Kaggle
- The dataset includes 13 features collected from 299 patients.
- Out of these patients, 203 survived, and 96 passed away.
- Feature types: 7 numerical, 6 binary.
- The primary outcome of interest is the 'death event' indicating patient mortality.

## Key Findings
- **Smoking Status**: No significant association between smoking status and heart failure survival was detected using the Chi-Squared Test.
- **Serum Creatinine**: A Wilcoxon Rank Test suggested a significant difference in median Serum Creatinine levels between patients with varying heart failure survival outcomes.
- **Anemia**: No statistically significant association between anemia status and heart failure survival was found based on the Chi-Squared Test.
- **Creatinine Phosphokinase**: The Mann-Whitney U Test revealed no significant difference in median Creatinine Phosphokinase levels between heart failure and non-heart failure patients.

## Conclusions and Future Work
The initial analysis indicates that Serum Creatinine levels are significantly associated with heart failure survival. Future research may include the application of binary classifiers, such as Logistic Regression and KNN, to predict heart failure survival.
