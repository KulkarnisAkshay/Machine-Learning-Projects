# Machine-Learning-Projects:
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
#_____________________________________________________________________________________________________________________________


## 2. Used Car Price Prediction

## Project Overview

This project focuses on predicting the selling price of used cars based on various features. The goal is to build a reliable machine learning model that can provide accurate price estimates, which can be valuable for both buyers and sellers in the used car market.

## Data

The dataset used in this project was collected from cardekho.com and contains information about used cars sold in India. It includes the following features:

- `car_name`: The name of the car model.
- `brand`: The brand of the car.
- `model`: The specific model of the car.
- `vehicle_age`: The age of the car in years.
- `km_driven`: The total kilometers driven by the car.
- `seller_type`: The type of seller (e.g., Individual, Dealer).
- `fuel_type`: The type of fuel used by the car (e.g., Petrol, Diesel).
- `transmission_type`: The type of transmission (e.g., Manual, Automatic).
- `mileage`: The fuel efficiency of the car in km/l.
- `engine`: The engine capacity in CC.
- `max_power`: The maximum power of the car in bhp.
- `seats`: The number of seats in the car.
- `selling_price`: The selling price of the car.

## Results

The project involved training and evaluating several machine learning models. The Random Forest Regressor emerged as the best-performing model with the following results on the test set:

- **R2 Score:** 0.9400
- **Root Mean Squared Error (RMSE):** 212488.03
- **Mean Absolute Error (MAE):** 98301.34

This indicates that the model can explain 94% of the variance in the car prices and has a relatively low error in its predictions.

## Conclusion

The Random Forest Regressor model provides a robust and accurate solution for predicting used car prices. Its high R2 score and low error metrics make it a reliable tool for estimating the market value of a vehicle based on its features. This model can be effectively used to assist sellers in setting competitive prices and to help buyers make informed decisions.
#_____________________________________________________________________________________________________________________________



