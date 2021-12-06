### Overview of the project:

This project aims to build a classification tool for banks and credit card companies to help them predict whether a costumer will churn or not based on his/her demographical information as well as the record of how they have used the credit card. 

The dataset that is used in this project contains a total of 10127 data with 21 valid columns.

EDA is first performed on the dataset, then the the data is splitted into a 20% holdout test set and a 80% of training and validation set.

Under 10 different random states, the whole machine learning pipeline including 4-fold cross validation and exhaustive grid search on hyperparameter choices are performed and accuracy scores are calculated with 7 different supervised learning algorithms along with a baseline dummy classifier.

After obtaining the best model, global feature importance and lobal feature importance are conducted and interpreted.

In the end, there is a outlook section for this project.


### Environments that are required for running this project:
```
name: data1030
channels:
  - conda-forge
  - defaults
dependencies:
  - python=3.9
  - matplotlib=3.4.2
  - pandas=1.3.1
  - scikit-learn=0.24.2
  - numpy=1.21.1
  - py-xgboost=1.3.3
  - shap=0.39.0
  - jupyter_client
  - jupyter_core
  - jupyterlab
  - jupyterlab_server
  - jupytext
  - rise
prefix: /opt/conda
```