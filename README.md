# final_project_datascience

Steelproof Project - Temperature Prediction in Steel Manufacturing Process

Please open files in sequence: 

1 - Intro

2 - Solution

3 - Report


### Problem Context:
Development of a predictive model to optimize energy consumption in steel production at Steelproof steel plant, through accurate prediction of final metal temperature during processing in a 100-ton ladle metallurgy furnace.

### Objective:
Create a regression model capable of predicting the final steel temperature, enabling optimized adjustments in the production process to reduce energy costs and improve operational sustainability.

Technical Competencies Used:
Exploratory Data Analysis (EDA):
- Investigation of 7 distinct datasets (electrodes, bulk materials, gas, temperature, wires)
- Analysis of missing values and temporal patterns
- Treatment of categorical data and data type conversion (datetime)

Data Preprocessing:
- Aggregation of multiple data sources by batch (key)
- Feature engineering with statistical metrics (sum, mean, maximum, minimum)
- Creation of temporal variables (process duration)
- Target variable treatment (last valid temperature per batch)

Machine Learning:
- Modeling with advanced algorithms (LightGBM, CatBoost)
- Feature importance analysis to identify most impactful variables
- Evaluation with regression metrics (R², MAE, MSE, RMSE)
- Hyperparameter optimization

### Main Libraries:
- pandas/numpy: Data manipulation and analysis
- scikit-learn: Evaluation metrics and preprocessing
- LightGBM/CatBoost: Machine learning algorithms for regression
- matplotlib: Data and results visualization

### Final Result:
High-performance models (R² > 0.95) capable of accurately predicting final steel temperature, identifying the most critical process variables (energy consumed, active power, previous temperatures) and providing valuable insights for energy optimization and operational cost reduction in steel production.
