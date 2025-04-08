![image](https://github.com/user-attachments/assets/983a3a62-67df-42b9-ac40-3d4edeb0d6a3)# CropDoc-HARNESSING-TENSORFLOW-FOR-EARLY-DETECTION-AND-PREDICTION-OF-CROP-DISEASES

This is a web application for predicting plant diseases from uploaded images using a deep learning model trained with TensorFlow and Keras. The application is built with Flask.

Features
Upload an image of a plant leaf to detect potential diseases.
Uses a deep learning model (plant_disease_prediction_model.h5) for prediction.
Provides detailed descriptions of identified plant diseases.
Built with Flask for an easy-to-use web interface.
Project Structure
├── app.py # Main Flask application ├── plant_disease_prediction_model.h5 # Pre-trained model file ├── static/ │ ├── uploads/ # Directory for uploaded images ├── templates/ │ ├── app.html # Upload page │ ├── result.html # Result display page ├── requirements.txt # List of dependencies └── README.md # Project documentation

Dependencies
Flask tensorflow numpy pillow werkzeug

Installation
python app.py

