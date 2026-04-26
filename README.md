#📘 Customer Churn Analysis & Prediction Project
##📊 Project Overview

Customer churn is a critical challenge for subscription-based and service-driven businesses. Identifying customers who are likely to leave allows organizations to take proactive measures to improve retention and reduce revenue loss.

This project combines customer segmentation (Stage 2) and predictive modeling (Stage 3) to deliver both analytical insights and actionable predictions.

Stage 2: Customer Segmentation using K-Means Clustering
Stage 3: Customer Churn Prediction using Artificial Neural Networks (ANN)

By integrating clustering and prediction, this project provides a data-driven framework for identifying high-risk customers and improving retention strategies.

##🎯 Objectives
Analyze customer data to identify churn patterns
Perform data preprocessing and feature engineering
Apply scaling techniques for model optimisation
Segment customers using K-Means Clustering
Predict churn using Artificial Neural Networks (ANN)
Evaluate model performance using classification metrics
Identify key factors influencing churn and retention
Provide actionable business recommendations

##🗂️ Project Structure
Customer-Churn-Analysis/
│
├── data_preparation/
│   ├── raw/
│   └── processed/
│
├── clustering_analysis/
│
├── predictive_modeling/
│
├── notebooks/
│   ├── data_preparation.ipynb
│   ├── clustering_analysis.ipynb
│   └── ann_model.ipynb
│
├── models/
│   ├── kmeans_model.pkl
│   ├── ann_model.h5
│   └── scaler.pkl
│
├── documents/
│   ├── Data Preparation Results.pdf
│   ├── Clustering Analysis Results.pdf
│   ├── ANN Model Report.pdf
│   ├── Final Report.pdf
│   └── visualizations/
│
├── README.md
└── LICENSE

##📁 Folder Description
data_preparation/
raw/ – Original dataset
processed/ – Cleaned and transformed dataset
clustering_analysis/

Contains scripts and outputs for customer segmentation using K-Means.

predictive_modeling/

Contains ANN model development, training, and evaluation.

notebooks/

Includes:

Data exploration
Preprocessing
Clustering analysis
ANN model training and evaluation
models/
kmeans_model.pkl → Clustering model
ann_model.h5 → Trained ANN model
scaler.pkl → Feature scaler
documents/
Reports
Visualizations
Final analysis outputs

##⚙️ Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
TensorFlow / Keras
K-Means Clustering
Git & GitHub

##🧠 Methodology
Stage 1: Data Preparation
Handling missing values
Encoding categorical variables
Feature transformation
Data type conversion
Stage 2: Customer Segmentation (Clustering)
Feature Scaling
Standardization applied to ensure equal contribution of features
Optimal Cluster Selection
Elbow Method used to determine optimal number of clusters
K-Means Clustering

Customer segments identified:

High-value loyal customers
Medium engagement customers
High churn-risk customers
Visualization
Cluster plots
Elbow curve
Stage 3: Churn Prediction (ANN)
Model Architecture
Input layer based on feature count
Hidden layers with ReLU activation
Output layer with Sigmoid activation
Training
Optimizer: Adam
Loss Function: Binary Crossentropy
Validation-based training
Model Performance
Metric	Value
Accuracy	78.28%
Precision (Churn)	0.63
Recall (Churn)	0.43
F1 Score (Churn)	0.51

##📊 Key Insights
From Clustering
Identified distinct customer segments
High-risk groups show low tenure and engagement
From ANN Model
Strong performance for non-churn prediction (recall = 0.91)
Moderate performance for churn detection
Key churn indicators:
High Monthly Charges
Low Tenure
Short-term contracts

##💼 Business Impact
Enables early identification of at-risk customers
Supports targeted retention strategies
Improves revenue retention
Enhances customer lifecycle understanding
Key Findings
High charges increase churn risk
Long-term customers are more stable
Contract-based customers are less likely to churn

##📌 Recommendations
Introduce loyalty programs
Optimize pricing strategies
Promote long-term contracts
Improve onboarding experience
Target high-risk segments with campaigns

##⚠️ Limitations
Moderate recall for churn (0.43)
Class imbalance affects performance
Limited interpretability of ANN
Correlation captures only linear relationships

##🚀 Future Improvements
Apply SMOTE or class balancing
Tune classification threshold
Use ensemble models (XGBoost, Random Forest)
Deploy as web app or API
Integrate dashboards (Power BI / Tableau)

##▶️ How to Run
git clone https://github.com/your-username/customer-churn-analysis.git
cd customer-churn-analysis
pip install -r requirements.txt
jupyter notebook

##👥 Contributors
Diksha Sharma
Devangi Patel
Krish Patel
Priyanka Panchal
Yash Thakkar

##📜 License

This project is for academic and educational purposes.

##⭐ Final Note

This project demonstrates a complete end-to-end machine learning pipeline, combining:

Data preprocessing
Customer segmentation
Deep learning-based churn prediction
Business-driven insights
