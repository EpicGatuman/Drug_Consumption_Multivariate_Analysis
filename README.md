# Drug Consumption – Multivariate Analysis Project

This repository contains an in-depth data science project focused on analyzing and modeling patterns of drug use based on psychological and demographic variables. The dataset was obtained from the [Drug Consumption dataset](https://www.kaggle.com/datasets/gregorut/drug-consumption) on Kaggle.

The project was carried out by Matías Mora along with two teammates as part of an academic initiative to explore multivariate techniques with an emphasis on interpretability and behavioral insight.

## Dataset Overview

The dataset includes individual-level information such as:
- Personality traits (NEO-FFI: Neuroticism, Extraversion, Openness, Agreeableness, Conscientiousness)
- Impulsivity and sensation-seeking scores
- Demographics (age, gender, education level, country, ethnicity)
- Self-reported usage of 18 legal and illegal substances

Target variables are binary indicators of drug consumption (e.g., used cocaine in the past year: yes/no).

## Methodology

This project explores the data through the following steps:

### 1. Data Preprocessing
- Cleaning and encoding categorical variables
- Handling class imbalance where necessary
- Standardizing numerical features

### 2. Exploratory Data Analysis (EDA)
- Analysis of correlations between traits and drug use
- Visualization of usage distributions across demographic segments
- Feature relevance assessment

### 3. Dimensionality Reduction
- Principal Component Analysis (PCA) to explore global structure
- Multiple Correspondence Analysis (MCA) for categorical data

### 4. Clustering
- K-means and Hierarchical clustering on PCA/MCA spaces
- Profiling of user segments based on psychological traits and drug use patterns

### 5. Classification
- Predictive modeling (Logistic Regression, Random Forest, etc.)
- Evaluation using cross-validation, F1-score, and ROC AUC

## Objectives

- Identify which personality or demographic features best explain differences in drug consumption
- Understand how users can be grouped based on behavior
- Show that interpretable models can yield useful social and psychological insight

## Technologies Used

- Python 3
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- prince (for MCA)
- scipy

## Files Included

- `Drug_Consumption_Analysis.ipynb`: Jupyter Notebook with the full analysis
- `data/`: Folder for raw and processed data
- `report.pdf`: Final report with interpretations and conclusions

## License

This repository is shared for academic and educational purposes.

---

Developed by Matías Mora and two collaborators, 2025
