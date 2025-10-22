# Predicting Youth Unemployment in Africa

This project builds a predictive model to forecast youth unemployment rates in African countries using key socioeconomic indicators. It was developed as a hands-on project during the DSN AI Bootcamp 2025, inspired by a session from Olalekan Akinsande (Mastercard Foundation).

The model uses a synthetic (but realistic) dataset to explore the relationships between GDP per Capita, Education Index, Urban Population (%), and Youth Unemployment Rates.

---

## Project Workflow and Features

This repository provides a complete end-to-end workflow in a single Jupyter Notebook, including:

* **1. Data Exploration (EDA):** Visualizing the relationships between GDP, education, and unemployment using Matplotlib.
* **2. Model Building:** Training a Linear Regression model using scikit-learn to predict unemployment.
* **3. Model Evaluation:** Assessing the model's performance and interpreting its coefficients to understand feature impact.
* **4. Interactive Prediction:** A simple UI built with `ipywidgets` to simulate predictions for different country profiles by adjusting sliders.

---

## Results and Performance

The final Linear Regression model demonstrated a clear predictive capability based on the input features.

* **R² Score: 0.74**
    This indicates that the model explains approximately 74% of the variation in youth unemployment rates.
* **Mean Absolute Error (MAE): 1.74**
    This means the model's predictions are, on average, off by 1.74 percentage points.

Visualizations in the notebook also include a Predicted vs. Actual comparison chart.

---

## Tech Stack

* Python 3.12
* Pandas (for data manipulation)
* Matplotlib (for plotting)
* Scikit-learn (for modeling and evaluation)
* Ipywidgets (for the interactive UI)
* Google Colab / Jupyter Notebook

---

## How to Run

### Option 1: Run in Google Colab (Recommended)

Click the "Open in Colab" badge below to open the notebook directly in Google Colab. The dataset is loaded from GitHub, so no local setup is required.

**[Add your "Open in Colab" badge here]**
*(You can create one at shields.io)*

### Option 2: Run Locally

1.  Clone this repository:
    ```bash
    git clone [https://github.com/your-username/Predicting_Youth_Unemployment_in_Africa.git](https://github.com/your-username/Predicting_Youth_Unemployment_in_Africa.git)
    cd Predicting_Youth_Unemployment_in_Africa
    ```

2.  Install dependencies (preferably in a virtual environment):
    ```bash
    pip install -r requirements.txt
    ```

3.  Launch Jupyter Notebook and open the `.ipynb` file.
    ```bash
    jupyter notebook
    ```
    *Note: You may be prompted to upload the CSV file if running locally.*

---

## Next Steps

Future improvements for this project include:

* **Feature Engineering:** Adding new predictors like internet penetration, access to finance, or sectoral data.
* **Model Comparison:** Benchmarking the Linear Regression model against others (e.g., Decision Tree, Random Forest, XGBoost).
* **Tuning:** Experimenting with cross-validation and hyperparameter tuning for better performance.

---

## Acknowledgments

* Guidance by **Olalekan Akinsande** (Mastercard Foundation).
* Special thanks to the **Data Science Nigeria (DSN)** team for organizing the DSN AI Bootcamp 2025 and making hands-on AI learning accessible.

---

## Author

**Ebunoluwa Arimoro**
* [LinkedIn Profile](https://www.linkedin.com/in/ebunoluwa-arimoro)
* [GitHub Profile](https://github.com/EbunoluwaArimoro)
