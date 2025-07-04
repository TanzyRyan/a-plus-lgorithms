# A+lgorithms
A comparative analysis between support vector machines (SVM) and random forest classifier for predicting student's grades based on their age, weekly study time, absences through the year and the level of parental support.

## Description
The goal is not only to predict student's grades based on certain variables, but to also determined which predictive model would perform better in this context between SVM and random forest. 

This comparative analysis involves cleaning the dataset using Pandas for data manipulation. This step handles missing values, remove outliers, and filtering columns to just the relavent features required for our predictive models. This data set is splitted into training and testing dataset. 

SVM and random forest classifier were implimented using Scikit-Learn and are both used to predict the student grades and are trained using the training dataset. The models are evaluated based on its accurancy of their prediction based on the test dataset to assess which predictive model has the better performance.  
