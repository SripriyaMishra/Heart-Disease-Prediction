Heart Disease Prediction System

# Project Overview
This project builds a machine learning model to predict heart disease risk using clinical health parameters. The system includes data preprocessing, model training, evaluation, and an interactive UI built with Gradio for real-time prediction.

# Dataset
- Contains structured patient health records for heart disease classification.
- Includes numerical and categorical clinical parameters.
- Key numerical features used for model training:
  Age, Cholesterol, Blood Pressure, Heart Rate, Exercise Hours, Stress Level, Blood Sugar
- Target Variable: Heart Disease (0 = No, 1 = Yes)

# Machine Learning Workflow
1. Data Cleaning & Missing Value Handling
2. Feature Selection
3. Train-Test Split
4. Feature Scaling (StandardScaler)
5. Model Training (Gaussian Naive Bayes)
6. Model Evaluation using:
   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - Confusion Matrix
   - Precision-Recall Curve
7. Model Performance Visualization

# Deployment
- Interactive UI built using Gradio
- Real-time heart disease risk prediction
- Displays probability score for clinical interpretation

# Model Performance (Naive Bayes)
- Accuracy: 93.5%
- Precision: 96%
- Recall: 87.8%
- F1 Score: 91.7%
Gaussian Naive Bayes achieved the highest overall performance and was selected as the final deployment model based on accuracy and balanced precision-recall metrics.

# Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Gradio

# Future Improvements
- Add advanced models (Random Forest, XGBoost)
- Include more medical parameters
- Deploy as full web application
