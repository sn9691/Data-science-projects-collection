# kaggle-submission
## Titanic: Machine learning from disaster challenge


This is my last submission in the Titanic challenge in Kaggle. The submission score was 79.9% and the rating was 1694 (top 17%) at the time of writing this.

About the model:

The missing cabin data was predicted using a simple Decision Tree because too much of the data was missing and the data had to be predicted using a lot more categorical variables than continuous variables.

The predictions were made using two models: Random Forest and Support Vector Machine.

The Random Forest, tuned using GridSearchCV, scored an accuracy of 77.8%.
The Support Vector Machine, tuned using GridSearchCV, scored an accuracy of 79.9%.
The kernel used for SVM was linear since this is a binary classification problem.
