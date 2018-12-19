# Food-Borne-Illness-Analysis

A foodborne disease outbreak occurs when two or more people get the same illness from the same contaminated food or drink. The Center for Disease Control and Prevention (CDC) estimates roughly 1 in 6 Americans (48 million people) get sick, 128,000 are hospitalized, and 3,000 die of foodborne diseases each year.

### ***Use cases :***

  * Predict the status of a food borne illness (confirmed/suspected)
  * Predict the number of illnesses that might occur in a state in USA
  
### ***Models used for prediction :***

  * K Nearest Neighbors
  * Linear Regression
  * Logistic Regression
  * Ada boost 
  * Random Forest
  * Gradient Descent
  
  
Model Hyper parameter tuning for Random forest Classifier was employed to improve model accuracies. GridSearchCV methodologies 
were implemented to estimate the best parameters for the model. Various parameters tuned for improving the performance were : 
n_estimators, max_depth (max depth to which a random forest should build a tree), min_samples_split and min_samples_leaf. The 
below plot is a feature importance plot that shows that state, location and species causing illness are major contributors to 
case being confirmed or suspected of food borne illness.
<br></br>


![Tuned Hyper Parameters](https://github.com/srijitravi94/Food-Borne-Illness-Analysis/blob/master/Images/ParameterTunedRFC.JPG)
<br></br>
![Feature Importance plot and classification report](https://github.com/srijitravi94/Food-Borne-Illness-Analysis/blob/master/Images/TunedModelReportClassification.JPG)
<br></br>
<br></br>
<br></br>

5 different regressors were tried for predicting illnesses in a state and were evaluated based on the test set. Random Forest 
regressor proved yet again, to be the best suited model for this dataset with a test accuracy of around 82%.
<br></br>

![Regressors](https://github.com/srijitravi94/Food-Borne-Illness-Analysis/blob/master/Images/RegressorsAtGlance.JPG)
<br></br>
<br></br>

Parameter tuning  was done for Random forest model to improve accuracies. Parameters like n_estimators, min_samples_split and 
min_samples_leaf were tuned and optimized. This resulted in an increase in the accuracy to 83.42%.
<br></br>

![HyperparameterTunedTask2](https://github.com/srijitravi94/Food-Borne-Illness-Analysis/blob/master/Images/HyperparameterTunedTask2.JPG)
