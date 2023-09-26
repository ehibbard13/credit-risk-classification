# credit-risk-classification

The origional files were provided by UW Madison boot camp. 

First the provided CSV file was imported, labels were created, displayed, and then it was split into training and testings sets.

After I created a logistic regression model with the origial data, I used this data to print a balanced accuracy score, a confusion matrix, and a classification report. 

The result of this was that the model predicted the healthy loans flawlessly and the high-risk loans not so much. 
              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384

After I nearly repeated the previous steps with the resampled data. 

It was found that the model predicted the healthy loans nearly perfectly and did a better job than the previous model with the high-risk loans. 
              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619

    accuracy                           0.99     19384
   macro avg       0.92      0.99      0.95     19384
weighted avg       0.99      0.99      0.99     19384
