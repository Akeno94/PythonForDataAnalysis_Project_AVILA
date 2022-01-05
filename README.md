# Python For Data Analysis - Final Project
## Avila Data Set
Project done by Kevin Gomes

### The project

This project aims to visualize and predict data from the Avila Data Set.

The prediction of this Data Set is a case of Classification.

To predict the data, I used the following methods :
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- eXtreme Gradiant Boost (XGBoost)
- Decision Tree
- Random Forest
- Logistic Regression

### Conclusion

After using many models with differents combinations of hyperparameters, the best model found is XGB Classifier with an accuracy of 99.6357%.
There were also other models with an accuracy close to XGB like Random Forest (98.8878%) and Decision Tree (98.2934%).
But the least accurate model was Logistic Regression with only 55.2733% of accuracy.


Link to the Avila Data Set : https://archive.ics.uci.edu/ml/datasets/Avila

libraries needed :
- pandas
- numpy
- seaborn
- matplotlib
- sklearn
- xgboost
