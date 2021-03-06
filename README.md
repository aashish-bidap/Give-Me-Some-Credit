# Title Give Me Some Credit

## Description
Banks play a crucial role in market economies. They decide who can get finance and on what terms and can make or break investment decisions. For markets and society to function, individuals and companies need access to credit. Credit scoring algorithms, which make a guess at the probability of default, are the method banks use to determine whether or not a loan should be granted. This analysis focusses to improve on the state of the art in credit scoring, by predicting the probability that somebody will experience financial distress in the next two years.
<br><br>
The goal of this analysis is to build a model that borrowers can use to help make the best financial decisions.

## Technology Used
- Machine Learning
- Binary Classification
- XGBoost Classifier
- Descriptive Statistics

## Environment
Python (scikitlearn, seaborn, pandas, numpy, matplotlib) , Jupyter Notebook ,SHAP

## XGBoost Model Intepretation

![model](https://github.com/aashish-bidap/Give-Me-Some-Credit/blob/master/Model_interpretation.png)

<br>

-  Higher the RevolvingUtilizationofUnsecuredLines higher the defaulter probability <br>
-  Higher the number of times the borrower has past due more is the probability of being a defaulter.<br>
-  Lower the age high are the likelihood of being defaulter.<br>
-  With more number of open credit lines and loans high are probability for being a defaulter.<br>
-  Lower the Monthly Income higher the chances of being a defaulter.<br>
-  Higher the Number of dependents and realestate loans more the probability of being a defaulter.<br>
