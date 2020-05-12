# Pattern Recognition Project
## Breast cancer detection using Machine learning models and algorithms

With the use of the python and it's libraries i made a project for detecting a breast cancer with the applying **Machine Learning** to a set of data informations. 
For this project i have used the database from https://www.kaggle.com/uciml/breast-cancerwisconsin-data. 

The distribution of the data set classes is: 357 benign and 212 malignant.
For data Visualization i have used the **seaborn** (countplot, heatmap, distplot, boxplot) and **matplotlib**.

In the algorithms part of the project, because we have only two types of values, we have a **classification** problem. In this project i have used the tools from the **Scikit-Learn** library.
Algorithms used in this project:
  - Stochastic Gradient Descent classifier
  - K Nearest Neighbors Classifier
  - Random Forest Classifier
  - Decision Tree Classifier
  - SVC - Support Vector Machines Classifier
  - NuSVC - Support Vector Machines Classifier
  - LinearSVC - Support Vector Machines Classifier

Also i have used **GridSearchCV()** for tunning the parameters of the **Random Forest Classifier** and **Decision Tree Classifier**.


# Conclusion
From all of the experiments done on this data set, we can surely say that **Random Forest Classification** gives the most accurate results.

# References:
1. Data set: https://www.kaggle.com/uciml/breast-cancer-wisconsin-data
2. Pandas: https://pandas.pydata.org/pandas-docs/stable/
3. NumPy and Scipy: https://docs.scipy.org/doc/
4. Seaborn: https://seaborn.pydata.org/
5. Scikit-learn: https://scikit-learn.org/stable/modules/svm.html
6. Wikipedia – Confusion Matrix: https://en.wikipedia.org/wiki/Confusion_matrix
7. Developers.Google: https://developers.google.com/machine-learning/crashcourse/classification/precision-and-recall
