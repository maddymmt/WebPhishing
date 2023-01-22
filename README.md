# Web Phishing  

This code is a demonstration of building machine learning models for classification problem. The goal of this code is to train machine learning models and find the best parameters for each model using Grid Search and Recursive Feature Elimination (RFE).  

The models used in this code are Decision Tree, Random Forest, XGBoost, and Neural Network. For each model, we first train the model using Grid Search to find the best parameters. Then we use RFE to select the most important features, and retrain the model using the new feature set. Finally, we use Permutation Importance to check the importance of each feature.

The code is written in Python, and the main libraries used are:

* pandas for data manipulation
* numpy for numerical computation
* sklearn for machine learning models and feature selection
* eli5 for permutation importance
* xgboost for the XGBoost model
