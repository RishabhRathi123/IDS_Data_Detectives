# Indian Liver Patient Dataset Analysis - Data Detectives

## Overview  
This project leverages **Machine Learning (ML)** techniques to analyze the **Indian Liver Patient Dataset (ILPD)**, focusing on the accurate classification of liver disease and understanding critical health determinants. By employing models like **Logistic Regression** and **Random Forest Classifier**, we extract actionable insights into liver health patterns within the Indian population.

## Table of Contents  
1. [Introduction](#introduction)  
2. [Dataset Description](#dataset-description)  
3. [Data Preprocessing](#data-preprocessing)  
4. [Exploratory Data Analysis](#exploratory-data-analysis)  
5. [Classification Models](#classification-models)  
6. [Findings and Insights](#findings-and-insights)  
7. [Conclusion](#conclusion)  
8. [References](#references)  

---

## Introduction  
Liver diseases present a significant global health challenge, particularly in diverse and densely populated regions like India. This project explores liver health patterns by analyzing the ILPD through ML techniques to:  
- Classify liver diseases effectively.  
- Identify influential features.  
- Gain demographic and clinical insights.

---

## Dataset Description  
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/225/ilpd+indian+liver+patient+dataset)  
- **Attributes:** 11 features including Age, Gender, Bilirubin levels, and protein ratios.  
- **Instances:** 583 patients (with liver disease diagnosis labels).  
- **Characteristics:** Numerical and categorical data.  

---

## Data Preprocessing  
Key steps include:  
- Handling missing values in the `Albumin-Globulin Ratio` by imputing the mean.  
- Encoding categorical variables (e.g., Gender).  
- Standardizing attributes to ensure consistency in scale using **Z-Score Standardization**.  
- Splitting the dataset into training (80%) and testing (20%) sets.

---

## Exploratory Data Analysis  
- Gender-specific and age-specific patterns in liver disease prevalence.  
- Correlation analysis of liver fluid concentrations.  
- Visualizations using **Seaborn** and **Matplotlib** to uncover trends and outliers.  

---

## Classification Models  
### Logistic Regression  
- Utilized for its simplicity and interpretability in binary classification tasks.  
- **Accuracy:** 73.50%  

### Random Forest Classifier  
- Selected for its robustness and ability to handle complex data relationships.  
- Achieved better generalization with **Feature Importance Analysis** highlighting key predictors.  
- **Accuracy:** 63%  

---

## Findings and Insights  
1. Liver disease prevalence is higher in **males (75.82%)** than females (24.18%).  
2. Middle-aged individuals (30–65 years) exhibit higher susceptibility.  
3. Key predictors include **Direct Bilirubin**, **Total Bilirubin**, and **Albumin Levels**.  
4. Random Forest Classifier offers deeper insights into feature contributions but requires further optimization.  

---

## Conclusion  
This project demonstrates the potential of machine learning to enhance liver disease diagnostics. Insights derived from this study aim to support early diagnosis and personalized healthcare strategies, particularly in the Indian context. Future work includes testing on real-world data and refining models for improved accuracy.

---

## References  
1. [Indian Liver Patient Dataset (UCI Repository)](https://archive.ics.uci.edu/dataset/225/ilpd+indian+liver+patient+dataset)  
2. Descriptive and Inferential Statistics - Dr. Manoj Kumar Yadav  
3. Classification Models - Dr. Aloke Dutta  
4. [Seaborn Documentation](https://seaborn.pydata.org/)  
5. [Matplotlib Tutorials](https://matplotlib.org/3.1.1/tutorials/index.html)  

---
