# Machine Learning Algorithms from Scratch

This project implements several machine learning algorithms from scratch in Python, including Decision Tree Classifier and Regressor, AdaBoost Classifier, and Gradient Boost Regressor. The goal is to build these algorithms without using any explicit machine learning libraries, except for basic utilities like NumPy.

## Dataset

The dataset used in this project consists of real estate features in different areas of Bangalore. The original data can be found [here](https://www.kaggle.com/amitabhajoy/bengaluru-house-price-data). The data was pre-processed for convenience and split into train, validation, and test sets.

### Variables

- `availability`: is the property available immediately (1) or in the near future (0).
- `total_sqft`: the area of the property in square feet (1 foot = 30.54 cm).
- `bedrooms`: the number of bedrooms in the property.
- `bath`: the number of bathrooms in the property.
- `balcony`: the number of balconies in the property.
- `rank`: the ranking of the neighborhood in terms of average price (1 is the highest).
- `area_type`: is the property type a built up area (B) or plot area (P).
- `price in rupees`: the price of the property.

## Algorithms Implemented

1. **Decision Tree**
   - Classifier: Predicts the area type (B, P) using all features in the dataset.
   - Regressor: Predicts the price of a property using all features in the dataset.

2. **AdaBoost Classifier**: Predicts the area type (B, P) using all features in the dataset.

3. **Gradient Boost Regressor**: Predicts the price of a property using all features in the dataset.

## Evaluation

Each algorithm builds a model based on the training and validation data and predicts the label of the test data. The following evaluation metrics are reported:

- Accuracy for classification tasks.
- Mean Squared Error (MSE) for regression tasks.

## Comparison with Sklearn

The project also includes implementations of the same algorithms using the Sklearn library. The results of the custom implementations are compared with the Sklearn models in terms of metrics and runtime.

## Dependencies

- Python 3.x
- NumPy
- Sklearn (for comparison)
