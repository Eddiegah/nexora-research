# Early Detection of Cardiovascular Disease Using Machine Learning
## A Sex-Stratified Fairness-Aware Study for Low-Resource Clinical Settings in Sub-Saharan Africa

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20373324.svg)](https://doi.org/10.5281/zenodo.20373324)

**Author:** Edmund Eric Gah  
**Affiliations:** Nexora · St. Peter's Senior High School, Ghana  
**Published:** May 2026 · Zenodo Preprint  
**License:** [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

📄 **[Download Full Paper (PDF)](https://zenodo.org/records/20373324/files/Nexora_CVD_Paper_FINAL%20(1).pdf)**

---

## Abstract

Cardiovascular disease (CVD) is the leading cause of mortality worldwide and the fastest-growing non-communicable disease burden across sub-Saharan Africa, where late clinical diagnosis continues to drive preventable deaths. This study presents a fairness-aware comparative evaluation of eight machine learning algorithms for the early prediction of CVD, using a combined primary dataset of 1,100 patient records validated against established clinical feature distributions from the cardiovascular disease literature.

---

## Models Evaluated

| # | Model | Notes |
|---|---|---|
| 1 | Logistic Regression | Baseline |
| 2 | Decision Tree | |
| 3 | Random Forest | Best accuracy & recall |
| 4 | Support Vector Machine | Best AUC-ROC & CV accuracy |
| 5 | K-Nearest Neighbors | |
| 6 | XGBoost | |
| 7 | LightGBM | |
| 8 | Multi-Layer Perceptron | |

---

## Key Results

| Model | Metric | Score |
|---|---|---|
| **SVM** | AUC-ROC | **0.9270** |
| **SVM** | Cross-validated Accuracy | **87.68%** |
| **Random Forest** | Accuracy | **86.36%** |
| **Random Forest** | Recall | **0.8515** |

---

## Preprocessing Pipeline

- Median imputation for missing values
- SMOTE oversampling for class imbalance
- Standard Scaler normalization

---

## Explainability (SHAP)

Top 5 predictive features identified by SHAP analysis:
1. **Thalassemia status**
2. **ST depression**
3. **Maximum heart rate**
4. **Exercise-induced angina**
5. **Number of major vessels**

---

## Fairness Analysis

Three-dimensional stratification across **sex**, **age group**, and **cholesterol level**.

| Group | Recall |
|---|---|
| Male patients | 85.92% |
| Female patients | 80.00% |

This gap empirically confirms the well-documented clinical phenomenon of **female CVD underdiagnosis**, raising critical concerns for equitable AI deployment in diverse clinical populations.

---

## Dataset

- Combined primary dataset of **1,100 patient records**
- Validated against established clinical feature distributions from the CVD literature

---

## Related Work

This paper extends the scientific program initiated in:
> Gah, E. E. (2026). *Early Detection of Type 2 Diabetes Using Machine Learning.* [DOI: 10.5281/zenodo.20348652](https://doi.org/10.5281/zenodo.20348652)

---

## Citation

```bibtex
@misc{gah2026cvd,
  author    = {Gah, Edmund Eric},
  title     = {Early Detection of Cardiovascular Disease Using Machine Learning: A Sex-Stratified Fairness-Aware Study for Low-Resource Clinical Settings in Sub-Saharan Africa},
  year      = {2026},
  publisher = {Zenodo},
  doi       = {10.5281/zenodo.20373324},
  url       = {https://doi.org/10.5281/zenodo.20373324}
}
```

---

*This paper is part of the [Nexora Research](https://github.com/Eddiegah/nexora-research) program.*
