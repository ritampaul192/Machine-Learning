# Social Network Ad Purchase Prediction (K-NN Classification)

## Overview
This project focuses on predicting whether a user will purchase a product after seeing a social network advertisement. The problem is a **binary classification** task that uses user demographic and financial data to predict the outcome.

## Dataset
- **`Social_Network_Ads.csv`**: The dataset contains $400$ records with the following key features:
    - `Gender`
    - `Age`
    - `EstimatedSalary`
    - `Purchased` (Target Variable: $0$ for No, $1$ for Yes)

## Methodology
The classification model was developed in the provided Jupyter notebook (`DAY_7.ipynb`).

### Key Steps:
1.  **Data Preprocessing**:
    * **Label Encoding** was applied to the `Gender` feature to convert it to a numerical format.
    * **Feature Scaling** was performed on the numerical features (`Age` and `EstimatedSalary`) using `StandardScaler` to standardize the input data.
2.  **Model Training**: A **K-Nearest Neighbors (K-NN)** classifier was trained on the preprocessed data.
3.  **Evaluation**: Model performance was assessed using a **Confusion Matrix** and **Accuracy Score**.

## Files
-   **`Social_Network_Ads.csv`**: The raw dataset used for the project.
-   **`DAY_7.ipynb`**: Jupyter notebook containing the full workflow, including data preprocessing, K-NN model training, and performance evaluation.
