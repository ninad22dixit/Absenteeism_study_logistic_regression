# Absenteeism_study_logistic_regression

Absenteeism study is a guided project as a part of the 'Udemy Data Science Bootcamp'. The raw data was provided in a '.csv' file, which contained employees' details such as dates and duration of absence, average work load, age, body mass index, commuting distances, and reason for absence. Our task was to develop a model that would predict which employees are likely to be absent for longer than the median duration of absence. This task was divided into two parts, which are stored in two separate Jupyter notebooks.

'Absenteeism preprocessing ND' notebook contains the code written to split the reasons of absence into several groups. This notebook utilizes the learnings of NumPy and Pandas. 'Absenteeism_preprocessed.csv' contains the cleaned data that was used to perform further analysis.

'Absenteeism_exercise_ND' contains a logistic regression model to predict absenteeism. By setting the median value as a standard, the data was split into nearly equal halves giving us a reasonably balanced data set. Standardization (scaling) and logistic regression of the data was carried out using 'SciKit-learn'. A model with about 80% accuracy was achieved the factors having significant influence on the employee absenteeism were identified.
