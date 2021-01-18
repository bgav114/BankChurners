# Bank Churners Classification

The primary purpose of the analysis is to utilise a machine learning classification model that can predict whether or not a customer of a bank is likely to churn. 

In order to do so, banking data (acquired from on online source: https://www.kaggle.com/shrutimechlearn/churn-modelling) consisting of 10 descriptive features (quantitative and qualitative) and 1 binary target feature, is modelled using the K-Nearest Neighbour Classifier, the Decision Tree Classifier and the Random Forest Classifier. 

Parameter specifications and feature selection for each of the aforementioned classifiers are determined using grid searches over all possible parameter values. The final model was selected based on its capabilities of optimising either the F-1 Score metric or the ROC-AUC metric, given that the sample data has a class imbalance within the target feature. 

The optimal models that we are able to derive are the Decision Tree Classifier and the Random Forest Classifier, given that they are 82.9% and 82.6% accurate (respectively) in predicting churners and non churners within a given bank’s customer base.
