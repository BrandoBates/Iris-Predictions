# Iris Predictions

Uses the well known Iris data set to evaluate different models of predicting types of flowers given their attributes.

First, we import the data set.

Then, we visualize the data through univariate and multivariate plots.

Next:
1. Separate out a validation dataset
2. Set-up the test harness to use 10-fold cross validation.
3. Build 6 different models to predict species from flower measurements (Logistic Regression (LR), Linear Discriminant Analysis (LDA), K-Nearest Neighbors (KNN), Classification and Regression Trees (CART), Gaussian Naive Bayes (NB), Support Vector Machines (SVM))
4. Select the best model

Finally, we test the most accurate model (in this case SVM) on our validation set to see just how accurate it is.
