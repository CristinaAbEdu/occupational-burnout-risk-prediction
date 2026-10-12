# occupational-burnout-risk-prediction

# Early Prediction of Occupational Burnout Risk Using Interpretable Machine Learning Models

**BSc IT (Data Science) Honours Research Project | 2026**

**Institution:** Eduvos  
**Researcher:** Cristina Abrahamse

## 1. Project Overview

This repository contains the Python code and Jupyter notebooks developed for my Honours research project, *Early Prediction of Occupational Burnout Risk Using Interpretable Machine Learning Models*.

The study investigates how interpretable machine-learning models can be used to identify elevated occupational burnout-related risk and highlight factors associated with these classifications.

The research focuses on both predictive performance and model interpretability, with the aim of supporting a more transparent and evidence-informed understanding of workplace burnout risk.

## 2. Research Objectives

The primary objectives of this research are to:

- Develop and evaluate interpretable machine-learning models for identifying elevated burnout-related risk.
- Compare the predictive performance of Logistic Regression and Decision Tree classifiers.
- Identify influential predictors associated with elevated-risk classifications.
- Examine how model explanations may support the interpretation of workplace burnout-related factors.
- Consider the limitations of applying these models to different secondary datasets.

## 3. Datasets

Five datasets were analysed, covering different occupational populations, working conditions and burnout-related measures.

| Dataset | Focus |
|---|---|
| Oldenburg Burnout Inventory (OLBI) | Burnout-related risk and demographic or employment characteristics |
| Burnout, Emotional Symptoms and Work Engagement | Burnout, psychological symptoms and work engagement among psychologists and workers |
| Brazilian Teacher Pandemic Burnout | Burnout-related experiences and working conditions among teachers during the COVID-19 pandemic |
| Workplace Incivility and Emotional Exhaustion | Workplace incivility and elevated emotional-exhaustion risk |
| Synthetic Work-from-Home Burnout | Simulated work-from-home behaviour and burnout-risk classifications |

The first four datasets provide empirical analyses. The synthetic dataset is included as a supplementary demonstration of the modelling approach and is not treated as evidence of real-world predictive accuracy.

## 4. Methodology

The research follows a quantitative approach using secondary datasets.

The modelling workflow includes:

1. Dataset inspection and exploratory data analysis.
2. Data cleaning, preprocessing and variable mapping.
3. Burnout-related outcome definition and risk classification.
4. Model training and evaluation.
5. Interpretation of predictor contributions and model findings.

Where appropriate, a Harmonised Burnout Score (HBS) was used to express burnout-related outcomes on a common numerical scale. Dataset-specific outcome definitions and classification thresholds are documented in the relevant notebooks.

### Machine-Learning Models

- Logistic Regression
- Decision Tree

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion matrices

### Model Interpretability

Interpretation was conducted using Logistic Regression coefficients, odds ratios, statistical significance where applicable, and Decision Tree feature importance.

## 5. Repository Structure

**01_PRIMARY/**

Contains the primary dataset assessment, preprocessing, analysis and modelling notebooks for the four empirical datasets.

**04_SYNTHETIC_TESTING/**

Contains the supplementary synthetic Work-from-Home dataset analysis and modelling.

**00_Modelling_Framework.ipynb**

Contains the modelling framework used to support the research workflow.

**README.md**

Provides an overview of the research and repository contents.

## 6. Reproducibility and Code Access

The Jupyter notebooks document the analytical procedures, Python code, visualisations, model evaluations and interpretation outputs used in the study.

To review the research, navigate to the relevant folder and open the corresponding `.ipynb` notebook.

The notebooks can be viewed directly on GitHub without installing Python. Reproducing the analyses requires a compatible Python environment, the necessary packages and access to the original datasets.

Dataset access details and software requirements should be checked against the individual notebooks before attempting reproduction.

## 7. Research Limitations

The study uses secondary datasets with different populations, variables and burnout-related outcome measures. As a result, the findings are not directly comparable across all datasets.

The empirical datasets are cross-sectional, meaning the models identify existing elevated-risk classifications rather than demonstrating prospective prediction of future burnout.

The models are intended for research and exploratory risk assessment, not clinical diagnosis or independent employee-level decision-making.

## 8. Academic Purpose

This repository was developed as part of a BSc IT (Data Science) Honours research project at Eduvos in 2026.

It is provided for academic review, transparency and reproducibility of the research methodology and results.
