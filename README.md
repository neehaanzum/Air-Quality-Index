# AQI Prediction Model using Machine Learning


📌 Project Overview

This project focuses on building a Machine Learning model to predict Air Quality Index (AQI) using various atmospheric pollutant concentrations. By analyzing pollutant data such as PM2.5, PM10, NO₂, CO, and SO₂, the model estimates AQI with high accuracy.

This project supports environmental monitoring, smart city systems, and pollution forecasting.

📊 Sample Visualization
📁 Dataset Information

Dataset: air quality data.csv
Rows: Multiple city-wise observations
Columns include:

Pollutants: PM2.5, PM10, NO, NO2, NOx, CO, SO2, NH3, O3

Volatile organics: Benzene, Toluene, Xylene

City, Date

AQI (Target)

AQI Bucket (Categorical)

🧽 Data Preprocessing Steps

Removed duplicates

Handled missing pollutant values

Standardized datatypes

Created feature matrix (X) and target vector (y)

Performed train-test split (75:25)

Normalized feature values when required

🧠 Machine Learning Models Used
1. K-Nearest Neighbors Regressor (KNN)

Baseline model

Easy to implement

2. Decision Tree Regressor

Handles non-linearity

Can capture pollutant interactions

3. Random Forest Regressor

Best accuracy

Lowest RMSE

High generalization performance

📈 Model Evaluation Metrics

Models were evaluated using:

RMSE (Root Mean Square Error)

R² Score (Coefficient of Determination)

Example metrics printed:

RMSE Train Data = ...
RMSE Test Data = ...
R² score (Train) = ...
R² score (Test) = ...

🛠️ Technologies & Libraries

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

🚀 How to Run the Project
1. Clone the Repository
git clone https://github.com/<your-username>/AQI-Prediction-Model.git

2. Install Dependencies
pip install -r requirements.txt

3. Run the Notebook
jupyter notebook "AQI Prediction Model.ipynb"

4. Ensure Dataset Availability

Place air quality data.csv in the project directory.

📌 Project Structure
AQI-Prediction-Model/
│── air quality data.csv
│── AQI Prediction Model.ipynb
│── README.md
│── requirements.txt
└── visuals/

📈 Future Enhancements

Hyperparameter tuning (GridSearch, RandomSearch)

Deep learning models (LSTM for AQI forecasting)

Real-time AQI dashboard (Streamlit)

Model deployment with FastAPI

👩‍💻 Author

Shaik Neeha Anzum
AI & Machine Learning Enthusiast

For contact or collaboration, connect on LinkedIn.
