# CPSC 330 – Machine Learning Workflows

University of British Columbia

---

## Overview

This assignment focuses on building and evaluating machine learning workflows using structured pipelines in Python. The goal is to apply preprocessing, model training, evaluation, and interpretation techniques within a reproducible and modular framework.

The notebook demonstrates the use of scikit-learn pipelines and model evaluation tools consistent with the CPSC 330 workflow emphasis.

---

## Objectives

* Construct preprocessing pipelines using `ColumnTransformer`
* Train and evaluate multiple machine learning models
* Perform cross-validation for model comparison
* Apply appropriate evaluation metrics
* Interpret model behavior using feature importance and SHAP values
* Maintain reproducibility within a structured workflow

---

## Tools and Environment

### Programming Environment

* Python 3
* Jupyter Notebook

### Libraries Used

* `numpy` – numerical computation
* `pandas` – data manipulation and preprocessing
* `matplotlib` – visualization
* `seaborn` – statistical visualization
* `scikit-learn` – preprocessing, pipelines, model training, cross-validation, and evaluation
* `shap` – model interpretability
* `otter` – assignment autograding

Standard library modules such as `os`, `sys`, and `warnings` were also used.

---

## Machine Learning Workflow

The assignment follows a structured workflow:

1. Data loading and preprocessing
2. Feature transformation using pipelines
3. Model training and comparison
4. Cross-validation and performance evaluation
5. Model interpretation

Models explored include linear models and tree-based methods implemented through `scikit-learn`.

---

## Reproducibility

To install the required packages:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn shap
```

The assignment was developed and executed within a standard Python environment compatible with course requirements.

---

## Repository Structure

```
hw5/
  hw5.ipynb
  README.md
  data/
  img/
```

---
