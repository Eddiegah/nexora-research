# Early Detection of Type 2 Diabetes Using Machine Learning
## A Fairness-Aware Study for Underserved Populations

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20348652.svg)](https://doi.org/10.5281/zenodo.20348652)

**Author:** Edmund Eric Gah  
**Affiliation:** St. Peter's Senior High School, Ghana  
**Published:** May 2026 · Zenodo Preprint  
**License:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

📄 **[Download Full Paper (PDF)](https://zenodo.org/records/20348652/files/Nexora_Diabetes_Paper_FINAL.pdf)**

---

## Abstract

Type 2 diabetes mellitus represents one of the most urgent public health challenges in sub-Saharan Africa, where late diagnosis continues to drive preventable complications. This study presents a fairness-aware comparative evaluation of seven machine learning algorithms for early prediction of Type 2 diabetes, using the Pima Indians Diabetes Database and validated against the CDC Behavioral Risk Factor Surveillance System (BRFSS) dataset.

---

## Models Evaluated

| # | Model | Notes |
|---|---|---|
| 1 | Logistic Regression | Baseline |
| 2 | Decision Tree | |
| 3 | Random Forest | Best AUC-ROC |
| 4 | Support Vector Machine | |
| 5 | K-Nearest Neighbors | |
| 6 | XGBoost | Best accuracy |
| 7 | Multi-Layer Perceptron | |

---

## Key Results

| Model | Metric | Score |
|---|---|---|
| **Random Forest** | AUC-ROC | **0.8226** |
| **XGBoost** | Cross-validated Accuracy | **81.12%** |

---

## Preprocessing Pipeline

- Median imputation for missing values
- SMOTE oversampling for class imbalance
- Feature normalization (Standard Scaler)

---

## Explainability (SHAP)

Top predictive features identified by SHAP analysis:
1. **Glucose concentration** — dominant predictor
2. **BMI** — dominant predictor

---

## Fairness Analysis

Stratified across **age** and **BMI** subgroups. Significant performance disparities found across subgroups — raising critical implications for equitable AI deployment in low-resource clinical settings.

---

## Datasets

| Dataset | Role |
|---|---|
| Pima Indians Diabetes Database | Primary training/evaluation |
| CDC BRFSS | External validation |

---

## Citation

```bibtex
@misc{gah2026diabetes,
  author    = {Gah, Edmund Eric},
  title     = {Early Detection of Type 2 Diabetes Using Machine Learning: A Fairness-Aware Study for Underserved Populations},
  year      = {2026},
  publisher = {Zenodo},
  doi       = {10.5281/zenodo.20348652},
  url       = {https://doi.org/10.5281/zenodo.20348652}
}
```

---

*This paper is part of the [Nexora Research](https://github.com/Eddiegah/nexora-research) program.*
