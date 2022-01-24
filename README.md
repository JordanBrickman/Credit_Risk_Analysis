# Credit_Risk_Analysis


## Overview of the loan prediction risk analysis:
We have been tasked to evaluate credit risk using different techniques (over and under sampling, and methods of classification) with imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.


## Results:
High Risk Data using the 6 methods. 
- RandomOverSampler: 66.0% accuracy, 1% precision, 62% recall.
- SMOTE: 66% accuracy, 1% precision, 62% recall.
- ClusterCentroids: 54% accuracy, 1% precision, 67% recall.
- SMOTEENN: 64% accuracy, 1% precision, 70% recall.
- BalancedRandomForestClassifer: 78.9% accuracy, 3% precision, 70% recall.
- EasyEnsembleClassifer: 93.2% accuracy, 9% precision, 92% recall.  


## Summary:
Each method results in varying results, however the dataset is skewed more towards low risk. Using a different dataset would likley show more variance in methods. 
Using a comination over/under sampling would typically be a way to take the advantages of both Over and Under sampling, however, the reviewed must also be aware of teh drawbacks of each, since those issues remain. 
