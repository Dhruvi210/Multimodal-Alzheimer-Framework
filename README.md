

# Multimodal-Alzheimer-Framework

A multimodal biomarker framework integrating **CSF biomarkers, structural MRI, language-derived cognitive features, and behavioural signals** to model Alzheimer’s disease severity and evaluate **cross-cohort generalization** across the **Alzheimer’s Disease Neuroimaging Initiative (ADNI)** and **COMPASS-ND (CCNA)** datasets.

This repository provides the **experimental implementation and reproducible pipelines** corresponding to the methodology described in the associated research manuscript.

---

# Overview

Alzheimer’s disease involves complex interactions between molecular pathology, neurodegeneration, cognitive decline, and behavioural disruption. Traditional diagnostic approaches often rely on single modalities, which limits generalizability across cohorts.

This framework integrates **four complementary biomarker domains**:

* Cerebrospinal fluid (CSF) biomarkers
* Structural MRI markers of neurodegeneration
* Language-derived cognitive indicators
* Behavioural and sleep-related signals

The repository also includes **multimodal fusion models** and **cross-cohort validation experiments** to evaluate robustness across independent datasets.

---

# Repository Structure

```
Multimodal-Alzheimer-Framework
│
├── ADNI FUSION MODEL
│   Multimodal fusion model trained on ADNI cohort
│
├── CCNA FUSION MODEL
│   Multimodal fusion model trained on COMPASS-ND cohort
│
├── CROSS COHORT VALIDATION
│   Experiments evaluating generalization across ADNI → CCNA
│
├── CSF_(CCNA).ipynb
│   CSF biomarker analysis and modelling experiments
│
└── README.md
```

---

# Cross-Cohort Validation

To evaluate model robustness, experiments were conducted using:

* **Training dataset:** ADNI
* **External validation dataset:** COMPASS-ND (CCNA)

The cross-cohort validation pipeline evaluates whether multimodal models trained on ADNI maintain predictive stability when applied to independent cohorts.

---

# Reproducibility

All experiments required to reproduce the results reported in the manuscript are provided in this repository.

The workflow includes:

1. Data preprocessing
2. Feature extraction
3. Model training
4. Multimodal fusion
5. Cross-cohort evaluation

Each experiment script or notebook contains the full modelling pipeline used to generate the reported results.

---

# Datasets

The experiments utilize publicly available datasets:

* **ADNI (Alzheimer’s Disease Neuroimaging Initiative)**
  [https://adni.loni.usc.edu](https://adni.loni.usc.edu)

* **COMPASS-ND / CCNA (Canadian Consortium on Neurodegeneration in Aging)**
  [https://ccna-ccnv.ca](https://ccna-ccnv.ca)

Due to data access restrictions, raw datasets are **not distributed in this repository**.

---

# Citation

If you use this repository or build upon this framework, please cite the associated research work.




