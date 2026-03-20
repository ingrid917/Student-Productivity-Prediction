# Student-Productivity-Prediction

This project focuses on predicting a student's `productivity_score` from behavioral and academic features using regression-based machine learning models.

#1. Data Loading
- Loaded `train.csv`, `test.csv`, and `sample_submission.csv`.
- Created working copies for training (`df`) and testing (`X_test`) data.

#2. Data Cleaning
- Removed duplicate rows from the training dataset.
- Added a missing-value check to quickly verify whether null values exist in the dataset.
- Used boxplotting in order to check for ouliers and see any other inconsistencies in the data
- Used distribution plotting in order to see whether there are any asimetries in the data for each feature.

#4. Categorical Encoding
- Applied one-hot encoding to the `gender` feature in the training and testing data.

#5. Data Split
- Splitted the target from the training data
