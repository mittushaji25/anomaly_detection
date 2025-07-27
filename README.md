# Anomaly Detection in Healthcare Provider Data using Isolation Forest

## Project Overview  
This project demonstrates a robust anomaly detection pipeline using **Isolation Forest**, applied to a large Medicare provider dataset. The goal is to identify unusual patterns in billing behavior, service intensity, and financial metrics—potential indicators of fraud, coding errors, or atypical provider practices.

## Problem Statement  
How can unsupervised machine learning techniques be used to automatically flag suspicious claims and outlier providers in real-world healthcare data?

## Techniques Used

| Module | Purpose |
|--------|--------|
| EDA | Understanding distributions, outliers, and feature relationships |
| Data Cleaning | Handling missing values, type conversions, and scaling |
| Isolation Forest | Unsupervised anomaly detection |
| Visualization | Box plots, scatter plots, and heatmaps for pattern interpretation |

## Exploratory Data Analysis
Performed extensive EDA to uncover insights:
- Skewed distributions in financial metrics  
- Correlation between submitted charges and payments  
- Anomalies clustered away from high-density normal groups  
- Breakdown of anomalies by provider demographics and HCPCS codes

## Key Visuals
- Box plots comparing anomalous vs. normal provider metrics  
- Scatter plots of feature pairs revealing billing irregularities  
- Heatmaps showing strong inter-feature relationships  
