AI Weather Predictor 🌦️

Problem Statement

Weather prediction is crucial for agriculture, transportation, and daily planning. Traditional weather forecasting models can be inaccurate. This project leverages machine learning to improve forecasting by analyzing historical weather data.

Methodology

Data Collection: Used historical weather dataset containing temperature, humidity, wind speed, and rainfall.

Data Preprocessing: Handled missing values using SimpleImputer and standardized data using StandardScaler.

Feature Engineering: Visualized correlations and removed low-impact features.

Model Training: Implemented and compared three machine learning models:

Linear Regression

Random Forest Regressor

K-Nearest Neighbors (KNN) Regressor

Evaluation: Assessed model performance using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

Dataset

File: weather_dataset.csv (Uploaded in this repository)

Features: Temperature, Humidity, Wind Speed, Rainfall

Results

Best Model: Random Forest Regressor (Highest R² score, lowest error)

Example Prediction:

Input: [25°C, 80% Humidity, 10 km/h Wind]

Output: Light Rain Expected

Installation & Usage

To run the project locally, follow these steps:

git clone https://github.com/basitibrahim890/weather-predictor.git  
cd weather-predictor  
pip install -r requirements.txt  
jupyter notebook  

Open 422_project_weather_predictor.ipynb in Jupyter Notebook and run the cells.

Future Improvements

Improve accuracy using Deep Learning models (LSTMs, CNNs).

Integrate real-time weather APIs for live predictions.

Deploy as a web app (Flask/Django + React).

Contact

📧 Email: basitibrahim890@gmail.com
🔗 LinkedIn: Basit Ibrahim

