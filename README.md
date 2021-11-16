#Credit_Risk_Analysis:
Supervised Machine Learning and Credit Risk week 17
# Credit_Risk_Analysis
Working with Supervised Machine Learning through Jupyter Notebook
## Overview of MechaCar_Challenge_Analysis:

You have worked over the last few weeks, mentoring with Jill to gain a background in supervised machine learning. After studying, you are comfortable preforming data preparation, statistical reasoning and know the basics behind machine learning. Jill is now looking for you to apply your skills in a real-life scenario credit card risk. After getting the data from LendingClub, we will utilize what we learned from imbalanced-learn and scikit learn to build models. Then taking our knowledge of RandomOverSampler, and ClusteringCenteroids algorithm and tying in the Smoteen algorithm in to oversample the data. From there we will be comparing the data utilizing the BalancedRandomForestClassifier and EasyEnsembleClasifyier machine learning modules to help reduce bias and best asses credit risk. 

#### The below pseudocode provided us an outline for the analysis ####
•	Deliverable 1:  Use Resampling Models to Predict Credit Risk

•	Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk

•	Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

•	Deliverable 4: A Written Report on the Credit Risk Analysis

### Credit_Risk_Analysis Results: ###

1.	#### Deliverable 1:  Use Resampling Models to Predict Credit Risk 

•	Create the training variables by converting the string values into numerical ones using the get_dummies() method:


![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/getdummies_method .PNG) 

•	Create the target variables:


![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/set_target.PNG)


![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/balance_target_var.PNG)


![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/update_target_var.PNG)


## Resampling training data:

•	Logistic Regression Classifier:

![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/logisticregression_randomoversampler.PNG)


•	Balanced Accuracy Score:

![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/accuracy_score_logistic.PNG)

•	Confusion Matrix:

![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/confusion_matrix_logistic.PNG)

•	Classification Report:

![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/mainResources/classification_report_logistic.PNG)

## Smote Oversampling:

•	Logistic Regression Classifier:


![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/logisticregression_smote.PNG)

•	Balanced Accuracy Score:


![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/logisticregression_smote.PNG)

•	Confusion Matrix:


![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/logisticregression_smote.PNG)

•	Classification Report:


![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/classification_report_logistic.PNG)

## Undersampling:

•	ClusterCentroids resampler:


![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/clustercentriods_undersampling.PNG)

•	Logistic Regression:


![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/mainResources/logisticregression_undersampling.PNG)

•	Balanced Accuracy Score:


![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/accuracy_score_undersampling.PNG)

•	Confusion Matrix:


![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/confusion_matrix_undersampling.PNG)

•	Classification Report:


![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/classification_report_undersampling.PNG)


2.	## Use the SMOTEENN algorithm to Predict Credit Risk

•	Smoteen Model:


![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/smoteen_model.PNG)

•	Logistic Regression:

![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/logisticregression_smoteen.PNG)

•	Balanced Accuracy Score:

![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/accuracy_score_smoteen.PNG)

•	Confusion Matrix:

![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/confusion_matrix_smoteen.PNG)

•	Classification Report:


![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/classification_report_smoteen.PNG)


3.	## Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

•	Balanced Accuracy Score:


•	![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/accuracy_score_randomforest.PNG)

•	Confusion Matrix:


![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/confusion_matrix_randomforest.PNG)

•	Classification Report:


![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/classification_randomforest.PNG)

•	The features are sorted in descending order by feature importance:


•	![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/sorted_features_randomforest.PNG)

### Easy Ensemble Classifier

•	Balanced Accuracy Score:


![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/accuracy_score_easyensemble.PNG)

•	Confusion Matrix:

![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/confusion_matrix_easyensemble.PNG)

•	Classification Report:

![alttext](https://github.com/mbehr11/Credit_Risk_Analysis/blob/main/Resources/classification_easyensemble.PNG)

## Contributing 
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)

