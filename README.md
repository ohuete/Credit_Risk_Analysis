# Credit Risk Analysis
## Purpose & Background
In this project, I utilize machine learning to determine how effective this method may be when identifying credit card risk. As we know, the credit risk problem is inherently unbalanced. I used a number of different techniques to train and evaluate models with unbalanced classes. Some techniques used were RandomOverSampler and SMOTE to compare oversampling models and ClusterCentroids for undersampling. SMOTEEN was also used in undersampling and over sampling models. Lastly, I utilized the BalancedRandomForestClassifier and EasyEnsembleClassifier algorithms, which focused on reducing bias. 

## Results
The following is a list of the results from the machine learning techniques used with images. 

**RandomOverSampler**

From the image below, we see that the accuracy score is about 64.5% and low risk detection is high while high risk detection is low. Recall score for high risk is 61% and low risk is 68%.

<img width="917" alt="Screen Shot 2022-10-21 at 3 19 21 PM" src="https://user-images.githubusercontent.com/107595127/197296775-b5e547d0-6904-4601-b95c-424a8a2b6468.png">

**SMOTE**

From the image below, we see that the accuracy score is about 62.8% and low risk detection is high while high risk detection is low. Recall score for high risk is 61% and low risk is 65%.

<img width="786" alt="Screen Shot 2022-10-21 at 3 47 47 PM" src="https://user-images.githubusercontent.com/107595127/197303015-840248d0-ed72-4caa-ba4e-9412ae825c23.png">

**ClusterCentroids/Undersampling**

From the image below, we see that the accuracy score is about 62.8% and low risk detection is high while high risk detection is low. Recall score for high risk is 57% and low risk is 45%. 

<img width="796" alt="Screen Shot 2022-10-21 at 4 01 34 PM" src="https://user-images.githubusercontent.com/107595127/197303235-b29c4c0d-2fc9-4e17-9da2-2590afdecc43.png">

**SMOTEEN/Combination**

From the image below, we see that the accuracy score is about 64.1% and low risk detection is high while high risk detection is low. Recall score for high risk is 70% and low risk is 58%.

<img width="791" alt="Screen Shot 2022-10-21 at 4 05 20 PM" src="https://user-images.githubusercontent.com/107595127/197303450-6a14561f-1255-4fee-9d47-710f47671fc9.png">

**Balanced Random Forest Classifier**

From the image below, we see that the accuracy score is about 79.4% and low risk detection is high while high risk detection is low. Recall score for high risk is 70% and low risk is 89%.

<img width="785" alt="Screen Shot 2022-10-21 at 4 08 47 PM" src="https://user-images.githubusercontent.com/107595127/197303522-609c66a7-78f5-44b7-b78b-37bdf91663de.png">

**EasyEnsembleClassifier**

From the image below, we see that the accuracy score is about 92.5% and low risk detection is high while high risk detection is low. Recall score for high risk is 91% and low risk is 94%.

<img width="784" alt="Screen Shot 2022-10-21 at 4 10 29 PM" src="https://user-images.githubusercontent.com/107595127/197303653-50bf317a-71c2-4665-b379-f0ba1888ccd1.png">

## Summary
Of all the different models and methods used for credit risk analysis, the EasyEnsemble AdaBoost Classifier proved to be the best one. This model method generated the best results, however, it's precision on high risk analysis could improve. Nonetheless it is higher than the rest. Perhaps, additional methods could be used to detect high risk in order to get the precision on par with the low risk analysis.
