# Challenge17_Machine_Learning_Credit_Risk

## Objectives
In this module, we're using Python to build and evaluate several machine learning models to predict credit risk. 

## Technoligies
* Python

## Resources
- Dataset: LoanStats_2019Q1.csv
- Notebook: credit_risk_ensemble.ipynb and credit_risk_resampling.ipynb

## Results

### Balanced accurancy
Balance Accuracy
|Type|Model|Balanced accurancy score|
|---|--|--|
|Ensemble|Balanced Random Forest Classifier|0.49979537|
|Ensemble|Easy Ensemble AdaBoost Classifier|0.931660071|
|Resampling|Naive Random Oversampling|0.649992706|
|Resampling|SMOTE Oversampling|0.657746089|
|Resampling|Random Undersampling|0.657746089|
|Combination (Over and Under) Sampling|SMOTEENN|0.540713075|

### Precision, Recall and F1 scores
|Classification|Precision|Recall|F1|
|---|--|--|--|
|*Balanced Random Forest Classifier*|
|high_risk|0.00|0.00|0.00|    
|low_risk|0.99|1.00|1.00| 
|*Easy Ensemble AdaBoost Classifier*|
|high_risk|0.09|0.92|0.16|    
|low_risk|1.00|0.94|0.97|
|*Naive Random Oversampling*|
|high_risk|0.01|0.71|0.02|  
|low_risk|1.00|0.59|0.74|
|*SMOTE Oversampling*|
|high_risk|0.01|0.63|0.02|
|low_risk|1.00|0.68|0.81|
|*Random Undersampling*|
|high_risk|0.01|0.53|0.01|
|low_risk|0.99|0.55|0.71|
|*SMOTEENN*|
|high_risk|0.01|0.73|0.02|
|low_risk|1.00|0.59|0.74|


### Analysis
Based on our dataset, all models have high precision for low risk credit and low precision score for high risk credit. Based on the balanced accurancy, EasyEnsembleClassifier model has highest accuracy of 93%. Thus, EasyEnsembleClassifier model could be the best model for credit risk analysis. 

### Recommendation
* Additional model to be used, for example Decision Tree, Gradient Boosting or Deep Neural Networks. 
* Filtered out some "fake" or biased information from the dataset. 