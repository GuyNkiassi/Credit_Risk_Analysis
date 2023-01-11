# Credit_Risk_Analysis


Supervised Machine Learning and Credit Risk

Overview of the loan prediction risk analysis:
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Different techniques were used to train and evaluate models with unbalanced classes. Various libraries and algorithms were used to build and evaluate models using resampling including:

imbalanced-learn
scikit-learn
RandomOverSampler
SMOTE algorithms
ClusterCentroids algorithm
SMOTEENN algorithm
BalancedRandomForestClassifier (bias reduction model)
EasyEnsembleClassifier (bias reduction model)
Purpose:
Explain how a machine learning algorithm is used in data analytics.
Create training and test groups from a given data set.
Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
Compare the advantages and disadvantages of each supervised learning algorithm.
Determine which supervised learning algorithm is best used for a given data set or scenario.
Use ensemble and resampling techniques to improve model performance.
Results:
The results for the six machine learning models including their respective balanced accuracy, precision, and recall scores are as follows:

Naive Random Oversampling


Balanced Accuracy: 0.6612700484668286
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .66/.67
SMOTE Oversampling


Balanced Accuracy: 0.6303296388959394
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .62/.64
Undersampling


Balanced Accuracy: 0.6303296388959394
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .63/.40
Combination Under-Over Sampling


Balanced Accuracy: 0.5173713090878325
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .70/.57
Balanced Random Forest Classifier
Pic 5

Balanced Accuracy: 0.7877672625306695
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .67/.91
Easy Ensemble AdaBoost Classifier


Balanced Accuracy: 0.925427358175101
Precision: The precision is low for High-risk loans and is high for Low-risk loans.
Recall: High/Low risk = .91/.94
Summary:
When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model. For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy. The other models were below .80 balanced accuracy. The precision for all models were similar and within an appropriate range. The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model. The Easy Ensemble AdaBoost Classifier had the highest recall score, making it the final best machine learning model to choose for further credit card analysis.