# Automobile Insurance Fraud Claim Detection Using Machine Learning: A Comparative Approach

## Overview

Insurance fraud is one of the major challenges faced by the automobile insurance industry, leading to significant financial losses every year. This project presents a machine learning-based comparative analysis for detecting fraudulent automobile insurance claims using multiple classification algorithms and imbalance handling techniques.

The study evaluates the performance of:

- Support Vector Machine (SVM)
- Random Forest (RF)
- K-Nearest Neighbors (KNN)

along with oversampling techniques such as:

- SMOTE
- ADASYN

The objective is to identify the most effective approach for handling highly imbalanced fraud datasets.

---

## Dataset

The dataset used is the **Car Insurance Claims Dataset (carclaims)** obtained from Kaggle.

### Dataset Details

- Total Samples: 15,420
- Legitimate Claims: 14,497
- Fraudulent Claims: 923
- Highly imbalanced classification problem

Dataset Source:
https://www.kaggle.com/datasets/khusheekapoor/vehicle-insurance-fraud-detection

---

## Features of the Project

- Data preprocessing
- Handling missing values
- One-hot encoding
- Feature importance analysis
- Feature selection
- Hyperparameter tuning
- Comparative model evaluation
- Class imbalance handling
- Confusion matrix visualization
- Fraud recall comparison

---

## Technologies Used

| Category | Libraries |
|---|---|
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Imbalanced Learning | SMOTE, ADASYN |
| Hyperparameter Tuning | RandomizedSearchCV |
| Development Environment | Google Colab  |

---

## Machine Learning Models

### 1. Support Vector Machine (SVM)
- RBF Kernel
- Hyperparameter tuning using RandomizedSearchCV

### 2. Random Forest
- Ensemble learning approach
- Feature importance extraction
- Balanced class weighting

### 3. K-Nearest Neighbors (KNN)
- Distance-based classification
- Feature scaling applied

---

## Handling Class Imbalance

Since the dataset is highly imbalanced, the following oversampling methods were applied:

### SMOTE
Synthetic Minority Oversampling Technique creates synthetic fraud samples to improve learning.

### ADASYN
Adaptive Synthetic Sampling focuses more on difficult fraud samples.

---

## Workflow

1. Dataset loading
2. Exploratory Data Analysis (EDA)
3. Data preprocessing
4. Feature encoding
5. Feature importance selection
6. Train-test split
7. Feature scaling
8. Model training
9. Hyperparameter tuning
10. Model evaluation
11. Comparison of balancing techniques

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC

Special importance was given to fraud recall due to the class imbalance problem.

---

## Results

The comparative analysis showed that balancing techniques significantly improved fraud detection performance.

- Random Forest achieved strong overall performance.
- ADASYN improved fraud recall for KNN.
- SMOTE and ADASYN both helped reduce bias toward the majority class.


---

## Future Improvements

- Deep learning-based fraud detection
- Real-time fraud prediction system
- Web deployment using Flask/Streamlit
- Ensemble stacking methods

---

## Author

Nivetha N

---

## License

This project is licensed under the MIT License.
