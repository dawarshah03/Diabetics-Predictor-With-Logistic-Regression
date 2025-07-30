# Diabetics Predictor Using Logistic Regression 

I made a Diabetics Predictor using Logistic Regression in Python.

It’s a binary classification model which means it predicts only two outcomes: diabetic (1) or not diabetic (0).

I used the train_test_split method to split the data into training and testing sets.

Then I applied Logistic Regression to train the model and check how well it predicts.

At the end, I tested it using the x_test and y_test data.

The accuracy score I got was:
0.8051948051948052

I also used .predict_proba() which gives the probabilities like how sure the model is about 0 or 1.

For example, if it says [0.75 0.25], that means 75% chance it's 0 and 25% it's 1.

Code and dataset are in the repo.
