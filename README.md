🏠 House Price Prediction — Random Forest ML App
An end-to-end machine learning web app that predicts house prices using a Random Forest Regressor, built with Python and deployed via an interactive Streamlit UI.

🎯 Objective
Predict house prices based on 12 property features including bedrooms, bathrooms, sqft, location, and renovation year — with real-time prediction on user-defined input data.

🚀 Key Features

🤖 Random Forest Regressor with 500 estimators for high accuracy
🏷️ Label Encoding for categorical city data
📊 Model evaluation using R² Score and MAE
🎛️ Interactive Streamlit UI for real-time custom predictions
📈 Dual-mode Chart Dashboard:

Predefined Charts — Bedroom count, Price vs Sqft, Monthly trend, Top 10 cities by avg price
Custom Chart Builder — Bar, Horizontal Bar, Line, Scatter, Histogram with dynamic aggregation controls




🛠️ Tech Stack
ToolPurposePythonCore programming languageScikit-learnRandom Forest model & preprocessingPandas & NumPyData manipulationMatplotlibData visualizationStreamlitInteractive web app UIKaggleDataset source

🧠 ML Model Details
ParameterValueAlgorithmRandom Forest RegressorEstimators500Test Size30%Train Size70%Evaluation MetricsR² Score, MAEEncodingLabel Encoding (city column)

📁 Features Used for Prediction
bedrooms, bathrooms, sqft_living, sqft_lot, floors,
view, condition, sqft_above, sqft_basement,
yr_built, yr_renovated, city

📁 Project Structure
house-price-prediction-rf/
│
├── rf_mini_project.py    # Main Streamlit app
├── requirements.txt      # Dependencies
└── README.md             # Project documentation

▶️ How to Run

Clone the repository

bashgit clone https://github.com/Shiva-keerth/house-price-prediction-rf.git
cd house-price-prediction-rf

Install dependencies

bashpip install -r requirements.txt

Download the dataset from Kaggle and place it in the project folder
Run the Streamlit app

bashstreamlit run rf_mini_project.py

📊 Outcome

Built a fully interactive ML web app with real-time price prediction
Custom Chart Builder allows dynamic exploration of the dataset
Demonstrates end-to-end ML pipeline: Data → Preprocessing → Model → Deployment


⚠️ Dataset not included — download from Kaggle


👤 Author
Shiva Keerth G
📧 gantishivakeerth@gmail.com
🔗 GitHub | LinkedIn
