# A+lgorithms

A comparative analysis between support vector machines (SVM), random forest classifier, and regression models for predicting student's grades based on their age, weekly study time, absences through the year and the level of parental support.

## Description
The goal is not only to predict student's grades based on certain variables, but to also determined which predictive model would perform better in this context. The question of interests are:
  1. which classification algorithm performs better for predicting student's letter grade between support vector machine (SVM) or random forest
  2. would using regression algorithm to predict GPA and then converting it to letter grade produce a higher accurancy than directly using classification model to predict the letter grade?

This comparative analysis involves cleaning the dataset using Pandas for data manipulation. This step handles missing values, remove outliers, and ensuring all GPA are mapped to the correct letter grade. This dataset is split two sets such that the models are trained using the training dataset and are then tested based on the teest dataset. 

all classification and regression models are implimented using Scikit-Learn and the models are evaluated based on its accurancy of their prediction based on the test dataset to assess which predictive model has the better performance.  
