# Credit Risk Analysis

## Purpose

In this project, we were tasked with utilizing supervised machine learning tools to compare whether or not users will be a credit risk in the future. We accomplished laying the groundwork for further machine learning operations on the data. We trained and tested our data utilizing a number of different machine learning models. By using RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier, and EasyEnsembleClassifier we set up models that are prepared to take in more data that will help our client better recognize risk from potential lendees.

## Results

The following are the outputs that show the efficacy of different machine learning models utilized on the data

### - RandomOverSampler

![oversampling](https://user-images.githubusercontent.com/85508764/136703287-6262f3e1-7f5b-4c47-9191-8a981c23f9c0.png)


### - SMOTE

![smote](https://user-images.githubusercontent.com/85508764/136703311-5f7e4226-906f-436d-8724-f1a4f1286f95.png)


### - Undersampling

![undersampling](https://user-images.githubusercontent.com/85508764/136703326-afddad63-f788-414a-b2de-09f09af3a38e.png)


### - SMOTEENN

![smoteenn](https://user-images.githubusercontent.com/85508764/136703331-6399bc86-381a-45c6-9cbc-127485d74767.png)


###  - BalancedRandomForestClassifier

![Balanced_Rand_Forest](https://user-images.githubusercontent.com/85508764/136703333-215c438f-080f-438c-a2c9-2eff147c4213.png)

  - Feature Importance from RandomForestClassifier
    ![FeatureImportance](https://user-images.githubusercontent.com/85508764/136703340-8a89a1b0-55f2-43e9-a33c-2732fa5ac70e.png)

### - EasyEnsembleClassifier

![ensemble](https://user-images.githubusercontent.com/85508764/136703348-5391b433-6d4f-4bac-b15e-2f8633654ca9.png)


## Summary

Based solely on these outputs, we can see that the EasyEnsembleClassifier is the most accurate of all of these tests. However, due to the large number of features this number starts to become a little less meaningful. Therefore, I would recommend one of the random sampling methods, namely SMOTEEN as it provides a balance of different methods of sampling to give a more balanced look at the data.
