# Credit_Risk_Analysis

## Overview of the analysis
In this project. I applied machine learning to evaluate credit card risk. However, Credit card risk is unbalanced. Therefore, I used six different techniques to train and evaluate models using imbalanced-learn and scikit-learn libraries. 

I oversampled the data using the RandomOverSampler and SMOTE, undersampled the data using the ClusterCentroids aalgorithm. I then combined over and undersampling using the SMOTEENN algorithm. Then I compared these two to the BalancedRandomForestClassifier and EasyEnsembleClassifier. 

## Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### RandomOverSampler

- Balanced accuracy score: .640. This means that the model is correct 64.0% of the time. 

- Precision: .99. This means that the algorithm is 99% reliable in prediciting positive classifications.

- Recall: .62. This means that of the positive outcomes, the algorithm correctly classified them as positive 62% of the time.

### SMOTE
- Balanced accuracy score: .651. This means that the model is correct 65.1% of the time. 

- Precision: .99. This means that the algorithm is 99% reliable in prediciting positive classifications. 

- Recall: .69. This means that of the positive outcomes, the algorithm correctly classified them as positive 69% of the time.

### ClusterCentroids
- Balanced accuracy score: .640. This means that the model is correct 64.0% of the time. 

- Precision: .99. This means that the algorithm is 99% reliable in prediciting positive classifications. 

- Recall: .62. This means that of the positive outcomes, the algorithm correctly classified them as positive 62% of the time.

### SMOTEENN 
- Balanced accuracy score: .645. This means that the model is correct 64.5% of the time. 

- Precision: .99. This means that the algorithm is 99% reliable in prediciting positive classifications. 

- Recall: .57. This means that of the positive outcomes, the algorithm correctly classified them as positive 57% of the time.

### BalancedRandomForestClassifier
- Balanced accuracy score: .789. This means that the model is correct 78.9% of the time. 

- Precision: .99. This means that the algorithm is 99% reliable in prediciting positive classifications. 

- Recall: .87. This means that of the positive outcomes, the algorithm correctly classified them as positive 87% of the time.

### EasyEnsembleClassifier
- Balanced accuracy score: .932. This means that the model is correct 93.2% of the time. 

- Precision: .99. This means that the algorithm is 99% reliable in prediciting positive classifications. 

- Recall: .94. This means that of the positive outcomes, the algorithm correctly classified them as positive 94% of the time.

Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
