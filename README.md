# Poverty Prediction Model

---

## Introduction

The Poverty Probability Index (PPI) offers a systematic approach to understanding poverty levels. By utilizing the PPI, we can estimate the chance that a specific household resides below the poverty line. This determination stems from ten country-centric questions focused on a household's attributes and asset ownership. Poverty denotes a situation where individuals are unable to afford fundamental daily needs, including food, clothing, and shelter. This predicament is notably rampant in underdeveloped countries.

## Dataset Description

The dataset leveraged in this project has its origins in a competition hosted by Microsoft. The primary goal was to ascertain the likelihood of an individual subsisting on less than $2.5 a day across seven nations.

This data has been extracted from the Financial Inclusion Insights household surveys, a meticulous effort by InterMedia to shed light on the real-world scenario.
![image](https://user-images.githubusercontent.com/91441204/207525295-f4f4ab9e-3bb5-4fb9-a258-8e5c645d107f.png)

## Technical Overview

To provide a comprehensive and detailed analysis, a variety of Python libraries were employed, each serving a distinct purpose:

- **Data Handling and Manipulation**: `pandas`, `numpy`
- **Visualization**: `seaborn`, `matplotlib`
- **Machine Learning**: 
  - **Pre-processing**: `preprocessing`, `Ro bustScaler`, `StandardScaler`
  - **Model Selection and Validation**: `sklearn.model_selection`
  - **Regression Models**: `linear_model`, `ElasticNet`, `Lasso`, `Ridge`, `BayesianRidge`, `LassoLarsIC`, `RandomForestRegressor`, `GradientBoostingRegressor`, `KernelRidge`
  - **Classification Models**: `RandomForestClassifier`, `KNeighborsClassifier`, `DecisionTreeClassifier`
  - **Metrics**: `sklm`, `classification_report`, `confusion_matrix`, `accuracy_score`
  - **Feature Selection and Engineering**: `feature_selection`, `skde`, `SelectKBest`, `chi2`, `featurewiz`
- **Deep Learning**: `tensorflow`
- **Exploratory Data Analysis**: `dataprep.eda`
- **Utilities**: `%matplotlib inline`

By leveraging these libraries, the project aims to offer an intricate and precise poverty prediction model, ensuring that the predictions are both accurate and actionable.
