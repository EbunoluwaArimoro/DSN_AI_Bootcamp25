Predicting Youth Unemployment in Africa 🇳🇬🌍

This project was developed during the DSN AI Bootcamp 2025, inspired by a session led by Olalekan Akinsande (Mastercard Foundation).
It demonstrates how to build a predictive model from scratch using Python and real-world-inspired data.

🧠 Project Overview

The goal of this project is to predict youth unemployment rates in African countries using socioeconomic indicators such as:

GDP per Capita

Education Index

Urban Population (%)

The dataset contains synthetic but realistic values for demonstration and learning purposes.

📊 Project Workflow

Data Loading & Exploration (EDA)

Loaded dataset from GitHub or local upload

Visualized relationships between GDP, education, and unemployment

Model Building

Trained a Linear Regression model using scikit-learn

Interpreted coefficients and key insights

Model Evaluation

Mean Absolute Error (MAE): 1.74

R² Score: 0.74

Visualization

Scatter plots for feature relationships

Predicted vs Actual comparison chart

Interactive Prediction UI

Added sliders using ipywidgets to simulate predictions for different country profiles.

⚙️ Tech Stack

Python 3.12

Pandas

Matplotlib

scikit-learn

ipywidgets

Google Colab / Jupyter Notebook

🚀 How to Run
Option 1: Run in Google Colab

Click below to open the notebook directly in Colab:

Option 2: Run Locally

Clone this repository

git clone https://github.com/your-username/Predicting_Youth_Unemployment_in_Africa.git
cd Predicting_Youth_Unemployment_in_Africa


Install dependencies

pip install -r requirements.txt


Launch Jupyter or Colab and upload the CSV file when prompted.

📈 Results

The model explains about 74% of the variation in youth unemployment across countries, showing strong relationships between GDP, education, and urbanization levels.

💡 Next Steps

Add new predictors (internet penetration, access to finance, sectoral data)

Compare multiple models (Decision Tree, Random Forest, etc.)

Experiment with cross-validation and hyperparameter tuning

👏 Acknowledgment

Guided by Olalekan Akinsande during the DSN AI Bootcamp 2025.
Special thanks to the Data Science Nigeria (DSN) team for making hands-on AI learning accessible.

👩🏽‍💻 Author

Ebunoluwa [Your Last Name]
