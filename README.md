# Heart Disease Naive Bayes

This is a beginner-friendly machine learning project where I used Gaussian Naive Bayes to predict heart disease from a medical dataset.

The main goal was to practice a simple classification workflow: checking the data, doing basic EDA, splitting the data, training a Naive Bayes model, making predictions, and evaluating the result.

## What This Notebook Covers

- Loading and checking the heart disease dataset
- Null value check
- Target distribution check
- Basic EDA plots
- Correlation heatmap
- Train/test split
- Gaussian Naive Bayes model training
- Model evaluation using accuracy, precision, recall, F1-score, and classification report
- Confusion matrix print and plot
- Final result table

## Files

- `heart_disease_naive_bayes_project.ipynb` - final cleaned notebook
- `heart.csv` - dataset used in the notebook

## Dataset

The dataset contains medical features related to heart disease prediction. The target column is `target`:

- `1` means heart disease is present
- `0` means heart disease is not present

## Results

The Gaussian Naive Bayes model performed well on the test data.

| Model | Accuracy | Precision | Recall | F1 Score |
| --- | ---: | ---: | ---: | ---: |
| Gaussian Naive Bayes | 86.89% | 90.00% | 84.38% | 87.10% |

## Main Learning

This project helped me understand how Naive Bayes can be used for binary classification. The focus was on keeping the workflow simple and clear: load data, split data, train the model, predict values, and evaluate the model.
