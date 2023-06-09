# Credit_Card_Defaulters_Prediction-
Credit_Card_Defaulters_Prediction
Given characteristics (gender, education, age, marriage) and payment history of a customer, is he or she likely to default on the credit card payment next month? Overview This is a classification model for a most common dataset, Credit Card defaulter prediction. Prediction of the next month credit card defaulter based on demographic and last six months behavioral data of customers.

# Problem Statement
Predicting whether a customer will default on his/her credit card This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients.

# Data Description
This research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. This study reviewed the literature and used the following 23 variables as explanatory variables:

X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.

X2: Gender (1 = male; 2 = female).

X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).

X4: Marital status (1 = married; 2 = single; 3 = others).

X5: Age (year).

X6 - X11: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows: X6 = the repayment status in September, 2005; X7 = the repayment status in August, 2005; . . .; X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.

X12-X17: Amount of bill statement (NT dollar). X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005; . . .;X17 = amount of bill statement in April, 2005.

X18-X23: Amount of previous payment (NT dollar). X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .;X23 = amount paid in April, 2005.

# Algorithms

Support Vector Machine,

Random Forest Classifier,

Decision Tree Classifier,

Logistic Regression,

knn,

naive bayes.

# Appraoch Pipeline

Data Preprocessing

Data Exploration

Model Prediction

# CONCLUSIONS:

• From the above machine learning models, we can conclude that Logistic Regression gives us the highest accuracy.

• After implementation of bagging concept, Logistic Regression still tops is terms of accuracy with 81.61 %.

• Based on the exploratory data analysis, we discover that human characteristics are not the most important predictors of default.

• Model can be improved with more data and computational resources.

• We can also see that most credit card users are females and so are the highest number of defaulters.

• People aged between 20 to 30 have moderate default conditions.

• People aged above 61 are more likely to default the payments.

• Highly educated persons are less likely to default whereas, less educated people come under the highly defaulted category.







