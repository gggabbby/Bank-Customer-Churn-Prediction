# Bank Customer Churn Prediction 
This project uses logistic regression, k-nearest neighbors, and random forest models to predict user churn in the banking industry. Among them, the hyperparameter tuning are performed by using grid-search.

## 1. Data Source

The data set of the project comes from the kaggle website. The data set contains 14 features and 10,000 rows of data. 

- Use the link below to visit the data source:

  [Predicting Churn for Bank Customers](https://www.kaggle.com/adammaus/predicting-churn-for-bank-customers)


## 2. Data Exploration

- boxplot of numerical features

<img src="images/numerical-boxplot.png" width=700>

- countplot of categorical features

<img src="images/countplot-categorical.png" width=650>

- correlations between features

<img src="images/feature-correlation.png" width=450>

* Use link below to check more details of data explaration:
  [Data Exploration](churn-predict.ipynb)

## 3. Model Training and Result Evaluation

### 3.1 Logistic Regression

<img src="images/gridsearch_lr_std.png" width=450>  <img src="images/gridsearch_lr_no_std.png" width=450>



### 3.2 K-Nearest Neighbors

<img src="images/gridsearch_knn.png" width=550>

### 3.3 Random Forest

<img src="images/gridsearch_rf.png" width=550>

### 3.4 Model Evaluation 

#### 3.4.1 plot confusion matrix

<img src="images/cm_lr.png" width=300>  <img src="images/cm_knn.png" width=300>  <img src="images/cm_rf.png" width=300>

#### 3.4.2 plot roc-curve

<img src="images/roc.png" width=500>
