# Best Model for Heart Attack Prediction using Machine Learning

#### -- Project Status: Completed

## Project Objective
Make the best model to predict heart attack for patients using machine learning. Three types of models are used: **Logistic Regression, Support Vector Machines, Decision Tree** and the results will be compared the accuracy and F1-score to determine the best model.

### Methods Used
* Machine Learning
* Logistic Regression
* Support Vector Machines
* Decision Tree

### Language
* Python

### Module
* skicit-learn
* matplotlib
* pandas
* numpy
* seaborn

## Step-by-step
1. It will be checked whether the data is ready to use by checking
    - Missing value
    - Outliers
2. Perform **feature selection** by using **Pearson Correlation** or comparing the correlation variable with the target variable, namely output
3. Visualize the correlation between variables with a heat map
4. Calculate the mean correlation and take the features with a greater correlation than the mean
5. Extract these features into data X and the target variable as data Y
6. Split the data into training data and testing data with a ratio of 8:2
7. Will use **Logistic Regression, Deision Tree, and Support Vector Machine **with
   - Choose the best parameters by hypertuning
   - Print reports from the Logistic Regression model

Conclusions are reached by analyzing the test and train scores that have been obtained for each model, it is obtained
1. The Logistic Regression model has the highest test score but there is a significant difference from the train score, which allows overfitting to occur.
2. The Decision Tree model produces a train score of 1 so that it allows overfitting to occur
3. The SVM model has a fairly high test score and when compared to the train score there is not too much difference so the possibility of overfitting is low
So, the best model to predict this dataset is **Support Vector Machine Method.**

## Getting Started
1. You can access the raw data [here](https://github.com/angelpatriciads/heart-attack-prediction/blob/main/heart_attack_dataset.csv) within this repo.
2. All of the scripts are being kept [here](https://github.com/angelpatriciads/heart-attack-prediction/blob/main/heart_attack_prediction.ipynb).
