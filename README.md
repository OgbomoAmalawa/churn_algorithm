## This project develops and deploys an end-to-end customer churn prediction system for a financial services use case. The goal is to identify customers at risk of leaving the bank and support proactive retention strategies.
## A trained Deep Learning model (Keras/TensorFlow) predicts churn probability using customer profile, account behaviour, and geographical demographics. The model is ## exposed via a Python API, enabling real-time inference for operational systems.
## The full solution includes:
#### •	Feature engineering with One-Hot Encoding & Label Encoding for categorical fields
#### •	Deep Neural Network model trained using TensorFlow/Keras
#### •	StandardScaler for numerical feature normalization
#### •	ML model and preprocessing artifacts saved as .pkl and .h5 for deployment
#### •	REST API endpoint through a Python application (Flask or FastAPI—depending on code)
#### •	Customer churn dataset included for reproducibility (Churn_Modelling.csv)
#### •	Experiment notebooks documenting model training and evaluation
#### •	Requirements file for environment setup
