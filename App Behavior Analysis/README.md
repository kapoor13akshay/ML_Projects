In this Case Study we are going to analyze the Users behaviour on a mobile application and will predict which users are more likely to
quit using the app after the trial period. This company wants to give selective offers to the users who are more likely to unenroll
once the trial period ends.
The dataset comprises of several features like timestamp when the app was opened for first time,age of the user,number of different screens
user went through during the trial period etc.
For this we did a lot of Feature engineering, also derived new columns from existing features to add more meaning to the existing features.
We used XGBoost Classifier as it is a huge dataset and were able to achieve a mean accuracy score of 75% using 10 Fold Cross Validation.
