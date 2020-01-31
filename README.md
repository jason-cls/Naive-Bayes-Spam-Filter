# Naive Bayes Spam Filter
I build a multinomial Naive Bayes algorithm in order to classify incoming SMS messages as spam or non-spam (ham). To train and test the Naive Bayes model, a dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection) consisting of 5,572 SMS messages is used.

### Results
- With term frequency featurization, the model achieved an accuracy of 98.7% on the test set
- Weighted averaged f1-score of 0.99 on test data

### Libraries used
- pandas
- re
