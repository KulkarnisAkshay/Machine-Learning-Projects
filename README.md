# Machine-Learning-Projects
## 1. Holiday Package Purchase Prediction

## Project Overview

This project aims to predict which customers are most likely to purchase a holiday package offered by "Trips & Travel.Com". By leveraging historical customer data, the goal is to improve the efficiency of marketing campaigns for a new "Wellness Tourism Package".

## Data

The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/susant4learning/holiday-package-purchase-prediction). It contains 20 columns and 4888 rows, providing various details about customers and their interactions with the company's offerings.

## Results

The Random Forest model with tuned hyperparameters achieved the best performance on the test set.

*   **Accuracy**: 0.9366
*   **F1 Score**: 0.9324
*   **Precision**: 0.9708
*   **Recall**: 0.6963
*   **ROC AUC Score**: 0.8456

## Conclusion

The data was loaded and cleaned, handling missing values and correcting inconsistencies. Several models were trained to predict holiday package purchases. After hyperparameter tuning, the Random Forest model performed best on the test set, achieving over 93% accuracy and effectively identifying about 70% of customers likely to purchase a package. This model can help the company improve marketing efficiency.

## Visualizations

The ROC AUC curve for the Random Forest Classifier is included as `auc.png`, demonstrating the model's performance.

<img width="640" height="480" alt="auc" src="https://github.com/user-attachments/assets/6baeb31d-3fd5-4fef-8ab7-40488f199242" />



