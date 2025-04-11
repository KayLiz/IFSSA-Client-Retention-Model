
# IFSSA Client Retention Model

The **IFSSA Client Retention Model** is a machine learning solution designed to predict client retention for the food hamper distribution program of the Islamic Family & Social Services Association (IFSSA). The model predicts whether a client is likely to be retained or churned based on their historical engagement with the program, helping IFSSA optimize outreach, service delivery, and resource allocation.

This project involves the full machine learning pipeline, including data collection, cleaning, exploratory data analysis (EDA), model development, deployment, and a user-friendly interface built with Streamlit.

## 🎯 Objectives

- **Predict Client Retention**: Classify clients as "retained" or "churned" based on their participation history and other relevant features.
- **Enhance Program Effectiveness**: Use the model's predictions to improve outreach and ensure continued support for clients in need.
- **Deployment**: Deliver an interactive application where stakeholders can input client data and receive retention predictions instantly.

## 🛠️ Features

- **Interactive Web App**: A user-friendly app built using Streamlit for visualizing data insights and providing real-time predictions.
- **Advanced Classification Models**: Utilizes machine learning models such as Logistic Regression, Random Forest, or other classifiers for accurate predictions.
- **Comprehensive Data Analysis**: Includes robust exploratory data analysis (EDA) to uncover trends and ensure high-quality model performance.

## 📊 Dataset

### Data Sources
The dataset includes historical client engagement data, detailing:
- Client participation history in the food hamper distribution program.
- Demographics and client-related features (excluding sensitive socioeconomic factors).
- Data on distribution center proximity and interaction with service programs.

### Key Features
- **Client Participation History**
- **Distribution Center Location**
- **Client/Household-Based Features**
- **Temporal Features** (e.g., participation trends over time)

> **Note**: Sensitive information has been anonymized to comply with data privacy policies.

## 🚀 Machine Learning Pipeline

1. **Data Collection**: Aggregated data from past food hamper distribution records.
2. **Data Cleaning & Preparation**: Removal of outliers, missing value imputation, and feature engineering.
3. **Exploratory Data Analysis (EDA)**: Insights into retention patterns and client behavior.
4. **Model Development**: Classification models to predict client retention.
5. **Model Deployment**: Hosted on Streamlit for user interaction and real-time predictions.

## 💻 App Demo

To test the app, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ifssa-client-retention-model.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ifssa-client-retention-model
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

Open the app in your browser and explore its features!

## 📂 Repository Structure

```
├── app.py               # Streamlit app file
├── data/                # Data files used for model training and testing
├── models/              # Pre-trained models for prediction
├── notebooks/           # Jupyter notebooks for EDA and model development
├── requirements.txt     # Required Python dependencies
└── README.md            # Project documentation
```

## 👥 Contributors

- **Enkeshie Parris**

Lead Developers & Data Scientists

## 📧 Contact

For inquiries or contributions, feel free to reach out via LinkedIn or email me directly.

