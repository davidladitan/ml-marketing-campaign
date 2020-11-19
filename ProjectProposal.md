# Project proposal for *Predicting Positive Responders to Marketing Campaign*
Author: David O. Laditan

## 1. Why: Question/Topic being investigated 2pts

I would like to compare the performance of different classifiers and practice working with pipelines. 

## 2. How: Plan of attack 2pts
I will be using the work flow used in lab3 as a template. In addition to the steps in the template, I will use pipelines to do preprocessing and grid searching. The grid search will be used to compare classifiers and also for parameter tuning. If time permits I would do a PCA on the best estimator to see how well the classifier performs with fewer features.  

## 3. What: Dataset, models, framework, components 2pts
Dataset: http://archive.ics.uci.edu/ml/datasets/Bank+Marketing#

Scikit-learn classifiers: LogisticRegression, RandomForest, GradientBoosting, SVC
