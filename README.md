
## Dataset
The dataset is gotten from http://archive.ics.uci.edu/ml/datasets/Bank+Marketing#

The data folder contains 3 download links. I used the `bank-additional.zip` link. The zip folder contains 2 csv files, the one used for this project is `bank-additional.csv`
  
 ## How to run the code
All the work done for this project was done in the IPython notebook `bank_marketing.ipynb`. This can be run using any software you use to run .ipynb file. I used a jupyter notebook for this project.

The modules needed are:
- mglearn
- numpy
- pandas
- scikit learn

## Results:
#### Default Model

Default threshold : 0.5

precision: 0.69

recall: 0.38

accuracy: 0.91

#### Fine-tuned Model
Optimal threshold : 0.61

precision:  0.74

recall: 0.22

accuracy:  0.91


## Interpretation
My assumption for this application is that we want the marketing campaign to have as minimal negative responses as possible, this because the bank is working on a tight marketing budget. We only want to market to people whom we are relatively confident will say yes. 

The fine-tuned model is fairly useful for the task because I was able to get a precision of 0.74 which is better than 0.69 from the default random forest model gotten from our grid search.

## Reflection
I was able to compare the performance of different classifiers on this dataset and practice using pipelines which were my two goals for this project. I would however have liked to improve the performance of my gradient boosted classifier, but with my computer resources the amount of time it took to run a grid search for hyperparameter tuning did not allow me to achieve this. 
