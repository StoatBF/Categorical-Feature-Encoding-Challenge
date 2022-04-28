# Categorical Feature Encoding Challenge

An appropriate method for encoding categorical variables is important for machine learning tasks.\
It aims to try different encoding schemes for different algorithms to compare the performance.

binary features;

low- and high-cardinality nominal features;

low- and high-cardinality ordinal features;

(potentially) cyclical features;

This project aims to predicti the probability [0, 1] of a binary target column.

The data contains binary features (bin_*), nominal features (nom_*), ordinal features (ord_*) as well as (potentially cyclical) day (of the week) and month features. The string ordinal features ord_{3-5} are lexically ordered according to string.ascii_letters.

Since the purpose of this competition is to explore various encoding strategies, the data has been simplified in that (1) there are no missing values, and (2) the test set does not contain any unseen feature values.

# Files
train.csv - the training set；

test.csv - the test set; you must make predictions against this data；

sample_submission.csv - a sample submission file in the correct format
