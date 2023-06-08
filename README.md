# Tweet classification
This repository contains a notebook with a text classification task, and the data in a zip file.
## Task description
The task consists of a sentiment analysis task. It is a classification of tweets (positive or negative).
## Dataset
The dataset is available in the zip file. It is a .csv file. It contains 5 columns : ID, keyword, location, text and target.
## Approach
I began with the pre-processing steps of the text feature (lowercasing, special characters and stop words removal, lemmatization and tokenization).
Since Machine Learning algorithms require numerical data as input, I employed the TF-IDF (Term Frequency-Inverse Document Frequency) technique to transform the text feature to a numerical representation.
I tried different Machine Learning algorithms for the classification task (logistic regression, random forest, SVM, naive bayes), and printed the classification report for each model.
## Evaluation
To assess the performance of the logistic regression model, I used standard evaluation metrics for binary classifications.
Accuracy : 0.80
Precision : 0.79 for class 0 and 0.82 for class 1
Recall : 0.88 for class 0 and 0.69 for class 1
This can be due to the slight imbalance of the dataset in the target feature (4342 for the class 0 and 3271 for the class 1).
