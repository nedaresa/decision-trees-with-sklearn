
Building Decision Trees using scikit-learn

NJabbari; Aug 28th, 2019

Here I perform a decision tree algorithm on tennis.csv using scikit-learn.
Below, I suggest a few changes to be made to the solution workflow as provided by Learn.co:

- y is not a matrix and hence should be lowercase.
- Split train and test prior to OneHotEncoding rather than after. This helps avoid any information leakage from the test set into the train set.