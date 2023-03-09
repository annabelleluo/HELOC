# HELOC Interpretable Machine Learning

## Project Description

This is the HKU STAT3612 project, 2020. This notebook performs interpretable machine learning (IML) with application to a real data case
study in the banking industry. For an IML model, both “prediction accuracy” and “model explainability”
are equally important.

The data includes about 10,400 anonymized Home Equity Line of Credit (HELOC) loans (acquired from FICO),
together with 23 raw features. You may obtain the dataset, together with the data
description file at [here](https://github.com/ajzhanghk/Stat3612/blob/master/HelocDataDict2.xlsx). Note that in the second Excel file the monotonicity constraints are included
in the data dictionary, which are based on the prior knowledge about the input-output relationships.

This notebook performs two sets of machine learning models, one without the monotonicity
constraints and the other one with the monotonicity constraints.

## Project Contents
### Data Preprocessing
- Load Data Set
- Data Visualisation
### Feature Engineering
- Missing value processing
- Correlation checking
- Train/test split
- Categorical binning and encoding
### Model without Monotonicity Constraints
- Gradient boosting
- ExNN
- DNN Model
### Model with Monotonicity Constriants
- XG Boost
### LIME and SHAP 
- Lime and shap values for interpretable models
### Discussion
- Benchmarks
- Logistics Regression
- Generalised Additive Model


