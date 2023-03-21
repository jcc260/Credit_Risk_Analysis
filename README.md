# Credit_Risk_Analysis
## Overview
Build and evaluate several machine learning models to assess credit risk, using data from LendingClub; a peer-to-peer lending services company. Finally, recommend whether they should be used to predict credit risk. 
## Machine learning models assessed with analysis
### Naive Random Oversampling model
- Using this model, we come up with a balanced accuracy score of 64
- Based on the imbalanced classification report:
  - The precision for predicting low risk (1.0) is higher than the precision for predicting high risk (0.01)
  - The recall(sensitivity) values are the same for predicting both low risk and high risk credit - 0.64
  
  <img width="632" alt="Screenshot 2023-03-21 at 5 03 13 PM" src="https://user-images.githubusercontent.com/113556769/226740402-66a0b200-f28e-4e1f-9e0a-4c1f52824150.png">

### SMOTE Oversampling model
- Using this model, we come up with a balanced accuracy score of 66
- Based on the imbalanced classification report:
  - The precision for predicting low risk (1.0) is higher than the precision for predicting high risk (0.01)
  - The recall(sensitivity) values for predicting low risk credit is higher (0.69) compared to the high risk credit (0.63)
  
  <img width="561" alt="Screenshot 2023-03-21 at 5 08 27 PM" src="https://user-images.githubusercontent.com/113556769/226741368-1be72f81-4446-43a6-8662-89287fba9457.png">

### Undersampling using the Cluster Centroids Algorithm

- Using this model, we come up with a balanced accuracy score of 64
- Based on the imbalanced classification report:
  - The precision for predicting low risk (1.0) is higher than the precision for predicting high risk (0.01)
  - The recall(sensitivity) values for predicting low risk credit is lower (0.40) compared to the high risk credit (0.66)
  
  <img width="574" alt="Screenshot 2023-03-21 at 5 25 07 PM" src="https://user-images.githubusercontent.com/113556769/226744567-1e3e6359-3638-4cb2-ae13-b16c46fea602.png">

### SMOTEENN algorithm

- Using this model, we come up with a balanced accuracy score of 64
- Based on the imbalanced classification report:
  - The precision for predicting low risk (1.0) is higher than the precision for predicting high risk (0.01)
  - The recall(sensitivity) values for predicting low risk credit is lower (0.57) compared to the high risk credit (0.72)
  
  <img width="540" alt="Screenshot 2023-03-21 at 5 29 29 PM" src="https://user-images.githubusercontent.com/113556769/226745555-63d09c4a-1b7d-476c-b3d7-65d546dd6139.png">

## Analysis
- All four models have a similar accuracy score.
- The precision for predicting low risk is much better compared to high risk credit for all the four models.
- The recall (sensitivity) for predicting high risk credit is much better with the SMOTEEN model compared to the other three models.
- Even though all the four models do not have a good accuracy score and the recall values for predicting high risk credit is at a max value of 72, it would be appropriate to go with the SMOTEENN model due to the capability to predict high risk credit more accurately.
