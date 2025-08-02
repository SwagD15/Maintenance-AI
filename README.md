# Predictive Maintenance of Industrial Machinery

## Project Overview

This project aims to develop a machine learning model to predict failures in a fleet of industrial machines before they occur. By analyzing sensor data from machinery, the model classifies the type of failure—such as tool wear, heat dissipation, or power failure—based on real-time operational data. This enables proactive maintenance, reduces downtime, and lowers operational costs.

## Dataset

The model is trained on the [Predictive Maintenance Classification dataset](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification) from Kaggle, which contains sensor readings and labeled failure types for industrial machines.

## Technologies Used

- IBM Cloud Platform
- Watsonx.ai AutoAI for automated model building and optimization
- Snap Random Forest Classifier algorithm (selected by AutoAI)
- IBM Watsonx.ai Runtime for model deployment
- IBM Cloud Object Storage for data and model artifact storage

## Features

- Automated feature engineering and model tuning using IBM Watsonx.ai AutoAI
- Classification of multiple failure types with high accuracy
- Deployment as a scalable REST API on IBM Cloud for real-time predictions
- Robust testing covering both regular and edge cases

## How to Use

1. Clone this repository.
2. Access the dataset on Kaggle and upload it to IBM Cloud Object Storage.
3. Use IBM Watsonx.ai Studio to create an AutoAI experiment for training the model.
4. Deploy the trained model using Watsonx.ai Runtime on IBM Cloud.
5. Send real-time sensor data to the deployed API endpoint to receive failure predictions.

## Future Enhancements

- Integration with real-time IoT sensor streams
- Automated model retraining with new data
- Expansion to anomaly detection and remaining useful life (RUL) prediction
- Edge deployment for on-site predictions

## Author

Swagatam Rui Das
