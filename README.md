# Credit_Risk_Analysis
## Overview:
  The purpose of this analysis was to learn and apply machine learning to make predictions based on a dataset. In this dataset, we analyzed data from FastLending to assess the credit risk of loan applicants. To find out which machine learning is the most accurate, six different types of machine learning were used. The types used were Naive Random Oversampling, SMOTE Oversampling, Cluster Centroids, SMOTEENN, Balanced Random Forest Classifier, and Easy Ensemble AdaBoost Classifier.
 
## Results
After organizing the dataframe to only show current applicants the dataframe was then restructured to only show applicants under two categories: High risk and low risk. This returned a total of 68,817 applications with a breakdown as follows:

![totals](https://github.com/JTGonzaga/Credit_Risk_Analysis/blob/main/Analysis/sample_numbers.png)

This datafram was then ran through the six different types of machine learning to determine balanced accuracy scores and the presision and recall scores. The results are as follows:

### Naive Random Oversampling

![nro_balance](https://github.com/JTGonzaga/Credit_Risk_Analysis/blob/main/Analysis/nro_balance.png)
![nro_class](https://github.com/JTGonzaga/Credit_Risk_Analysis/blob/main/Analysis/nro_class.png)

- The balanced accuracy score is 64.9%
- High risk applications had a precision score of 1% and a recall score of 62%
- Low risk applications had a precisoin score of 100% and a recall score of 68%

### SMOTE Oversampling

![smote_balance](https://github.com/JTGonzaga/Credit_Risk_Analysis/blob/main/Analysis/smote_balance.png)
![smote_class](https://github.com/JTGonzaga/Credit_Risk_Analysis/blob/main/Analysis/smote_class.png)

- The balanced accuracy score is 64.4%
- High risk applications had a precision score of 1% and a recall score of 63%
- Low risk applications had a precision score of 100% and a recall score of 66% 
### Cluster Centroid Undersampling

![cc_balance](https://github.com/JTGonzaga/Credit_Risk_Analysis/blob/main/Analysis/cc_balance.png)
![cc_class](https://github.com/JTGonzaga/Credit_Risk_Analysis/blob/main/Analysis/cc_class.png)

- The balanced accuracy score is 64.4%
- High Risk applications had a precision score of 1% and a recall score of 61%
- Low risk applications had a precision score of 100% and a recall score of 45%
### SMOTEENN 

![smoteenn_balance](https://github.com/JTGonzaga/Credit_Risk_Analysis/blob/main/Analysis/smoteenn_balance.png)
![smoteen_class](https://github.com/JTGonzaga/Credit_Risk_Analysis/blob/main/Analysis/smoteenn_class.png)

- The balanced accuracy score was 52.9%
- High Risk applications had a precision score of 1% and a recall score of 71%
- Low risk applications had a precision score of 100% and a recall score of 56%


### Balanced Random Forest Classifier

![brf_balance](https://github.com/JTGonzaga/Credit_Risk_Analysis/blob/main/Analysis/brf_balance.png)
![brf_class](https://github.com/JTGonzaga/Credit_Risk_Analysis/blob/main/Analysis/brf_class.png)

- The balanced accuracy score was 78.7%
- High risk applications had a precision score of 4% and a recall score of 67%
- Low risk applications had a precision score of 100% and a recall score of 91%

### Easy Ensemble AdaBoost Classifier

![eec_balance](https://github.com/JTGonzaga/Credit_Risk_Analysis/blob/main/Analysis/eec_balance.png)
![eec_class](https://github.com/JTGonzaga/Credit_Risk_Analysis/blob/main/Analysis/eec_class.png)

- The balanced accuracy score was 92.5%
- High risk applications had a precision score of 7% and a recall score of 91%
- Low risk applications had a precision score of 100% and a recall score of 94%

## Summary
Out of the six models used, ensemble models were by far the most accurate and precise. The Easy Ensemble Classifier had recall score of 91% which means it was 91% successful at recognizing high risk applications. It was also good at recognizing low risk applications with a recall score of 94%. Out of these 6 models, I would suggest that Fast Leding use the Easy Ensemble Classifier as it was the most successful at identifying both high and low risk applications. 
