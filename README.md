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
Type	Model	Balanced accurancy score
Ensemble	Balanced Random Forest Classifier	0.49979537
Ensemble	Easy Ensemble AdaBoost Classifier	0.931660071
Resampling	Naive Random Oversampling	0.649992706
Resampling	SMOTE Oversampling	0.657746089
Resampling	Undersampling	0.657746089
Combination (Over and Under) Sampling	SMOTEENN	0.540713075
####

Presents a cohesive written
analysis that:
✓ Describes the precision and
recall scores.
✓ Describes the balanced
accuracy score.
✓ Includes a final
recommendation on the model to
use, if any.
✓ Provides justification for your
recommendation.


### Analysis
    Based on the balanced accurancy, EasyEnsembleClassifier model has highest accuracy of 93%. 