# Machine Learning Homework


## Credit Risk Resampling

    1. Of the three aproaches, the oversampling models had the highest balanced accuracy scores, with naive oversampling the highest at 0.65.

    2. In terms of recall, again, oversampling had the highest scores - this time SMOTE the highest with 0.67.
    
    3.Oversampling was also highest for geometric mean, with naive oversampling the highest with a score of 0.66. 


---

## Credit Risk Ensemble

For the ensemble models, I was sure to scale my data before to achieve better results.

    1. Of the two models, the Easy Ensemble Classifier had the higher balanced accuracy score of 0.92.
    2. The Easy Ensemble Classifier also had the better recall, with a weighed average score of 0.94.
    3. Geometric mean was not reported in the classification report, but the Easy Ensemble Classifier had the higher F1 score of 0.97 (weighted average).
    4. For the balanced random forest model, the top three features were:
        Total Received Principal (0.074)
        Total_rec_int (0.061)
        Total_pymnt_inv (0.061)