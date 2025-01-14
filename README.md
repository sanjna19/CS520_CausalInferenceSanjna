# CS520_CausalInference
Causal Study of Physical Health’s Role in Heart Diseases
Project Overview
This project explores the causal relationship between physical activity and heart disease, focusing on both population-level and individualized treatment effects. By leveraging causal inference methodologies such as Directed Acyclic Graphs (DAGs), propensity score matching (PSM), and machine learning frameworks, this study provides robust insights into the impact of physical activity on heart disease prevention.

Motivation
Heart disease is one of the leading causes of death worldwide, posing significant health and economic challenges. While physical activity is widely recognized as a protective factor, its causal impact remains underexplored. This study aims to bridge this gap by identifying key confounders, estimating causal effects, and offering actionable recommendations for public health policies.

Key Features
Directed Acyclic Graphs (DAGs): Used to identify confounders and establish causal relationships.
Average Treatment Effect (ATE): Measures the overall impact of physical activity on heart disease risk.
Heterogeneous Treatment Effects (HTE): Explores individual variations in treatment effects across subgroups.
SHAP Analysis: Provides interpretability for key predictors driving treatment effects.
Methodology
Data Preparation and Cleaning:

Dataset from Kaggle.
Preprocessing steps included handling missing values, outlier detection, and feature encoding.
Causal Inference Approaches:

DAG Construction: Identified confounders such as BMI, Smoking, and Physical Health.
Back-Door Adjustment: Applied to block confounding paths using regression models.
Propensity Score Matching (PSM): Balanced treated and control groups for unbiased estimates.
Inverse Probability of Treatment Weighting (IPTW): Created a pseudo-population to control for confounders.
S-Learner Framework: Integrated with Random Forests for estimating HTE.
Model Evaluation:

Validation through Estimated Root Mean Squared Error (ERMSE) for model robustness.
SHAP analysis for feature interpretability.
Key Results
Physical activity reduces the risk of heart disease by approximately 3.5% (ATE).
Subgroup analysis highlights significant variations in treatment effects, with factors like smoking and BMI influencing outcomes.
SHAP analysis identifies Physical Health, BMI, and Smoking as the most critical predictors.
Technologies Used
Python libraries: DoWhy, NetworkX, Scikit-learn, SHAP
Dataset visualization: Matplotlib, Seaborn
Machine learning: Random Forests, Logistic Regression
Statistical methods: Bootstrap confidence intervals, Propensity Score Matching
