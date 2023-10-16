# Iris-Classification
## Task
Build a Machine Learning model for Iris Classifciation.</br>
Tool Used: Jupyter Notebook, Python
## Description
- Used 4 different model to find the best accuracy score
  - Logistic Regression
  - Support Vector Classifier
  - Random Forest Classifier
  - K Neighbors Classifier
- Model Selection is carried out in 2 ways:
  - Comparing the model with default parameters using cross validation</br>
    SVC has the highest accuracy with default hyperparameters
  - Comparing the model with Hyperparameter Tunning using Grid Search CV</br>
    SVC with hyperparameter values as c:5 and kernel: 'rbf' has the highest accuracy score
