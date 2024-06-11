# Decision Tree Classification

## Overview

This project involved implementing decision tree algorithms for classification tasks on two datasets: Iris and Spambase. The goal was to accurately predict the class labels (species of Iris flowers or spam/non-spam emails) given the input features. Key achievements include:

- Developed an efficient decision tree algorithm with binary splits and information gain as the splitting criterion
- Implemented an early stopping strategy based on a minimum number of instances at leaf nodes
- Conducted comprehensive experiments with 10-fold cross-validation on both datasets
- Achieved high classification accuracies, demonstrating the effectiveness of the decision tree model

## Datasets

### Iris Dataset

- 3 classes: 3 different species of Iris flowers
- 4 numerical features: sepal length, sepal width, petal length, petal width
- 150 instances, 50 per class

### Spambase Dataset

- Binary classification: spam or non-spam emails
- Approximately 4,600 instances

## Methodology

The decision tree algorithm was implemented with the following key features:

- **Binary Splits**: Continuous features were split into two branches based on a threshold value.
- **Information Gain**: Node impurity was measured using information gain, and the feature-threshold combination with the highest information gain was chosen for splitting.
- **Early Stopping**: To prevent overfitting, a minimum number of instances (nmin) at leaf nodes was used as a stopping criterion. Different values of nmin were tested for each dataset.

## Results Sample

The decision tree model achieved strong classification performance on both datasets, as summarized below:

### Spambase Dataset

Results for nmin=10

| Fold |Accuracy      |
|----|----------------|
|1  |  92.39%        |
|2  |  91.30%        |
|...| |
|10 |  91.96%        |
--------------------
Average accuracy: 90.76%
Standard deviation: 1.54%

## Conclusion

This project demonstrated the effectiveness of decision tree algorithms for classification tasks on numerical datasets. By implementing an efficient algorithm with binary splits, information gain splitting criterion, and early stopping, high classification accuracies were achieved on both the Iris and Spambase datasets. The results showcase the potential of decision trees as a powerful tool for predictive modeling and decision-making tasks.