# 🧬 CRC Microbiome Machine Learning

Machine learning analysis of the **Zeller colorectal cancer microbiome dataset** to identify microbial patterns associated with colorectal cancer (CRC).

---

## 📖 Project Overview

This repository contains baseline machine learning workflows developed using the Zeller gut microbiome dataset from the **curatedMetagenomicData** Bioconductor package.

The objective is to investigate whether microbial abundance profiles can distinguish between:

- Healthy individuals
- Adenoma patients
- Colorectal Cancer (CRC) patients

These notebooks serve as the baseline models for a larger research project exploring microbiome-based colorectal cancer classification.

---

## 📊 Dataset

**Dataset:** Zeller et al. (2014)

**Source:** curatedMetagenomicData (Bioconductor)

The dataset contains relative abundances of gut microbial species together with clinical labels for Healthy, Adenoma and CRC patients.

---

## 📁 Repository Structure

### 1. Binary Logistic Regression

Healthy vs Colorectal Cancer

Files:

- 01_Binary_Logistic_Regression_Healthy_CRC.Rmd
- 01_Binary_Logistic_Regression_Healthy_CRC.html

---

### 2. Multinomial Logistic Regression

Healthy vs Adenoma vs Colorectal Cancer

Files:

- 02_Multinomial_Logistic_Regression_Healthy_Adenoma_CRC.Rmd
- 02_Multinomial_Logistic_Regression_Healthy_Adenoma_CRC.html

---

## 📈 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall (Sensitivity)
- Specificity
- Balanced Accuracy
- Confusion Matrix

---

## 🛠 Software

- R
- RStudio
- tidyverse
- caret
- nnet
- ggplot2

---

## 🚀 Future Work

This repository will be expanded with additional machine learning models, including:

- Random Forest
- Support Vector Machine (SVM)
- XGBoost
- Feature Selection
- Model Comparison
- Explainable AI (SHAP)
- Biomarker Stability Analysis

---

## 📚 Research Status

This repository documents the ongoing development of classical machine learning workflows for colorectal cancer microbiome analysis.

The work is intended to serve as the baseline for future research and model development.

---

## 👩‍💻 Author

**Harshini Chintala**

B.Sc. Biotechnology

Interested in:

- Bioinformatics
- Machine Learning
- Microbiome Research
- Quantum Computing in Life Sciences
