# Principal Component Analysis and Its Applications

This project presents a research-oriented study on the application of **Principal Component Analysis (PCA)** and machine learning for analyzing and predicting heatwave characteristics in Bangladesh using **ERA5 reanalysis
climate data**.The study investigates the atmospheric and meteorological variables associated with heatwave occurrence and develops a data-driven framework for predicting **annual Heat Wave Days (HWDS)** across the eight
administrative divisions of Bangladesh.

## Project Overview

The workflow combines:
* **ERA5 reanalysis data** for atmospheric and surface meteorological variables
* **Heatwave detection** based on temperature thresholds and percentile-based criteria
* **mRMR (Minimum Redundancy Maximum Relevance)** for selecting the most informative climate predictors
* **Principal Component Analysis (PCA)** for dimensionality reduction and identification of dominant patterns
* **Machine learning regression models** for predicting annual heatwave days
* **SHAP (SHapley Additive exPlanations)** for interpreting the contribution of important climate variables
* **Division-wise analysis** to investigate spatial differences in heatwave behavior across Bangladesh

The dataset contains atmospheric predictors from multiple pressure levels and seasonal periods. The machine learning experiments compare models trained using the original predictors, mRMR-selected predictors, and
PCA-based representations.

## Research Objective

The main objective is to identify the most influential atmospheric variables associated with heatwave variability and develop an interpretable machine learning framework for **heatwave prediction in Bangladesh**.
The project contains the complete computational workflow, including data preprocessing, feature selection, PCA analysis, model training, evaluation, visualization, and interpretation.


## Study Period

* **ERA5 data:** 1940–2025
* **Training period:** 1940–2008
* **Testing period:** 2009–2025
* **Seasonal predictors:** March–April–May (MAM)
* **Target variable:** Annual Heat Wave Days (HWDS)
* **Spatial analysis:** Eight divisions of Bangladesh

This project is intended for researchers and students interested in **PCA, climate data analysis, heatwave research, dimensionality reduction, feature selection, and machine learning applications in climate science**.
