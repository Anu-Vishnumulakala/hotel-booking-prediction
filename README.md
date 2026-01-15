# hotel-booking-prediction
Predict hotel booking cancellations using ML
## Goal
Use Dataiku DSS to build a machine learning model that predicts whether a hotel booking will be canceled or not.
## Project Export-Dataiku
This ZIP file contains the full Dataiku DSS project export, including all:
- Datasets and recipes
- Machine learning models
- Data preparation flows
## Summary
- **Data Source:** `booking_train.csv` & `booking_test.csv`
- **Platform Used:** Dataiku DSS
- **Model Type:** Binary classification (booking canceled or not)
- **Best Model:** Random Forest
- **Final Accuracy:** 87.8%
## Model Training in Dataiku
- Selected **Binary Classification** with target: `booking_status`
- **Train/Test split** with `random_state=42` for reproducibility
- Used **Grid Search** to tune hyperparameters
## Best Performing Model
**Random Forest**
- Final Accuracy: **0.878**
- Strong performance without much overfitting
