JPMorgan Quantitative Research Simulation – Forage

This repository showcases my completed tasks from the JPMorgan Chase & Co. Quantitative Research Virtual Experience Program on Forage (https://www.theforage.com/simulations/jpmorgan/quantitative-research-11oc).

Overview
The simulation involved real-world credit risk modeling using borrower-level loan data, including:

- Estimating probability of default (PD) using classification models
- Calculating expected financial loss using PD, EAD, and LGD
- Implementing dynamic programming to optimally bucket FICO scores
- Building a feature set to feed into predictive models

Task 1 & 2 – Credit Risk Modeling
- Trained a logistic regression model to predict defaults.
- Evaluated performance using ROC curve and AUC score.
- Compared different classifiers and chose the most accurate one.

Task 3 – Expected Loss Estimation
- Computed expected loss using the formula:  
  Expected Loss = PD × LGD × EAD
- Integrated model outputs with business KPIs.

Task 4 - Explored multiple techniques to convert continuous FICO scores into categorical ratings
- Equal-frequency binning using KBinsDiscretizer
- Supervised tree-based binning via DecisionTreeClassifier
- PD-based sorting of buckets to assign risk-aligned credit ratings
  
Skills Demonstrated
- Python (NumPy, Pandas, Scikit-Learn, Matplotlib)
- Logistic Regression, ROC-AUC, Expected Loss modeling
- Dynamic Programming
- Credit Risk & Probability of Default Estimation
