# Exploratory Data Analysis of Sepsis in ICU Patients

## Project Overview

Sepsis is a life-threatening condition caused by the body's extreme response to infection. Early identification and effective clinical management are crucial for improving patient outcomes.

This project performs an Exploratory Data Analysis (EDA) on ICU sepsis patient data to identify patterns related to mortality, length of stay, comorbidities, inflammatory biomarkers, vital signs, and severity scores.

The goal is to understand the clinical factors influencing sepsis outcomes and derive insights that may support better clinical decision-making and patient management.

## Objectives

- Analyze the relationship between comorbidities and patient outcomes.
- Evaluate mortality trends among ICU sepsis patients.
- Examine the impact of multiple comorbidities on ICU length of stay.
- Study inflammatory biomarkers (NLR, MLR, CRP) and their association with disease severity.
- Analyze vital signs and severity scoring systems (NEWS, qSOFA, SIRS).
- Explore culture reports and antibiotic resistance patterns

## Dataset

The dataset contains clinical and laboratory data of ICU patients diagnosed with sepsis, including:

- Patient demographics
- Comorbidities
- Vital signs
- Blood parameters and inflammatory biomarkers
- Microbiological culture results
- Antibiotic usage
- Severity scoring systems (NEWS, qSOFA, SIRS)
- ICU length of stay
- Mortality outcome

## Tools and Technologies

The analysis was performed using the following tools:

- Python
- Pandas – Data manipulation and analysis
- NumPy – Numerical operations
- Matplotlib – Data visualization
- Seaborn – Statistical visualization
- Plotly – Interactive visualizations

## Data Preprocessing

- Translated column names and records into English
- Processed missing values
- Replaced inconsistent data entries
- Removed non-essential data
- Derived new clinical indicators such as NLR (Neutrophil-to-Lymphocyte Ratio) and MLR (Monocyte-to-Lymphocyte Ratio)
- Converted variables to appropriate data types
  
## Data Explorations

- The exploratory analysis was conducted using univariate, bivariate, and multivariate analysis techniques.

Key analytical methods included:

- GroupBy, filtering, pivot tables, and aggregations
- Heatmaps – Correlation analysis of clinical parameters
- Pie charts – Distribution of gender and antibiotic usage
- Bar charts – Comparison of mortality rates and vital signs
 -Box plots – Analysis of sepsis severity and biomarker distribution

## Key Insights

- Patients with multiple comorbidities tend to have higher mortality risk and longer ICU stays.
- Elderly patients (above 60 years) show increased mortality risk due to reduced physiological resilience.
- Inflammatory biomarkers (NLR, MLR, CRP) are associated with infection severity and patient outcomes.
- Abnormal vital signs, particularly elevated respiratory rate and reduced blood pressure, indicate worsening patient condition.
- NEWS scoring system appears to be more sensitive in predicting sepsis severity compared to qSOFA and SIRS.
- Certain antibiotic-resistant organisms are associated with longer hospital stays and potential treatment challenges

## Files Included

- ICU_Sepsis_Dataset.xlsx – Raw dataset

- EDA_Sepsis_ICU_Patients.ipynb – Jupyter Notebook containing data analysis and visualizations

## How to Use

- Download or clone this repository
- Open ICU_Sepsis_Dataset.xlsx to explore the raw dataset
- Open EDA_Sepsis_ICU_Patients.ipynb in Jupyter Notebook to view the complete data analysis and visualizations
