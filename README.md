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

- Using this model, we come up with a balanced accuracy score of 53
- Based on the imbalanced classification report:
  - The precision for predicting low risk (1.0) is higher than the precision for predicting high risk (0.01)
  - The recall(sensitivity) values for predicting low risk credit is lower (0.40) compared to the high risk credit (0.66)
  
  
