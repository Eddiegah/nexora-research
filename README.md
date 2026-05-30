# Nexora Research

**Fairness-aware machine learning for preventive healthcare in sub-Saharan Africa**

*by [Edmund Eric Gah](https://github.com/Eddiegah) · Nexora · St. Peter's Senior High School, Ghana 🇬🇭*

---

This repository is the public home of my research program. Each paper has its own folder containing a summary, key results, and a link to the full peer-reviewed preprint on Zenodo.

All work is built toward one mission: **making clinical AI equitable, interpretable, and deployable in low-resource health settings across Ghana and West Africa.**

---

## 📂 Papers

### [01 · Early Detection of Type 2 Diabetes](./papers/01-diabetes-prediction/)
> *Fairness-Aware ML Study for Underserved Populations*

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20348652.svg)](https://doi.org/10.5281/zenodo.20348652)
`May 2026` · `7 Models` · `Pima + CDC BRFSS Datasets` · `Random Forest AUC-ROC: 0.8226`

---

### [02 · Early Detection of Cardiovascular Disease](./papers/02-cvd-prediction/)
> *Sex-Stratified Fairness-Aware Study for Low-Resource Clinical Settings*

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20373324.svg)](https://doi.org/10.5281/zenodo.20373324)
`May 2026` · `8 Models` · `1,100 Patient Records` · `SVM AUC-ROC: 0.9270`

---

## 🔬 Research Themes

| Theme | Description |
|---|---|
| **Algorithmic Fairness** | Auditing ML performance across sex, age, BMI, and cholesterol subgroups |
| **Explainable AI** | SHAP-based feature attribution for clinical interpretability |
| **Preventive Healthcare** | Early detection to reduce diagnostic delays in sub-Saharan Africa |
| **Equity in Clinical AI** | Building systems that work for the populations most underserved by existing tools |

---

## 🛠️ Common Stack

```
Python · scikit-learn · XGBoost · LightGBM · SHAP · SMOTE (imbalanced-learn)
Pandas · NumPy · Matplotlib · Seaborn
```

---

## 📖 How to Navigate This Repo

```
nexora-research/
│
├── papers/
│   ├── 01-diabetes-prediction/
│   │   └── README.md       ← summary, results, Zenodo link
│   ├── 02-cvd-prediction/
│   │   └── README.md
│   └── ...                 ← future papers go here
│
└── README.md               ← you are here
```

Each paper folder contains a standalone `README.md` with the abstract, key results table, fairness findings, and a link to the full PDF on Zenodo. When code is available, it will also be included in that folder.

---

## ➕ Adding a New Paper

When a new paper is published:
1. Create a new folder: `papers/NN-short-title/`
2. Add a `README.md` using the template in any existing paper folder
3. Update the Papers table in this root README
4. Update the table in the [profile README](https://github.com/Eddiegah/Eddiegah)

---

## 📜 License

All research content is published open access under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
You are free to share and adapt with attribution.

---

*Built with purpose. For the communities that need it most.*
