# Software-Reliability-Prediction
Working to improve previous works on Software-Reliability-Prediction-Using-Ensemble-Learning.

Tests till now:
1. Tested lazypredict library for considering multiple algorithms on the dataset
2. Checked Report 1 and 2 for procedures they followed. K fold and interpolation found.
3. Dimentions checked for reduction, only column P had too low correlation. Removed P.
4. Found matrix of 26 algorithms with 4 metric scores.
5. Tried K fold technique for testing the dataset for different model but this functionality is not in library.

Current Approach: 
1. Checking alternative approach for K fold cross validation. K fold with value 10 is mentioned in the report.
2. Checking our top 5 libraries performing in each score for K folds seperately.

Maximum Accuracy till now: 0.86
(LGBMClassifier, ExtraTreesClassifier, RandomForestClassifier, RidgeClassifier, SVC)

Maximum balanced accuracy till now: 0.71
(BernoulliNB)

Maximum ROC AUC score: 0.71 (BernoulliNB)

Maximum F1 score: 0.85 (LGBMClassifier)
