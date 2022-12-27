# Software-Reliability-Prediction-Research
### Working to improve previous works on Software-Reliability-Prediction-Using-Ensemble-Learning.
Reliability Testing is a testing technique that relates to test the ability of a software to function and given environmental conditions that helps in uncovering issues in the software design and functionality. It is defined as a type of software testing that determines whether the software can perform a failure free operation for a specific period of time in a specific environment. It ensures that the product is fault free and is reliable for its intended purpose.

## Tests till now:
1. Tested lazypredict library for considering multiple algorithms on the dataset
2. Checked Report 1 and 2 for procedures they followed. K fold and interpolation found.
3. Dimentions checked for reduction, only column P had too low correlation. Removed P.
4. Found matrix of 26 algorithms with 4 metric scores.
5. Tried K fold technique for testing the dataset for different model but this functionality is not in library.

## Current Approach
1. Checking alternative approach for K fold cross validation. K fold with value 10 is mentioned in the report.
2. Checking our top 5 libraries performing in each score for K folds seperately.

## Metric Scores:
- Maximum Accuracy till now: 0.86
(LGBMClassifier, ExtraTreesClassifier, RandomForestClassifier, RidgeClassifier, SVC)

- Maximum balanced accuracy till now: 0.71
(BernoulliNB)

- Maximum ROC AUC score: 0.71 (BernoulliNB)

- Maximum F1 score: 0.85 (LGBMClassifier)



## References
#### Repository consulted: [Software-Reliability-Prediction-Using-Ensemble-Learning](https://github.com/SarthakSahoo/Software-Reliability-Prediction-Using-Ensemble-Learning)
