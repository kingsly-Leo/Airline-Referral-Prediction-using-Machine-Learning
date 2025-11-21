
# Airline Referral Prediction using Machine Learning

This project predicts whether an airline passenger is likely to recommend the airline based on their travel details and service experience. Using a real-world airline reviews dataset, the model learns patterns from features such as airline, traveller type, cabin class, and ratings for seat comfort, cabin service, food & beverage, entertainment, and value for money.

## Project Highlights

- **Data Preparation:** Cleans raw input data, applies label encoding to categorical fields, scales numerical features, and uses SMOTE to address class imbalance.
- **Modeling:** Trains a Random Forest Classifier to classify whether a passenger will recommend the airline.
- **Artifacts:** Saves trained model and processing tools (`rf_model.pkl`, `scaler.pkl`, `label_encoders.pkl`) for deployment.
- **Web Application:** Implements a user-friendly Flask web app allowing users to enter passenger details via a form and instantly receive:
  - A predicted recommendation (Yes/No)
  - The probability that the passenger would recommend the airline

## Pipeline Overview

1. **Data Preprocessing** – Cleaning, encoding, scaling, and balancing.
2. **Model Training** – Random Forest Classifier development and evaluation.
3. **Model Deployment** – Saving necessary artifacts for inference.
4. **Web App Integration** – Real-time predictions via a seamless Flask interface.

## Purpose

This project demonstrates an end-to-end machine learning workflow, from raw data to a live, interactive prediction tool that aids airlines in gauging passenger advocacy.

---
