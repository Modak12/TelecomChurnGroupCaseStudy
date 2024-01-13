# Telecom-Churn-Case-study - Upgrad


## Problem Statement
In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

Goal: To reduce customer churn, telecom companies need to predict which customers are at high risk of churn. In this project, you will analyze customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn.


# Conclusion

## Final conclusion with PCA
After trying several models we can see that for acheiving the best sensitivity, which was our ultimate goal, the classic Logistic regression or the adaboost models preforms well. For both the models the sensitivity was approx 85-90%. Also we have good accuracy of apporx 80%. But we also noticed the resource consumption is more in these models.

## Final conclusion with NO PCA
We can see that the logistic model with no PCA has good sensitivity and accuracy, with compare to the models with PCA. So, we can go for the more simplistic as it also reduces the chance for overfitting.

## Final Model selection
After seeing both the models we conclude the better option to go with Logestic regression with No PCA. As it expliains the important predictor variables as well as the significance of each variable. The model also hels us to identify the variables which should be act upon for making the decision of the to be churned customers. Hence, the model is more relevant in terms of explaining to the business
