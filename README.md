# Data Analysis on Drug Consumption using Python  ⚕️

# Objectives: 
* Data visualization
* Data cleaning
* Modeling
* Flask API

# Problem
Use given attributes to predict the drug consumption situation. Use binary classification by union of part of classes into one new class. "Never Used" and "Used over a Decade Ago" form class "Non-user" and all other classes form class "User".

# Data visualization
Using matplotlib and seaborn libraries to show relations between different variables and the targets.

For example : count of different classes for each drug, heat map showing correlation between the features, gender/age/education/ethnicity/country percentage comparaison, cross table using country and gender and ethnicity, relations between education/ethnicity and alcohol target, gender/age and cannabis/legal highs target, age and ecstasy target, pie chart of the frequency of using nicotine, number of observation and frequency for every consumption level of every drug, etc.

# Data cleaning
Changing drug classes into integer, rename columns, drop columns with low depedencies : nscore,escore,oscore,ascore,cscore and impulsive, convert some columns to string type and update data, modifying target into 0/1, etc.

# Modeling
Use the scikit-learn library, use different algorithms, different hyper parameters, do grid search.

Make train set and test set, scale the data, plot confusion matrix of the prediction, compare accurancy.

Models used : Logistic regression, Linear SVC, Random forest classifier, Decision Tree classifier, and KNN.
