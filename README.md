# Credit Risk Modelling - Using German Data from 1994

Using a dataset of around 1000 observations of loan applications, I try to use a variety of classification algorithms to construct a model that maximizes the recall when it comes to classifying bad loans.  

I fit six different models (e.g. Logistic Regression, KNN, SVC, Random Forests, XGBoost, Naive-Bayes) plus a stacked model comprising of the four best ones. In the end, Naive-Bayes performs the best when it comes to maximizing our recall (0.53) while XGBoost comes in second. On the other hand, XGBoost maximizes our AUC while Naive-Bayes comes third (after XGB and SVC). 
