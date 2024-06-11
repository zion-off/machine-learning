# SVM for Classification

## Overview
This project exemplifies the application of Support Vector Machine (SVM) for classification tasks, using a synthetic dataset generated with Scikit Learn. The project highlights the implementation of a soft margin SVM and demonstrates proficiency in optimizing the SVM model using mini-batch gradient descent.

## Dataset
The dataset is synthetically generated using Scikit Learn's `make_classification` function, providing a robust basis for testing the SVM model. The generated dataset includes:
- **Samples**: 500
- **Features**: 3 (all informative, no redundancy)
- **Clusters per Class**: 1
- **Noise**: 10% noise added to the labels
- **Class Separation**: Moderate (class_sep=1.0)

```python
from sklearn.datasets import make_classification

X, y = make_classification(n_samples=500, n_features=3, n_informative=3,
                           n_redundant=0, n_clusters_per_class=1,
                           flip_y=0.1, class_sep=1.0, random_state=40)
```

## Achievements

**Data Preparation and Preprocessing**

Successfully relabeled the target values to +1 and -1, preparing the dataset for SVM classification.
Effectively split the dataset into training and testing sets, ensuring reliable performance evaluation.

**Soft Margin SVM Implementation**

1. Implemented a robust soft margin SVM from scratch, showcasing deep understanding of SVM mechanics.
2. Utilized mini-batch gradient descent to efficiently minimize the loss function, optimizing the model's weights.

**Model Optimization and Evaluation**

1. Achieved optimal weights through meticulous minimization of the loss function.
2. Performed accurate predictions on the test data, demonstrating the model's practical applicability.
3. Calculated a high accuracy score, reflecting the model's precision and reliability.

**Data Visualization**

1. Created insightful 3D visualizations of the training data and the decision boundary, enhancing interpretability.
2. Visualized the loss function's progression over time, providing clear evidence of the model's optimization process.

## Instructions for Running the Project

1. Ensure the required libraries (numpy, scikit-learn, matplotlib, etc.) are installed.
2. Execute the notebook or script in a Python environment to replicate the results.
3. The script will handle data generation, model training, evaluation, and visualization.
4. Detailed comments and explanations are included within the code to guide you through each step.