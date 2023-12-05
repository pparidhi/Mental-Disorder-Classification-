# Mental_Disorder_Classification

## Overview

Major Depressive Disorder (MDD) and Bipolar Disorder (BD) are prevalent mental health conditions affecting millions worldwide. Accurate diagnosis poses a significant challenge due to shared symptoms and diagnostic criteria. Misdiagnosis, particularly mistaking BD for MDD, is common, leading to delayed recognition of BD. This project addresses the need for precise diagnosis by exploring Electroencephalography (EEG) signals as potential biomarkers and employs machine learning techniques for classification.

## Problem Statement

Distinguishing between MDD and BD is crucial for effective treatment, yet conventional methods relying on questionnaires and psychiatric evaluations are subjective and prone to errors. This project aims to identify quantitative biomarkers using EEG signals, specifically focusing on 71 MDD and 71 BD patients. Symbolic Transfer Entropy (STE) is employed for feature extraction—a robust measure of information flow between different brain regions.

## Data Set
Database has 142 rows and 46 columns. 

The first 71 rows belong to the patients with bipolar disorder (BD) and the remaining 71 rows belong to the patients with major depressive disorder (MDD). The first 45 columns are the features, and the last column is the label of the patients (1 for BD and 2 for MDD). 
File BP-MDD attached is the database file.


## Methodology

1. **Feature Extraction:** Symbolic Transfer Entropy (STE)
2. **Dataset:** 71 MDD and 71 BD patients
3. **Classifiers:** Naïve Bayes, Decision Tree, Random Forest, Linear Discriminant Analysis, and Quadratic Discriminant Analysis
4. **Evaluation:** 5-fold cross-validation, varying the number of features from one to 45

## Results

The project involves running the cross-validation code 100 times for each set of features, calculating mean ± standard deviation of sensitivity, specificity, total accuracy, precision, F1-score, and AUC for each class. The change in mean values for each parameter is plotted against the number of features. The maximum accuracy and corresponding metrics for each classifier are reported in a table.

## Performance Metrics

- Sensitivity
- Specificity
- Total Accuracy
- Precision
- F1-score
- Area Under the Curve (AUC)

## Conclusion

This comprehensive analysis aims to determine the optimal set of features and classifier for accurate MDD and BD classification. The results provide valuable insights into the potential of EEG signals as biomarkers and the effectiveness of different classifiers in distinguishing between these mental disorders.

Researchers, clinicians, and data scientists interested in mental health diagnostics, EEG-based biomarkers, and machine learning classification will find this project insightful and applicable to future studies.
