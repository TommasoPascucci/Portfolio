# Portfolio
Tommaso Pascucci
IS 6812 Portfolio

# Kaggle Home Credit Default Risk
## Business problem summary
The Home Credit Default Risk project focuses on predicting the likelihood of a client defaulting on a loan. The problem arises identifying potential customers who may have a high risk of default and without typical tools like credit scores. Lenders often have incomplete or inaccurate information on applicants' financial backgrounds, making it difficult to evaluate credit risk accurately. Defaulting loans can cause financial loss to the company, increase operational costs, and damage the institution's reputation. The goal is to model a way to predict whether clients will default on loans or not.

## Project objective

## solution to a business problem

## My contribution
I helped with some of the data cleaning and as a group decided how we wanted to handle missing values so that we all worked on the same cleaned data set when creating the models. I focused on creating the logistic regression and XGBoost models. With the XGboost being the one that achieved our best Kaggle score of 0.69889.

### Logistic Regression
* 91.93% Accuracy
* 2.09% F1
* 50% Recall
* 1.07% Precision
* 
### XGBoost model
* 91.98% Accuracy
* 95.81% / 4.34% F1
* 99.86% / 2.26% Recall
* 92.08% / 58.03% Precision /a
![](/images/matrix.png)
![](/images/AUC.png)

### [EDA](https://github.com/TommasoPascucci/Portfolio/blob/main/EDA.Rmd)
Exploring the data set and the importance of the various variables
![](/images/Age.png)

### [Modeling](https://github.com/TommasoPascucci/Portfolio/blob/main/practiceProjectModeling2.Rmd)
XGboost

## Business value of the solution
A reliable predictive model will help Home Credit make better loan approval decisions, reducing the risk of defaults while extending credit to more responsible clients. This will improve profitability, streamline the approval process, and enhance customer satisfaction by offering loans to applicants who may have been previously overlooked.

## Diffuiculties
There were a variate of challenges though we predominantly focused on data cleaning and handling 
Handling class imbalance was quite challenging  and variable importance

## Learnings
Spending more time at the beginning cleaning data and identifying important features makes it easier to work on building models. This also allows for more time for hyper parameter tuning 


