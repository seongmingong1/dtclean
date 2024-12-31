# Breast Cancer Data Analysis

## Overview
This project focuses on the analysis of clinical data related to breast cancer cases. The primary objective was to extract meaningful insights from the data through Exploratory Data Analysis (EDA), as the dataset lacked a specific target column suitable for supervised machine learning.
Data
The analysis utilized four datasets containing:

Patient demographic information
Tumor classification details

## Process
1. Data Preparation

Merged multiple datasets using unique patient identifiers
Cleaned the data by:

Removing unnecessary columns
Anonymizing sensitive information
Converting date fields to ages
Handling missing values
Transforming data types



2. Exploratory Data Analysis (EDA)

Conducted univariate analysis using histograms for:

Age-related variables
Pregnancy-related variables
Ki67 index


Performed correlation analysis using heatmaps and dendrograms
Visualized binary variables using pie charts
Executed bivariate analysis with count plots

## Tools and Libraries

Pandas: Data manipulation and cleaning
NumPy: Numerical operations
Matplotlib & Seaborn: Data visualization

## Key Findings

Age at diagnosis showed a notable increase between 45 and 65 years
Over 75% of Ki67 values were below 30%
Approximately 60% of patients had no pregnancy experience
Strong positive correlation between age at recurrence and age at death
Negative correlation observed between Ki67 and age at death
Less than 25% of patients received neoadjuvant chemotherapy
Tumor grades: ~50% grade 2, ~33% grade 1
Receptor status: ~80% estrogen receptor-positive, ~70% progesterone receptor-positive, ~20% HER2 overexpression
Most common tumor classifications: T1, followed by T2; N0 and N1 most frequent; M0 predominant

## Conclusion
This analysis revealed significant patterns and correlations within the breast cancer dataset, providing a foundation for further research and potential clinical applications.
