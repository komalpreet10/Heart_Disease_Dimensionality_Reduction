# Heart_Disease_Dimensionality_Reduction
This repository applies PCA, MCA, MDA, and stepwise regression to the Cleveland Heart Disease dataset. It aims to identify key predictors, analyze patterns in clinical and categorical data, and classify individuals as having heart disease or not. The dataset includes 303 records with 13 attributes related to heart disease diagnosis.

# Dimensionality Reduction Techniques for Improved Diagnosis of Heart Disease

## Group Members
- Shwetha
- Teshani
- Komalpreet
- Rachel

## Objective
The goal of this study is to explore the Heart Disease Dataset and answer the following questions:

1. **How many principal components are required to explain most of the variance in the dataset?**
2. **What are the underlying latent factors associated with the variables in the dataset?**
3. **How can categorical data in the study be represented and analyzed to identify patterns using Multiple Correspondence Analysis (MCA)?**
4. **How effective is Multivariate Discriminant Analysis (MDA) in classifying patients into heart disease and non-heart disease categories based on multiple clinical and demographic variables?**
5. **Which independent variables are the most significant predictors of heart disease, and how can stepwise regression techniques be applied to optimize the predictive model?**

## Population of Interest and Dataset Size
The study population consists of 303 individuals with heart disease-related symptoms who have undergone diagnostic testing. Specifically, the population is made up of all patients from the Cleveland Database with information related to heart disease, including clinical and diagnostic data. The dataset contains 13 medical attributes from these patients, such as age, sex, and results from various diagnostic tests, along with one target variable.

### Source of Dataset
The dataset is from the UCI Machine Learning Repository:
[Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease)

## Variables Used in the Project

### Quantitative Variables

| Variable Name           | Description                                                     | Unit  |
|-------------------------|-----------------------------------------------------------------|-------|
| **Age**                 | The patient’s age                                               | years |
| **Resting Blood Pressure** | Patient's level of blood pressure at resting mode               | mm/HG |
| **Cholesterol (chol)**  | The serum cholesterol level                                     | mg/dl |
| **Maximum Heart Rate**  | Measures the highest heart rate reached during physical exertion |       |
| **Oldpeak**             | Exercise-induced ST-depression relative to the state of rest    |       |

### Qualitative Variables

| Variable Name             | Description                                                    |
|---------------------------|----------------------------------------------------------------|
| **Chest Pain Type (cp)**   | Type of chest pain experienced by patient                      |
| **Resting Electrocardiographic Results (restecg)** | Measures heart function during rest |
| **Exercise-Induced Angina (exang)** | Measures whether physical exertion induces chest pain |
| **Major Vessels (ca)**    | Counts the number of major vessels (0–3)                       |
| **Thalassemia (thal)**    | A blood disorder measured                                      |
| **Target**                | Classify individuals as having heart disease or not            |

## Methodology
### 1. Principal Component Analysis (PCA)
- PCA will be performed to determine how many principal components are required to explain most of the variance in the dataset.

### 2. Multiple Correspondence Analysis (MCA)
- MCA will be used to represent categorical data and identify patterns across the variables in the dataset.

### 3. Multivariate Discriminant Analysis (MDA)
- MDA will be applied to classify patients into heart disease and non-heart disease categories.

### 4. Stepwise Regression
- Stepwise regression will be used to identify the most significant predictors of heart disease.

### Conclusion
By utilizing dimensionality reduction techniques like PCA and MCA, along with classification methods like MDA and regression analysis, this project aims to build a model that can effectively diagnose heart disease based on clinical and demographic variables.

