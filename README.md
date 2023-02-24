# Credit_Risk_Analysis
## Purpose
The give task is simple, run some machine learning algorithms and see which had the more percise and accurate measures for low and high risk loans based on credit. There were 6 that were tested for this task. These were split up between the resampled and ensembled machine learning algorithms. There were 4 resampled algorithms and 2 ensembled algorithms.

## Results
They were all percise on low risk credit evalution. They were all very inpercise with high risk cedit below 10% of the time. The difference comes in with the Recall column when evaluting the different machine learning algorithms.
### Resampling
- Random Oversampling

![Naive_Random_Oversampling_data](https://user-images.githubusercontent.com/114030563/220469446-324a2365-7d25-4709-89a4-048e647f7518.png)

- SMOTE Oversampling

![SMOTE_Oversampling_data](https://user-images.githubusercontent.com/114030563/220469753-7e3029d3-31a4-4caf-b011-3ab3623ee0ed.png)

- Undersampling

![Undersampling_data](https://user-images.githubusercontent.com/114030563/220469668-d4a04390-987b-4655-a929-90dffb7aef09.png)

This has one of the lowest recalls for low risk samplings and has the lowest F1 in both categories.

- Combination (Over and Under) Sampling

![Combination_sampling_data](https://user-images.githubusercontent.com/114030563/220469698-0019fc32-4353-4ce3-b7be-814b180f7e8d.png)

### Ensemble
- Balanced Random Forest Classifier (BRFC)

![Balanced_Random_Forest_Classifier_data](https://user-images.githubusercontent.com/114030563/220469625-a82ff7cd-1c5c-4d50-9359-1a3d5789ab40.png)

This is the second highest recall. This means that it has a very good percision on a what are true positives. 

- Easy Ensemble AdaBoost Classifier (EEC)

![Easy_Ensemble_data](https://user-images.githubusercontent.com/114030563/220469542-ec7a29b9-f05a-4076-9944-ac27bb8aa5e3.png)

Easy Ensemble with the AdaBoost Classifier has the highest recall out of all the other machine learning algorithms. This helps with the F1 column when we calculate it.

## Summary
I would only recommend the Ensemble algorithms for evaluting the credit risk because of how it was able to get true positives and get the best overall F1 scores. Although they are all needed to be desired with the percision on high credit risk, the high recall of the two Ensemble algorithms is very promising. I would still try to find a better algorithm to get more percision.
