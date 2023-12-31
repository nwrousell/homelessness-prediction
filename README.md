# Predicting Community Rates of Homelessness Using Historical Data
Homelessness is a major problem in the United States, with over [582,000 homeless individuals](https://endhomelessness.org/homelessness-in-america/homelessness-statistics/state-of-homelessness/) counted in January of 2022. Furthermore, homelessness has increased by 6% since 2017. For these reasons it is important to know which communities are going to suffer from the highest rates in the coming years. I develop a model that can predict rates of homelessness at the community level using historical data. The dataset used was compiled by the team of the study [Market Predictors of Homelessness](https://www.huduser.gov/portal/sites/default/files/pdf/Market-Predictors-of-Homelessness.pdf) and can be found on the [HUD website](https://www.huduser.gov/portal/datasets/hpmd.html). 

The project is built in Python 3.11.4 and repository organization is as follows:

1. `data/` - Stores raw and processed data files, as well as the Data Dictionary  
2. `figures/` - Stores visualizations; from EDA to model result comparisons  
3. `results/` - Trained models and comparison results  
4. `report/` - Report on development pipeline, methodology, and model results.  
5. `src/` - Contains all of the code. EDA can be found in `EDA.ipynb`; Autoregression, splitting, preprocessing, and model development can be found in `model_development.ipynb`; Evaluation and interpretation of model results is in `model_evaluation.ipynb`  
  
The key packages used in this project are the following*:
  
- matplotlib 3.7.2  
- numpy 1.24.4  
- pandas 2.0.3  
- pickle 4.0  
- scikit-learn 1.3.0  
- scipy 1.11.2  
- seaborn 0.12.2  
- shap 0.42.1  
- xgboost 1.7.6  
- geopandas 0.14.1  
  
*Check file environment.yml for complete configuration and package dependencies