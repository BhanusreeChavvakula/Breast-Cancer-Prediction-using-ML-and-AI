# Breast-Cancer-Prediction-using-ML-and-AI

📝 Overview

This project aims to predict breast cancer using machine learning and AI techniques. The dataset contains various features related to breast cancer patients, such as age, tumor size, lymph nodes, and more. The goal is to build a predictive model that can accurately classify whether a patient has breast cancer or not based on these features.


🌟 Introduction

Breast cancer is one of the most common cancers among women worldwide. Early detection and accurate diagnosis are crucial for effective treatment. This project leverages machine learning algorithms to predict breast cancer based on patient data. The project includes:

-Data preprocessing

-Exploratory data analysis

-Model training and evaluation

-SHAP-based model interpretation



📊 Dataset

The dataset used in this project is named Breast Cancer.csv. It contains the following features:

Patient Id: Unique identifier for each patient

Age: Age of the patient

Menopausal status: Menopausal status of the patient

Tumor size: Size of the tumor

Tumor grade: Grade of the tumor

Lymph nodes: Number of lymph nodes

Progesterone Receptor Status: Progesterone receptor status

Estrogen Receptor Status: Estrogen receptor status

Hormone Therapy: Whether the patient underwent hormone therapy

Recurrence-Free Survival Time: Time until recurrence

Patient Status: Target variable indicating whether the patient has breast cancer (1) or not (0)



🛠️ Data Preprocessing

The dataset is preprocessed to handle missing values, scale features, and split the data into training and testing sets. The preprocessing steps include:

-Dropping unnecessary columns (Patient Id)

-Checking for missing values

-Scaling the features using StandardScaler

-Splitting the data into training and testing sets (80% training, 20% testing)



📈 Exploratory Data Analysis (EDA) 

The EDA section includes visualizations to understand the distribution of the target variable and the relationships between different features. The following visualizations are included:

-Correlation Heatmap: To understand the correlation between different features.

-ROC Curve: To evaluate the performance of the model.

-Distribution of Target Variable: To visualize the distribution of the target variable (Patient Status). 



🤖 Model Training and Evaluation

The project uses the Random Forest Classifier for predicting breast cancer. The model is trained on the training set and evaluated on the testing set. The evaluation metrics include:

-Accuracy: The proportion of correctly classified instances.

-Confusion Matrix: To visualize the true positives, true negatives, false positives, and false negatives.

-Classification Report: Includes precision, recall, and F1-score.



🔍 Model Predictions with SHAP

SHAP (SHapley Additive exPlanations) is used to explain the model's predictions. SHAP values provide insights into the contribution of each feature to the model's output. The SHAP summary plot is used to visualize the importance of each feature.



📦 Requirements

Python 3.x

Libraries: numpy, pandas, matplotlib, seaborn, plotly, scikit-learn, xgboost, shap






            
