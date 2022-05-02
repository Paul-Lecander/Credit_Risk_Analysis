# Credit Risk Analysis Using Supervised Machine Learning

## Overview
For this analysis, a dataset from LendingClub was used to sample data using multiple machine learning models to assess
which model best predicts credit risk. This was done by using the imbalanced-learn and scikit-learn libraries
in Python.</br> 
Two methods of machine learning were used in this analysis:</br>
1.) Resample - takes samples from the dataset repeatedly and gives metrics based on the dataset.</br>
2.) Ensemble - takes multiple base models and combines them to give predictions. </br>

Each algorithm was analyzed by creating a confusion matrix, calculating an accuracy score, and printing a classification report to assess the effectiveness. </br>


## Results

### Resample Method
#### Random Oversampling </br>
![RandomOverSample](https://github.com/Paul-Lecander/Credit_Risk_Analysis/blob/main/Images/Resample/RandomOverSample.png)</br>
- Accuracy score of 65.2%
- High risk category had very low precision with 1% but low risk had precision of 100%. The F1 score for high risk was 2% and low risk was 81%.


#### SMOTE Oversampling </br>
![SMOTE](https://github.com/Paul-Lecander/Credit_Risk_Analysis/blob/main/Images/Resample/SMOTE.png)</br>
- Accuracy score of 62.4%</br>
- High risk category had very low precision with 1% but low risk had precision of 100%. The F1 score for high risk was 2% and low risk was 80%.</br>

#### Undersampling </br>
![Cluster](https://github.com/Paul-Lecander/Credit_Risk_Analysis/blob/main/Images/Resample/Cluster.png)</br>
- Accuracy score of 51.6% </br>
- High risk category had very low precision with 1% but low risk had precision of 100%. The F1 score for high risk was 1% and low risk was 60%.</br>

#### Combination (Over and Under) Sampling </br>
![SMOTEENN](https://github.com/Paul-Lecander/Credit_Risk_Analysis/blob/main/Images/Resample/SMOTEENN.png)</br>
- Accuracy score of 63.8% </br>
- High risk category had very low precision with 1% but low risk had precision of 100%. The F1 score for high risk was 2% and low risk was 73%.</br>


### Ensamble Method </br>

#### Balanced Random Forest Classifier </br>
![BRFC_cm_report](https://github.com/Paul-Lecander/Credit_Risk_Analysis/blob/main/Images/Ensemble/BRFC_cm_report.png)</br>
- Accuracy score of 78.8% </br>
- High risk category had slightly higher precision than any of the resample methods with 4% and low risk had precision of 100%. 
The F1 score for high risk was 7% and low risk was 95%.</br>

#### Easy Ensemble AdaBoost Classifier </br>
![EEC](https://github.com/Paul-Lecander/Credit_Risk_Analysis/blob/main/Images/Ensemble/EEB.png)</br>
- Accuracy score of 92.5% </br>
- High risk category had a precision of 7% and low risk had precision of 100%. The F1 score for high risk was 14% and low risk was 97%.</br>
