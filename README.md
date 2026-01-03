# Machine Learning – CS584

This repository contains selected coursework and implementations from **CS584: Machine Learning**
at Illinois Institute of Technology.

The focus is on **from-scratch implementations** of core machine learning algorithms,
along with empirical evaluation using cross-validation and comparisons against sklearn baselines.

## Topics Covered
- Linear & Logistic Regression
- Discriminative Learning (Perceptron, LDA)
- Generative Learning (GDA, Naive Bayes – Bernoulli & Multinomial)
- Support Vector Machines
- Ensemble Methods (Bagging, Boosting)

## Highlights
- Implemented **GDA (shared covariance)** and **Naive Bayes** from scratch
- Used **stratified cross-validation**, confusion matrices, and PR curves
- Compared custom models against **sklearn baselines**
- Focus on numerical stability and proper evaluation

## Structure
- `01-regression/` – Regression models and evaluation
- `02-discriminative-learning/` – Discriminative classifiers
- `03-generative-learning/` – Generative models (GDA, NB)
- `04-svm-ensembles/` – SVMs and ensemble classifiers
- `utils/` – Shared utilities (metrics, plotting)

## Notes
Datasets are fetched programmatically (e.g., UCI ML Repository).
No large datasets are stored in this repository.
