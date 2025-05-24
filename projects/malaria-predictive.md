---
layout: single
title: "Predicting Malaria Prevalence with Environmental Data"
permalink: /projects/malaria-predictive/
---

In collaboration with **Arup** and **Médecins Sans Frontières (MSF)**, this project developed an AI-based tool to predict malaria prevalence using satellite-derived environmental variables. Accurate forecasting helps optimize resource allocation for prevention and treatment in vulnerable regions.

By applying conventional machine learning models, we explored how environmental patterns—such as rainfall, vegetation, and land temperature—can act as early-warning signals for monthly malaria outbreaks.

## Project Highlights

- 🌍 **Global Health Meets AI**: Supports humanitarian operations through data-driven malaria forecasting.
- 🤖 **Conventional ML Models**: Includes Random Forest, Gradient Boosting, and Linear Regression for prediction tasks.
- 🔧 **Brute-Force Feature Engineering**: Engineered and tested hundreds of environmental variable combinations to find those most predictive.
- 📉 **Performance Evaluation**: Compared model outputs against observed monthly malaria case averages using statistical error metrics.

## Tech Stack

- **Data Sources**: Satellite imagery (NDVI, rainfall, temperature), MSF case data
- **Models**: Random Forest, XGBoost, Linear Regression
- **Feature Engineering**: Lag features, temporal aggregations, composite indices
- **Evaluation**: RMSE, standard deviation, correlation with monthly case averages

## Key Insights

- Certain engineered environmental indicators—created via brute-force combinations—showed **strong correlation** with malaria prevalence.
- ML models outperformed naive baselines, especially in capturing seasonal dynamics.
- The tool demonstrated potential for **scalable, non-invasive forecasting** to guide public health interventions.

> 📄 **More about the implementation**: [Predicting Malaria Prevalence with Environmental Data](https://www.linkedin.com/posts/msf-sweden-innovation-unit_climatecrisis-climatechange-activity-6994204445551038464-pf4M?utm_source=share&utm_medium=member_ios)