# Supervised Machine Learing and Credit Risk

## Background

Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

## Technology
- Machine Learning
- Python and Scikit-learn
- Data Source: [LoanStats_2019Q1](https://github.com/SoonaBritney/Supervised_Machine_Learning_and_Credit_Risk/blob/main/LoanStats_2019Q1.zip)

## Deliverable 1 Requirements
[credit_risk_resampling.ipynb](https://github.com/SoonaBritney/Supervised_Machine_Learning_and_Credit_Risk/blob/main/credit_risk_resampling.ipynb)

- For all three algorithms, the following have been completed:
- An accuracy score for the model is calculated (7.5 pt)
- A confusion matrix has been generated (7.5 pt)
- An imbalanced classification report has been generated (15 pt)

## Deliverable 2 Requirements
[credit_risk_resampling.ipynb](https://github.com/SoonaBritney/Supervised_Machine_Learning_and_Credit_Risk/blob/main/credit_risk_resampling.ipynb)

The combinatorial SMOTEENN algorithm does the following:
- An accuracy score for the model is calculated (5 pt)
- A confusion matrix has been generated (5 pt)
- An imbalanced classification report has been generated (5 pt)


## Deliverable 3 Requirements
[credit_risk_ensemble.ipynb](https://github.com/SoonaBritney/Supervised_Machine_Learning_and_Credit_Risk/blob/main/credit_risk_ensemble.ipynb)

The BalancedRandomForestClassifier algorithm does the following:
- An accuracy score for the model is calculated (2.5 pt)
- A confusion matrix has been generated (2.5 pt)
- An imbalanced classification report has been generated (5 pt)
- The features are sorted in descending order by feature importance (5 pt)
The EasyEnsembleClassifier algorithm does the following:
- An accuracy score of the model is calculated (2.5 pt)
- A confusion matrix has been generated (2.5 pt)
- An imbalanced classification report has been generated (5 pt)

## Deliverable 4: Written Report on the Credit Risk Analysis (30 points)

- Overview of the analysis: Explain the purpose of this analysis.
- Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.
- Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

## Challenge Summary
[credit_risk_resampling.ipynb](https://github.com/SoonaBritney/Supervised_Machine_Learning_and_Credit_Risk/blob/main/credit_risk_resampling.ipynb)

We used the imbalanced-learn library to resample the data and built and evaluated logistic regression classifiers using the resampled data.

1) Oversample the data using the RandomOverSampler and SMOTE algorithms.
2) Undersample the data using the cluster centroids algorithm.
3) Use a combination approach with the SMOTEENN algorithm.
4) For each of the above:
- Train a logistic regression classifier (from Scikit-learn) using the resampled data.
- Calculate the balanced accuracy score using balanced_accuracy_score from sklearn.metrics.
- Generate a confusion_matrix.
- Print the classification report (classification_report_imbalanced from imblearn.metrics).
- We wrote a brief summary and analysis of the models’ performance. In the analysis, we described the precision and recall scores, as well as the balanced accuracy score. We, ---also, included a final recommendation on the model to use, if any. If we did not recommend any of the models, we justified our reasoning.

**Extension**

[credit_risk_ensemble.ipynb](https://github.com/SoonaBritney/Supervised_Machine_Learning_and_Credit_Risk/blob/main/credit_risk_ensemble.ipynb)

For the extension, we trained and compared two different ensemble classifiers to predict loan risk and evaluated each model.

1) Train the model and generate predictions.**
2) Calculate the balanced accuracy score.
3) Generate a confusion matrix.
4) Print the classification report (classification_report_imbalanced from imblearn.metrics).
5) For the BalancedRandomForestClassifier, print the feature importance, sorted in descending order (from most to least important feature), along with the feature score.

Lastly, we wrote a brief summary and analysis of the models’ performance, described the precision and recall scores, as well as the balanced accuracy score. Additionally, we included a final recommendation on the model to use, if any. If we did not recommend any of the models, we justified our reasoning.
