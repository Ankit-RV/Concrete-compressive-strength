# Concrete compressive strength

### Description and Project Overview

… The objective of this project is trying to predict the concrete compressive strength based important predictors. The study will consist of evaluating the impact of different factors such as cement, water, age, fly ash, and or additives. We will evaluate the components that are highly correlated with concrete compressive strength and other components that are less influential and can be neglected through visualization or correlation matrix.

## Concrete Compressive Strength Prediction using Machine Learning

Concrete is one of the most important materials in Civil Engineering. Knowing the compressive strength of concrete is very important when constructing a building or a bridge. The Compressive Strength of Concrete is a highly nonlinear function of ingredients used in making it and their characteristics. Thus, using Machine Learning to predict the Strength could be useful in generating a combination of ingredients which result in high Strength.


## 1. Problem Statement
Predicting Compressive Strength of Concrete given its age and quantitative measurements of ingredients.
Modeling of strength of high performance concrete using Machine Learning.
https://docs.google.com/document/d/10oVqW5Nv7lr_dERYoTK9TO3OB23WRa3b/edit

### Context

Concrete is the most important material in civil engineering. The concrete compressive strength is a highly nonlinear function of age and ingredients. These ingredients include cement, blast furnace slag, fly ash, water, superplasticizer, coarse aggregate, and fine aggregate.

## 2. Data Description

This project will be based on a dataset obtained from the UCI Repository. The dataset consists of 1030 observations under 9 attributes. The attributes consist of 8 quantitative inputs and 1 quantitative output. The dataset does not contain any missing values. The dataset is focused on the compressive strength of a concrete. The attributes include factors that affect concrete strength such as cement, water, aggregate (coarse and fine), and fly ash etc.

Data is obtained from
https://drive.google.com/file/d/1J7fMxEFl8C0JUNa_2UqcOy8qnBmNcIvP/view?usp=sharing

* Number of instances - 1030
* Number of Attributes - 9
  * Attribute breakdown - 8 quantitative inputs, 1 quantitative output

#### Attribute information
##### Inputs
* Cement 
* Blast Furnace Slag
* Fly Ash
* Water
* Superplasticizer
* Coarse Aggregate
* Fine Aggregate

All above features measured in kg/m^3

* Age (in days)

##### Output
* Concrete Compressive Strength (Mpa)

## 3. Modelling and Evaluation

* Algorithms used
  * Linear regression
  * Decision Trees
  * Random Forests

* Metric - Since the target variable is a continuous variable, regression evaluation metric RMSE (Root Mean Squared Error) and R2 Score (Coefficient of Determination) have been used.

#### process

* Downloaded concrete strength data from UCI Repository. Instigate this data in SSMS database and perform ETL to remove outliers, clean up bad records, normalize revenue numbers to standards format using python, google colab and two standard deviation along with some other statistical techniques.
* Used Linear regression, Decision Trees and Random Forests algorithms for building the model. Since the target variable is a continuous variable, regression evaluation metric RMSE and R2 Score have been used.





## 4. Result
**Feature correlation**


![image](https://user-images.githubusercontent.com/53686812/203727759-45e036e7-c656-4292-9bfe-4c283c7450d2.png)



**Feature importance**


![image](https://user-images.githubusercontent.com/53686812/203728127-cf0b7223-a75c-4503-ba51-31613906ffaa.png)


**Final Comparison**


![image](https://user-images.githubusercontent.com/53686812/203728520-aa55da20-3be8-4c86-8fea-376fbc913026.png)




## 5. Conclusion

Evaluate the components that are highly correlated with concrete compressive strength and other components that are less influential and can be neglected through visualization or correlation matrix. In this study, used different machine learning techniques to analyze and predict the concrete compressive strength. Different modeling techniques will be used for the prediction. The modeling technique include multiple linear regression, decision tree, and random forest, etc. A comparative analysis will be performed to identify the best model for our prediction in terms of accuracy. Used Linear Regression, Decision Trees and Random Forests to make predictions and compared their performance. **Random Forest Regressor** has the lowest RMSE and is a good choice for this problem. Also, we can further improve the performance of the algorithm by tuning the hyperparameters by performing a grid search or random search.

The best model will be helpful for civil engineers in choosing the appropriate concrete for any kind of construction work.
