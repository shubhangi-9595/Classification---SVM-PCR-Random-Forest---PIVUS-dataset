# PIVUS Metabolomics Classification Analysis

This repository contains the analysis and data files for a comparative study of machine learning algorithms applied to the **MTBLS90 human serum metabolomics dataset** from the PIVUS study.

The primary goal was to create prediction models for classifying samples based on sex and identify the most significant metabolites.

---

## Repository Contents

| File Name | Description |
| :--- | :--- |
| **`PIVUS.ipynb`** | The complete **Jupyter Notebook** containing all Python code for data loading, preprocessing, hyperparameter optimization, model training, and result evaluation. |
| **`PIVUS_report_.pdf`** | The **full analysis report** detailing the project goal, data preprocessing steps, in-depth explanation of the methods used, and discussion of the results and biological significance. |
| **`MTBLS90.xlsx`** | The raw metabolomics data file (collected from Metabolights) used for the analysis. It consists of two sheets: a "Data Sheet" with 189 metabolite concentrations and a "Peak Sheet" with metabolite metadata. |

---

## Methods and Results

The analysis involved training and testing multiple machine learning algorithms on preprocessed metabolomics data.

The methods used include:
* **Support Vector Machine (SVM)**
* **Random Forest**
* **Principal Component Regression (PCR)**
* Others (including PCLR and SVM RBF).

A detailed description of the methods, the data pre-processing steps** (log transformation, Z-scale, kNN imputation), **the hyperparameter optimization process** (5-fold cross-validation), **and the results can be found in the `PIVUS_report_.pdf`**.
