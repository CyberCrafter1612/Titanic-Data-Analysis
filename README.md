# Titanic-Data-Analysis
The Titanic Data Analysis & Survival Prediction project involves using machine learning to predict which passengers survived the Titanic disaster based on various features such as age, sex, passenger class, and fare. The analysis starts with exploratory data analysis (EDA) to understand patterns and relationships in the data, followed by data cleaning, feature engineering, and handling missing values.

A classification model, often using algorithms like Random Forest, is trained on labeled data to learn the factors influencing survival. The trained model is then tested on unseen data to predict survival outcomes. The project typically achieves around 73–84% accuracy depending on the model and preprocessing.

Key steps in the project include:
Importing and preparing data from the Titanic dataset.
Analyzing demographic and socioeconomic factors affecting survival chances.
Engineering features to improve model performance.
Training and evaluating machine learning models to predict passenger survival.
Visualizing survival trends by gender, age, and class.

The project highlights how predictive analytics can reveal insights into historical events and demonstrates practical skills in data preprocessing, feature engineering, model building, and evaluation in a real-world context.

# 🚢 Titanic Data Analysis & Survival Prediction

## 📌 Overview
This project analyzes the Titanic dataset to explore passenger demographics, travel classes, and survival rates.  
It also builds a machine learning model to predict whether a passenger would survive based on their features.

## 🗂 Project Structure
- `titanic_analysis.ipynb` — Jupyter Notebook with data preprocessing, EDA, and modeling.
- `titanic_analysis.py` — Python script version of the workflow.
- `data/titanic.csv` — Titanic dataset used for analysis and prediction.
- `models/survival_model.pkl` — Saved trained ML model.
- `images/` — Visualizations from analysis.

## ⚙️ Installation
```bash
git clone https://github.com/yourusername/Titanic-Data-Analysis-and-Survival-Prediction.git
cd Titanic-Data-Analysis-and-Survival-Prediction
pip install -r requirements.txt
