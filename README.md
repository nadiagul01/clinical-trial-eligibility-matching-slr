# Systematic Literature Review: Clinical Trial Eligibility Matching Using AI

> **CS Department, NUCES (FAST-NUCES Islamabad)**  
> **Author:** Nadia Gul 

---

## 📌 Abstract

Clinical trial eligibility matching is critical for advancing medical research and ensuring patients receive appropriate treatments. Traditional methods are manual, error-prone, and inefficient. This systematic literature review examines how **Artificial Intelligence (AI)** — including **Natural Language Processing (NLP)**, **Machine Learning (ML)**, and **rule-based systems** — is transforming eligibility determination by processing eligibility criteria, extracting features, and resolving semantic inconsistencies in Electronic Health Records (EHRs).

---

## 🎯 Research Objectives

- Identify AI techniques and methodologies used for clinical trial eligibility matching
- Evaluate the accuracy and efficiency of these techniques
- Examine publicly available datasets and their key characteristics
- Identify challenges and propose future research directions

---

## 🔍 Methodology

| Aspect | Details |
|---|---|
| **Time Period Covered** | 2015 – 2024 (focus on 2021–2024) |
| **Databases Searched** | IEEE Xplore, PubMed, SpringerLink, Scopus, Elsevier |
| **Search Strategy** | Boolean queries combining "AI", "NLP", "ML", "clinical trial eligibility", "patient recruitment automation" |
| **Inclusion Criteria** | English, full-text, 2021–2024, reports precision/recall/F1-score |
| **Exclusion Criteria** | Non-English, unrelated domains, no full text available |

---

## 🗂️ Datasets Reviewed

| Dataset | Size & Scope |
|---|---|
| **N2C2 (2018)** | 576 patient records, 13 cohort selection criteria |
| **MIMIC-III** | 844 patient records (80/20 train/test split) |
| **ClinicalTrials.gov (COVID-19)** | 2,998 trials, 27,352 eligibility criteria |

---

## 🤖 AI Methodologies Surveyed

- **NLP Models:** BERT, RoBERTa, XLNet, ERNIE, ELECTRA, BioBERT, BioSentVec, GPT-4
- **ML Models:** Decision Trees, Random Forest, Gradient Boosted Trees, SVM, Ridge Regression
- **Deep Learning:** Att-BiLSTM + CRF, Ensemble Models with Metric Learning
- **Hybrid Systems:** Rule-based + NLP, C2Q 2.0 (NLP + human-in-the-loop)
- **Explainable AI (XAI):** SciSpacy, DeepPhe

---

## 📊 Key Performance Results

### N2C2 / MIMIC-III — Cohort Selection F1-Scores

| Model | N2C2 | MIMIC-III |
|---|---|---|
| NCBI-BERT | 0.9070 | 0.8353 |
| With selection criteria as questions | 0.8561 | 0.8083 |
| Without question framing | 0.6946 | 0.4619 |

### COVID-19 Entity Recognition — Att-BiLSTM vs Ontology-Based

| Model | Precision | Recall | F1 |
|---|---|---|---|
| Att-BiLSTM | 0.942 | 0.810 | 0.871 |
| Ontology-based (MeSH) | 0.715 | 0.659 | 0.686 |

---

## ⚠️ Key Challenges Identified

- **Limited dataset diversity** — most datasets focus on critical care or single disease (e.g., COVID-19)
- **Model interpretability** — many AI models function as "black boxes"
- **Data privacy & security** — HIPAA/GDPR compliance concerns with EHR datasets
- **Bias in AI models** — risk of demographic bias (age, gender, ethnicity)
- **Multimodal integration gaps** — genomic and imaging data not yet well-integrated

---

## 🔮 Future Research Directions

1. **Explainable AI (XAI)** for transparent eligibility decisions
2. **Cross-dataset validation** for generalizability
3. **Multimodal data integration** (structured + unstructured records)
4. **Enhanced temporal reasoning** for longitudinal patient data
5. **Standardized ontology mapping** (e.g., SNOMED-CT) across datasets


