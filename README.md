# Iris Classification using Logistic Regression, Naive Bayes, and KNN

## Overview

This project Shows the implementation and comparison of three popular machine learning classification algorithms:

* Logistic Regression
* Gaussian Naive Bayes
* K-Nearest Neighbors (KNN)

The models are trained and evaluated on the Iris dataset to classify iris flowers into three species based on their physical characteristics.

---

## Dataset

The project uses the Iris dataset containing 150 samples of iris flowers.

### Features

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

### Target Classes

* Iris Setosa
* Iris Versicolor
* Iris Virginica

---

## Project Workflow

1. Load the Iris dataset
2. Perform data preprocessing
3. Check for missing and duplicate values
4. Encode categorical target labels
5. Split the dataset into training and testing sets
6. Train multiple classification models
7. Evaluate model performance using:

   * Accuracy Score
   * Confusion Matrix
   * Classification Report
8. Compare the results of all models

---

## Algorithms Used

### Logistic Regression

A statistical classification algorithm that predicts class probabilities using a logistic function.

### Gaussian Naive Bayes

A probabilistic classifier based on Bayes' theorem with the assumption of feature independence.

### K-Nearest Neighbors (KNN)

A distance-based algorithm that classifies a sample based on the majority class among its nearest neighbors.

---

## Libraries Used

```python
pandas
numpy
scikit-learn
matplotlib
seaborn
```

Install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

---

## Model Performance

### Logistic Regression

* Accuracy: 100%
* Precision: 1.00
* Recall: 1.00
* F1-Score: 1.00

### Gaussian Naive Bayes

* Accuracy: 100%
* Precision: 1.00
* Recall: 1.00
* F1-Score: 1.00

### K-Nearest Neighbors (KNN)

* Accuracy: 100%
* Precision: 1.00
* Recall: 1.00
* F1-Score: 1.00

---

## Confusion Matrix

```
[[10  0  0]
 [ 0  9  0]
 [ 0  0 11]]
```

All test samples were correctly classified with no misclassifications.

---

## Results Summary

| Model                | Accuracy |
| -------------------- | -------- |
| Logistic Regression  | 100%     |
| Gaussian Naive Bayes | 100%     |
| KNN                  | 100%     |

All three models achieved perfect classification performance on the test dataset.

---

## How to Run

Clone the repository:

```bash
https://github.com/Sujan-Adhikari875/Iris-Classification.git
```

Navigate to the project directory:

```bash
cd Transforming
```

Launch Jupyter Lab:

```bash
jupyter lab
```

Open:

```bash
Assignment_Problem.ipynb
```

Run all cells to reproduce the results.

---

## Future Improvements

* Feature Scaling for KNN
* Cross-Validation
* Hyperparameter Tuning
* Visualization of Decision Boundaries
* Comparison with additional classification algorithms

---

## Author

Adhikari Sujan

Machine Learning | Data Science 
