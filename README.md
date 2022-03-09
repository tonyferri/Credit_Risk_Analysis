# Credit Risk Analysis
Module 17 Challenge

## Overview of the Analysis:
The purpose of this analysis is to use different machine learning techniques to determine credit card risk.

## Results:
* Random Oversampling
  * Balanced Accuracy = 0.6285
  * Precision (Ave) = 0.99
  * Recall (Ave) = 0.66

* SMOTE Oversampling
  * Balanced Accuracy = 0.6303
  * Precision (Ave) = 0.99
  * Recall (Ave) = 0.64

* Undersampling
  * Balanced Accuracy = 0.5160
  * Precision (Ave) = 0.99
  * Recall (Ave) = 0.44

* SMOTEENN (Combination)
  * Balanced Accuracy = 0.6376
  * Precision (Ave) = 0.99
  * Recall (Ave) = 0.57

* Random Forest
  * Balanced Accuracy = 0.6721
  * Precision (Ave) = 1.00
  * Recall (Ave) = 1.00

* Easy Ensemble
  * Balanced Accuracy = 0.9255
  * Precision (Ave) = 0.99
  * Recall (Ave) = 0.94

## Summary:
Taking into account all three measurables, my recommendation would be to use the Easy Ensemble technique to evaluate risk in this case. This technique showed the highest balanced accuracy (0.9255) while still having high precision and recall.

## Pics:

### Ranking - Balanced Random Forest
![Ranking - Balanced Random Forest](https://github.com/tonyferri/Credit_Risk_Analysis/blob/main/resources/Ranking%20-%20Balanced%20Random%20Forest.png)

### Summary - Balanced Random Forest
![Summary - Balanced Random Forest](https://github.com/tonyferri/Credit_Risk_Analysis/blob/main/resources/Summary%20-%20Balanced%20Random%20Forest.png)

### Summary - Easy Ensemble
![Summary - Easy Ensemble](https://github.com/tonyferri/Credit_Risk_Analysis/blob/main/resources/Summary%20-%20Easy%20Ensemble.png)

### Summary - Random Oversampling
![Summary - Random Oversampling](https://github.com/tonyferri/Credit_Risk_Analysis/blob/main/resources/Summary%20-%20Random%20Oversampling.png)

### Summary - SMOTE Oversampling
![Summary - SMOTE Oversampling](https://github.com/tonyferri/Credit_Risk_Analysis/blob/main/resources/Summary%20-%20SMOTE%20Oversampling.png)

### Summary - SMOTEENN (Combination)
![Summary - SMOTEENN (Combination)](https://github.com/tonyferri/Credit_Risk_Analysis/blob/main/resources/Summary%20-%20SMOTEENN%20(Combination).png)

### Summary - Undersampling
![Summary - Undersampling](https://github.com/tonyferri/Credit_Risk_Analysis/blob/main/resources/Summary%20-%20Undersampling.png)