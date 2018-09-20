# Lasso-Regression-using-Coordinate-Descent

This is my implementation of Lasso regression using an optimized version of the coordinate descent algorithm.

The data was scraped from WineEnthusiast during the week of June 15th, 2017 and can be found on the analytics website Kaggle. This dataset provides a variety of features, the points, description (review), variety, country, province etc. FThe feature vectors for each review have been provided for this project.

File descriptions
trainData.txt - Training data matrix for predicting number of starts 
trainLabels.txt - Training labels, list of the number of stars for each review 
valData.txt - Validation data 
valLabels.txt - Validation labels 
testData.txt - Test data 
featureTypes.txt - List of features used 
sampleSubmission.csv - a sample submission file in the correct format

The data matrices are stored in Matrix Market Format, a format for sparse matrices. Each line is is a tuple of three elements for instance ID, feature ID, and feature value. Meta information for each feature is provided in featuresTypes.txt. The features are strings of one, two, or three words (n-grams). The feature values correspond roughly to how often each word appears in the review. All rows have also been normalized.
