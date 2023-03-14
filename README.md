# Supervised-Machine-Learning-Mushroom_Competition
Supervised-Machine-Learning-Mushroom_Competition

Project Objective

The purpose of this project is to build a classification model for mushrooms with Pythons sklearn library. 
Based on some training data, the model should predict the outcome of the test data: Are the mushrooms poisonous or not? Special weight should be put on avoiding false negatives (i.e. predicting mushrooms as not poisonous when in fact they are poisonous).

Methods Used

Data exploration

Data preprocessing (using sklearns OneHotEncoder)

Building custom functions to manipulate the train data to put extra weight on avoiding fals negatives in the predicted test data

Building classification models with RandomForest and XGBoost and finding the best parameters for these models using GridSearch

Technologies

python, jupyter

pandas, numpy

matplotlib

scikit-learn, xgboost
