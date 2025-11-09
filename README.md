# Classification---SVM-PCR-Random-Forest---PIVUS-dataset

# PIVUS Metabolomics Classification Analysis

This repository contains the analysis and data files for a comparative study of machine learning algorithms applied to the **MTBLS90 human serum metabolomics dataset** from the PIVUS study.

[cite_start]The primary goal was to create prediction models for classifying samples based on sex and identify the most significant metabolites[cite: 4, 7].

---

## Repository Contents

| File Name | Description |
| :--- | :--- |
| **`PIVUS.ipynb`** | The complete **Jupyter Notebook** containing all Python code for data loading, preprocessing, hyperparameter optimization, model training, and result evaluation. |
| **`PIVUS_report_.pdf`** | [cite_start]The **full analysis report** detailing the project goal [cite: 7][cite_start], data preprocessing steps, in-depth explanation of the methods used [cite: 7][cite_start], and discussion of the results and biological significance[cite: 7]. |
| **`MTBLS90.xlsx`** | [cite_start]The raw metabolomics data file (collected from Metabolights) used for the analysis[cite: 9, 11]. [cite_start]It consists of two sheets: a "Data Sheet" with 189 metabolite concentrations and a "Peak Sheet" with metabolite metadata[cite: 13, 14]. |

---

## Methods and Results

[cite_start]The analysis involved training and testing multiple machine learning algorithms on preprocessed metabolomics data[cite: 24].

The methods used include:
* [cite_start]**Support Vector Machine (SVM)** [cite: 33]
* [cite_start]**Random Forest** [cite: 41]
* [cite_start]**Principal Component Regression (PCR)** [cite: 37]
* Others (including PCLR and SVM RBF).

> [cite_start]**A detailed description of the methods, the data pre-processing steps** (log transformation, Z-scale, kNN imputation) [cite: 19, 20][cite_start], **the hyperparameter optimization process** (5-fold cross-validation) [cite: 23][cite_start], **and the results can be found in the `PIVUS_report_.pdf`**[cite: 7, 48].
