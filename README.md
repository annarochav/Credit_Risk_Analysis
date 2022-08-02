# :credit_card: Credit_Risk_Analysis :credit_card:

Challenge Week17 Data Analysis BootCamp NumPy, SciPy, Scikit-learn.

## ⚡Overview of the analysis:

This project required to create a supervised machine learning model that predicts credit risk. Logistic regression, decision trees, random forest among other tools were used and compared to determine which algorithm works better: 

1.	Naive Random Oversampling
2.	SMOTE Oversampling
3.	Cluster Centroid Under sampling
4.	SMOTEENN Sampling
5.	Balanced Random Forest Classifying
6.	Easy Ensemble Classifying

## ⚡Results:

This are the results for the six machine learning models:

**Naive Random Oversampling**
 + Accuracy Score: 64%
 + Precision High Risk: 1%
 + Precision Low Risk: 100%
 + Recall High Risk: 62%
 + Recall Low Risk: 65%

<img src="https://github.com/annarochav/Credit_Risk_Analysis/blob/main/Resources/1_naive.png" width="550" height="" />

**SMOTE Oversampling**
 + Accuracy Score: 63%
 + Precision High Risk: 1%
 + Precision Low Risk: 100%
 + Recall High Risk: 62%
 + Recall Low Risk: 64%

<img src="https://github.com/annarochav/Credit_Risk_Analysis/blob/main/Resources/2_SMOTE.png" width="550" height="" />

**Cluster Centroid Under sampling**
 + Accuracy Score: 63%
 + Precision High Risk: 1%
 + Precision Low Risk: 100%
 + Recall High Risk: 59%
 + Recall Low Risk: 43%

<img src="https://github.com/annarochav/Credit_Risk_Analysis/blob/main/Resources/3_UNDERSAMPLING.png" width="550" height="" />

**SMOTEENN Sampling**
 + Accuracy Score: 51%
 + Precision High Risk: 1%
 + Precision Low Risk: 100%
 + Recall High Risk: 70%
 + Recall Low Risk: 57%

<img src="https://github.com/annarochav/Credit_Risk_Analysis/blob/main/Resources/4_combination.png" width="550" height="" />

**Balanced Random Forest Classifying**
 + Accuracy Score: 67%
 + Precision High Risk: 7%
 + Precision Low Risk: 100%
 + Recall High Risk: 34%
 + Recall Low Risk: 100%

<img src="https://github.com/annarochav/Credit_Risk_Analysis/blob/main/Resources/5_balanced.png" width="550" height="" />

**Easy Ensemble AdaBoost Classifier**
 + Accuracy Score: 93%
 + Precision High Risk: 8%
 + Precision Low Risk: 100%
 + Recall High Risk: 91%
 + Recall Low Risk: 95%

<img src="https://github.com/annarochav/Credit_Risk_Analysis/blob/main/Resources/6_ADA.png" width="550" height="" />

## ⚡Summary:

Loans are a very delicate topic, and it is important to detect the ones with high risk. The results show that the **Easy Ensemble AdaBoost Classifier** is the best model with an accuracy score of **93%** and a recall (sensitivity) score of **91%** for high risk and **95%** for low risk. The Easy Ensemble AdaBoost Classifier is the best machine learning model to choose for loan analysis.

Ranking of models in descending order based on High-Risk results:

 + Easy Ensemble AdaBoost Classifier: 93.2% accuracy, 9% precision, 92% recall
 + Balanced Random Forest Classifying: 67% accuracy, 7% precision, 70% recall
 + SMOTEENN Sampling: 51% accuracy, 1% precision, 70% recall
 + SMOTE Oversampling: 63% accuracy, 1% precision, 62% recall
 + Naive Random Oversampling: 64% accuracy, 1% precision, 62% recall
 + Cluster Centroid Under sampling: 63% accuracy, 1% precision, 59% recall 
