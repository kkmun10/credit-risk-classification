# credit-risk-classification

## Overview of Analysis:

Using a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. 
The dataset has loan information regarding the loan amount, rates, the number of derogatory marks(late payments) and if the loan status is in default or not. The goal was to predict weather a loan is classified  '0' (healthy loan) or '1' (high-risk loan). The original dataset has 75,036 healthy loans and 2,500 high risk loans. Using LogisiticRegression to predict these loans and then resampling the data to obtain a high accuracy score.

## Results
  Model 1: LogisticRegression
        *Balanced Accuracy Score: 94.43%
        *Precision Score: 
          *Class 0: 1.00
          *Class 1: 0.87
        *Recall Score:
          *Class 0: 1.00
          *Class 1: 0.89   
  Model 2: RandomOverSampler
        *Balanced Accuracy Score: 99.60%
        *Precision Score: 
          *Class 0: 1.00
          *Class 1: 0.87
        *Recall Score:
          *Class 0: 1.00
          *Class 1: 1.00
          
## Summary:
 Model 2 is far more accurate as predicting high risk loans. I would suggest we use Model 2 in this review.
 Correctly identifying high-risk loans is crucial to minimize the risk of incorrectly classifying them as healthy loans.
 
