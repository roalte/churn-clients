# churn-clients
 
### DATA:

* Check data (transactions.parquet)
* Items description (materials.csv)
* Stores description (plants.csv)
* Clients description (clients.csv)

### GOALS: 
1) Analyze the data and determine the optimal methodology for churn customers detection
2) Develop a model of customer churn according to chosen methodology 
3) Describe developed model, answer the questions: which features most affect at the customers churn

### NOTEBOOKS:
1) [1_preprocessing](https://github.com/roalte/churn-clients/blob/main/1_preprocessing.ipynb) - initial data preprocessing (formats and size optimization)\
2) [2_eda](https://github.com/roalte/churn-clients/blob/main/2_eda.ipynb) - EDA and decisions
3) [3_target](https://github.com/roalte/churn-clients/blob/main/3_target.ipynb) - description of selected methodology, creation of the target variable\
4) [4_featuring](https://github.com/roalte/churn-clients/blob/main/4_featuring.ipynb) - features engineering
5) [5_model](https://github.com/roalte/churn-clients/blob/main/5_model.ipynb) - best model selection, predictions, analyze, feature importance
