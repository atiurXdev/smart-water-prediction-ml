🌍 Smart Water Scarcity Prediction System

Predicting Global Water Stress using Machine Learning (2000-2025)

📌 Project Overview
As a CSE AIML student, I developed this project to address the growing global water crisis. This system uses a Random Forest Classifier to analyze environmental and socioeconomic factors to predict water scarcity levels across different regions.

The goal is to provide a data-driven framework that identifies "Critical" zones and enables intelligent resource management between surplus and deficit regions.

🛠️ Tech Stack
Language: Python 3.x

Platform: Google Colab / Jupyter Notebook

Libraries: Scikit-Learn, Pandas, NumPy, Seaborn, Matplotlib

Model: Random Forest Classification (Serialized via Pickle)

📊 Key Features & Methodology
Data Preprocessing: Handled categorical encoding for global datasets and feature scaling.

Predictive Modeling: Trained a Random Forest model to classify water scarcity into 4 levels: Critical, High, Moderate, and Low.

Feature Engineering: Identified key drivers such as Rainfall Impact, Groundwater Depletion, and Industrial vs. Agricultural usage.

Model Persistence: Saved the trained "brain" as a .pkl file for instant future predictions.

📈 Results & Analysis
1. Confusion Matrix
This matrix validates the model's precision. It shows how accurately the AI identifies each scarcity level without confusion.

2. Feature Importance
This is the most critical insight. It reveals that Rainfall and Groundwater levels are the most significant predictors of water stress, highlighting the impact of climate change.

📁 Repository Structure
Water_Scarcity_Prediction.ipynb: Complete source code and documentation.

global_water_consumption_2000_2025.csv: The primary dataset.

water_scarcity_model.pkl: The finalized, ready-to-use ML model.

plots/: Directory containing performance visualizations.

👨‍💻 Author
Atiur Rahaman Computer Science & Engineering (AIML) Student
