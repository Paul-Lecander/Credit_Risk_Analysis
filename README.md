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



#### SMOTE Oversampling </br>
![SMOTE](https://github.com/Paul-Lecander/Credit_Risk_Analysis/blob/main/Images/Resample/SMOTE.png)</br>

#### Undersampling </br>
![Cluster](https://github.com/Paul-Lecander/Credit_Risk_Analysis/blob/main/Images/Resample/Cluster.png)</br>

#### Combination (Over and Under) Sampling </br>
![SMOTEENN](https://github.com/Paul-Lecander/Credit_Risk_Analysis/blob/main/Images/Resample/SMOTEENN.png)</br>


### Ensamble Method </br>

#### Balanced Random Forest Classifier </br>
![BRFC_cm_report](https://github.com/Paul-Lecander/Credit_Risk_Analysis/blob/main/Images/Ensemble/BRFC_cm_report.png)</br>


#### Easy Ensemble AdaBoost Classifier </br>
![EEC](https://github.com/Paul-Lecander/Credit_Risk_Analysis/blob/main/Images/Ensemble/EEB.png)</br>
