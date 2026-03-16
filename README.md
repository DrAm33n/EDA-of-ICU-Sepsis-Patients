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

- The column names and records were translated to English
- Processed missing values
- Replaced inconsistent data
- Removed nonessential datas
- Derivation of new columns - NLR,MLR
- Convertion of datatype

## Data Explorations

- Done in the format of univariate, bivariate and multivariate
- Using groupby,filter, pivotvtables and aggregations for analysis
- Heatmap- correlations of clinical parameters
- Pie Chart - Gender and antibiotic distribution
- Bar Chart - To compare mortality rate and vitals
- Box Plots - To analyse sepsis severity

## Key Insights

- Patients with multiple comorbidities tend to have higher mortality risk and longer ICU stays.
- Elderly patients (above 60 years) show increased mortality risk due to reduced physiological resilience.
- Inflammatory biomarkers (NLR, MLR, CRP) are associated with infection severity and patient outcomes.
- Abnormal vital signs, particularly elevated respiratory rate and reduced blood pressure, indicate worsening patient condition.
- NEWS scoring system appears to be more sensitive in predicting sepsis severity compared to qSOFA and SIRS.
- Certain antibiotic-resistant organisms are associated with longer hospital stays and potential treatment challenges

## How to Use

- First download or clone this repository
- 
