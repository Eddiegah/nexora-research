<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Nexora%20Research&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Machine%20Learning%20for%20Health%20Equity%20in%20Sub-Saharan%20Africa&descAlignY=58&descSize=16&descColor=a8d8ea" width="100%"/>

<br/>

[![Author](https://img.shields.io/badge/Author-Edmund%20Eric%20Gah-0a9396?style=for-the-badge&logoColor=white)](https://github.com/Eddiegah)
[![Institution](https://img.shields.io/badge/Nexora-Ghana%20🇬🇭-ee9b00?style=for-the-badge)](https://github.com/Eddiegah/nexora-research)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0003--9772--2471-a8dadc?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0003-9772-2471)
[![License](https://img.shields.io/badge/License-CC%20BY%204.0-94d2bd?style=for-the-badge)](https://creativecommons.org/licenses/by/4.0/)
[![Papers](https://img.shields.io/badge/Published%20Papers-3-e9d8a6?style=for-the-badge)](#-published-papers)

</div>

---

<br/>

> *"Only 8 of 47 clinical AI studies reviewed included any fairness evaluation.*
> *Only 12 were conducted on African patient data.*
> *This research program exists to change that."*

<br/>

I am **Edmund Eric Gah**, an AI researcher from Ghana building **fairness-aware machine learning systems** for early disease detection in underserved communities across sub-Saharan Africa.

Clinical AI has a blind spot. Tools that perform well on Western populations routinely fail the communities that need them most — and almost no one is measuring it. My work addresses this gap head-on: auditing algorithmic bias, building interpretable models, and publishing evidence that makes equitable deployment impossible to ignore.

**This is the Nexora AI for African Health Research Program.** Three papers in. Many more to come.

<br/>

---

## 🔬 Research Pillars

<table>
<tr>
<td width="50%">

**⚖️ Algorithmic Fairness**
Auditing ML performance disparities across sex, age, BMI, and cholesterol subgroups — before deployment, not after harm.

</td>
<td width="50%">

**🔍 Explainable AI**
SHAP-based feature attribution that makes model predictions clinically interpretable — not black boxes that clinicians cannot trust.

</td>
</tr>
<tr>
<td width="50%">

**🫀 Preventive Detection**
Shifting the intervention point from crisis care to early warning for diabetes, CVD, and beyond.

</td>
<td width="50%">

**🌍 Low-Resource Deployment**
Designing for the real constraints of clinical settings in emerging economies — not idealized Western labs.

</td>
</tr>
</table>

<br/>

---

## 📑 Published Papers

<br/>

### `03` &nbsp; Systematic Review · Algorithmic Fairness in Clinical ML

**Algorithmic Fairness in Clinical Machine Learning for Non-Communicable Disease Prediction in Sub-Saharan Africa:**
*A Systematic Review, Empirical Analysis, and Research Agenda*

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20417981.svg)](https://doi.org/10.5281/zenodo.20417981)
&nbsp;`May 2026` &nbsp;`PRISMA Protocol` &nbsp;`47 Studies Reviewed (2015–2026)`

| Finding | Statistic |
|:---|:---|
| Studies with any fairness evaluation | **8 / 47 — only 17.0%** |
| Studies using formal fairness metrics | **3 / 47 — only 6.4%** |
| Studies conducted on African patient data | **12 / 47 — only 25.5%** |

**🔍 Key contribution:** The **first systematic review** of algorithmic fairness in clinical ML for NCD prediction oriented toward sub-Saharan Africa. Enriched with original empirical evidence from Papers 01 and 02, forming the first multi-disease fairness dataset for NCD prediction in West Africa. Proposes a **five-pillar research agenda** addressing the data representation crisis, fairness measurement gap, explainability requirement, deployment infrastructure barrier, and sex/demographic bias emergency.

📂 [View paper folder](./papers/03-systematic-review/) &nbsp;·&nbsp; 📄 [Download PDF](https://zenodo.org/records/20417981/files/Nexora_Review_Paper3_FINAL%20(1).pdf)

<br/>

---

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

**🔍 Key finding:** Sex-stratified fairness analysis revealed female recall at **80.0%** vs **85.92%** for males — empirically confirming female CVD underdiagnosis in clinical AI. SHAP identified thalassemia status, ST depression, and maximum heart rate as dominant predictors.

📂 [View paper folder](./papers/02-cvd-prediction/) &nbsp;·&nbsp; 📄 [Download PDF](https://zenodo.org/records/20373324/files/Nexora_CVD_Paper_FINAL%20(1).pdf)

<br/>

---

### `01` &nbsp; Type 2 Diabetes Prediction

**Early Detection of Type 2 Diabetes Using Machine Learning:**
*A Fairness-Aware Study for Underserved Populations*

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20348652.svg)](https://doi.org/10.5281/zenodo.20348652)
&nbsp;`May 2026` &nbsp;`7 Models` &nbsp;`Pima Indians + CDC BRFSS Datasets`

| Best Model | Metric | Score |
|:---|:---|:---|
| Random Forest | AUC-ROC | **0.8226** |
| XGBoost | Cross-validated Accuracy | **81.12%** |

**🔍 Key finding:** SHAP identified glucose concentration and BMI as dominant predictors. Fairness analysis across age and BMI subgroups revealed significant performance disparities — with direct implications for equitable AI in low-resource clinical settings.

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

**Nexora** is an AI-driven preventive health intelligence platform being developed for underserved communities across Ghana and West Africa. This repository is its scientific backbone — every paper published here advances the evidence base for clinically actionable, fair, and interpretable ML tools for real-world deployment in emerging economies.

<br/>

---

<div align="center">

*All research is published open access under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)*
*— free to read, share, and build upon with attribution.*

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%"/>

</div>
