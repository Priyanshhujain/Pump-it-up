# Pump-it-up
# Water Pump Status Prediction Using Machine Learning

**This project focuses on predicting the operational status of water pumps in Tanzania using machine learning models. Given the historical data of pumps, the model predicts whether a pump is:**
1. **Functional**,
2. **Non-functional**, or
3. **Functional but requiring repair**.

## Problem Statement
Access to clean water is a pressing issue in many parts of the world. A significant challenge in maintaining water access is knowing which pumps are functional and which are broken. This model helps predict the condition of water pumps based on factors such as geographic location, construction year, and various technical features.

## Project Structure
- `pump_it_up_by_myself.ipynb`: Jupyter notebook containing all the code for data preprocessing, model training, and evaluation.
- `data`: Directory containing the dataset (`train.csv`).
- `models`: Directory for storing trained models.

## Dataset
The dataset includes features related to water pumps, such as:
- **Amount_tsh**: Total static head (amount of water available to waterpoint).
- **Date_recorded**: The date the row was entered.
- **Funder**: Who funded the well.
- **Gps_height**: Altitude of the well.
- **Installer**: Organization that installed the well.
- **Longitude** and **Latitude**: Geographic coordinates.
- **Waterpoint_type**: The kind of waterpoint (e.g., communal standpipe, hand pump).
- **Status_group**: Target variable indicating the operational status of the pump (functional, non-functional, functional but needs repair).

## Steps Involved
1. **Data Preprocessing**:
   - Handling missing data.
   - Feature encoding for categorical variables (e.g., `funder`, `installer`).
   - Feature scaling for numeric features like `gps_height` and `amount_tsh`.

2. **Model Training**:
   - Models like Random Forest, Decision Trees, and Logistic Regression are trained to predict the water pump status.
   - Hyperparameter tuning is performed to optimize model performance.

3. **Evaluation**:
   - Accuracy, Precision, Recall, and F1-score are used to evaluate the models.

## Results
The model achieves an accuracy of approximately `87%` (replace with actual value) in predicting the status of water pumps. Other evaluation metrics include Precision, Recall, and F1-Score to give a comprehensive view of the model’s performance.


