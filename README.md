<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Nexora%20Research&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Machine%20Learning%20for%20Health%20Equity%20in%20Sub-Saharan%20Africa&descAlignY=58&descSize=16&descColor=a8d8ea" width="100%"/>

<br/>

[![Author](https://img.shields.io/badge/Author-Edmund%20Eric%20Gah-0a9396?style=for-the-badge&logo=person&logoColor=white)](https://github.com/Eddiegah)
[![Institution](https://img.shields.io/badge/Nexora-Ghana%20🇬🇭-ee9b00?style=for-the-badge)](https://github.com/Eddiegah/nexora-research)
[![License](https://img.shields.io/badge/License-CC%20BY%204.0-94d2bd?style=for-the-badge)](https://creativecommons.org/licenses/by/4.0/)
[![Papers](https://img.shields.io/badge/Published%20Papers-2-e9d8a6?style=for-the-badge)](#-published-papers)

</div>

---

<br/>

> *Late diagnosis is not an inevitability — it is a systems failure.*
> *This research program exists to fix it.*

<br/>

I am **Edmund Eric Gah**, an AI researcher from Ghana building **fairness-aware machine learning systems** for early disease detection in underserved communities. My work addresses a critical gap: clinical AI tools that perform well on Western populations but fail the very communities that need them most.

Every paper in this repository is built toward one mission:

**→ Make preventive healthcare intelligence equitable, interpretable, and deployable across sub-Saharan Africa.**

<br/>

---

## 🔬 Research Focus

<table>
<tr>
<td width="50%">

**Algorithmic Fairness**
Auditing ML performance disparities across sex, age, BMI, and cholesterol subgroups — before deployment, not after.

</td>
<td width="50%">

**Explainable AI**
SHAP-based feature attribution to make predictions clinically interpretable — not black boxes.

</td>
</tr>
<tr>
<td width="50%">

**Preventive Detection**
Shifting the intervention point from crisis to early warning for diabetes, CVD, and beyond.

</td>
<td width="50%">

**Low-Resource Deployment**
Designing for the constraints of real clinical settings in emerging economies — not idealized labs.

</td>
</tr>
</table>

<br/>

---

## 📑 Published Papers

<br/>

### `02` &nbsp; Cardiovascular Disease Prediction

**Early Detection of Cardiovascular Disease Using Machine Learning:**
*A Sex-Stratified Fairness-Aware Study for Low-Resource Clinical Settings in Sub-Saharan Africa*

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20373324.svg)](https://doi.org/10.5281/zenodo.20373324)
&nbsp;`May 2026` &nbsp;`8 Models` &nbsp;`1,100 Patient Records`

| Best Model | Metric | Score |
|:---|:---|:---|
| SVM | AUC-ROC | **0.9270** |
| SVM | Cross-validated Accuracy | **87.68%** |
| Random Forest | Accuracy | **86.36%** |

**🔍 Key finding:** Female patients had a recall of **80.0%** vs **85.92%** for male patients — empirically confirming female CVD underdiagnosis in clinical AI. SHAP identified thalassemia status, ST depression, and maximum heart rate as dominant predictors.

📂 [View paper folder](./papers/02-cvd-prediction/) &nbsp;·&nbsp; 📄 [Download PDF](https://zenodo.org/records/20373324/files/Nexora_CVD_Paper_FINAL%20(1).pdf)

<br/>

---

### `01` &nbsp; Type 2 Diabetes Prediction

**Early Detection of Type 2 Diabetes Using Machine Learning:**
*A Fairness-Aware Study for Underserved Populations*

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20348652.svg)](https://doi.org/10.5281/zenodo.20348652)
&nbsp;`May 2026` &nbsp;`7 Models` &nbsp;`Pima + CDC BRFSS Datasets`

| Best Model | Metric | Score |
|:---|:---|:---|
| Random Forest | AUC-ROC | **0.8226** |
| XGBoost | Cross-validated Accuracy | **81.12%** |

**🔍 Key finding:** SHAP analysis identified glucose concentration and BMI as dominant predictors. Fairness analysis across age and BMI subgroups revealed significant performance disparities with direct implications for equitable AI in low-resource clinical settings.

📂 [View paper folder](./papers/01-diabetes-prediction/) &nbsp;·&nbsp; 📄 [Download PDF](https://zenodo.org/records/20348652/files/Nexora_Diabetes_Paper_FINAL.pdf)

<br/>

---

## 🛠️ Stack

```
Python  ·  scikit-learn  ·  XGBoost  ·  LightGBM  ·  SHAP
SMOTE (imbalanced-learn)  ·  Pandas  ·  NumPy  ·  Matplotlib  ·  Seaborn
```

<br/>

---

## 🏥 About Nexora

**Nexora** is an AI-driven preventive health intelligence platform being developed for underserved communities across Ghana and West Africa. This research repository is its scientific foundation — every paper advances the evidence base for clinically actionable, fair, and interpretable tools for real-world deployment.

<br/>

---

<div align="center">

*All research is published open access under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)*
*— free to read, share, and build upon with attribution.*

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%"/>

</div>
