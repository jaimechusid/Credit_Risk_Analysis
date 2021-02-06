# Credit Risk Analysis

## Project Overview
In this project, we were tasked with creating multiple different machine learning models with the goal to better predict credit risk of loans. Using Pandas along with several machine learning and sampling libraries, I was able to test out many machine learning techniques to figure out which models yields the highest accuracy. 

## Machine Learning Analysis
Below is a summary of the 6 machine learning models, including their balanced accuracy scores, and precision and recall of having high credit risk.
1. Random Over Sampler
- Accuracy: 0.66
- Precision: 0.01
- Recall: 0.67

2. SMOTE 
- Accuracy: 0.61
- Precision: 0.01
- Recall: 0.57

3. Cluster Centroids
- Accuracy: 0.52
- Precision: 0.01
- Recall: 0.63

4. SMOTEENN
- Accuracy: 0.64
- Precision: 0.01
- Recall: 0.71

5. Balanced Random Forest
- Accuracy: 0.82
- Precision: 0.02
- Recall: 0.54

6. Easy Ensemble
- Accuracy: 0.94
- Precision: 0.08
- Recall: 0.91

## Summary
All of the machine learning models used to predict credit loans yielded decent accuracy and recall, but very low precision. Out of the different models, I would recommend using the Easy Ensemble because it had the highest accuracy and precision. This model is also one of the ensemble learning models, which I would recommend over oversampling or undersampling. Balanced Random Forest is also a good option because it also yielded high accuracy and recall as well.
