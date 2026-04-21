# AI-Based Health Risk Prediction System

<img src="readme_pictures/fig1.png" alt="System Architecture">

## Introduction

The AI-Based Health Risk Prediction System is designed to assess an individual’s health risk level using machine learning techniques. By analyzing user inputs such as travel history, health parameters, and demographic factors, the system predicts potential risk levels and provides preventive recommendations.

This project aims to bridge the gap between raw health-related data and actionable insights by leveraging data-driven models for early risk detection and decision support.

<img src="readme_pictures/fig2.png" alt="Overview">

---

## Objectives

The primary objectives of this project are:

- **Risk Prediction**: Develop machine learning models to classify individuals into different health risk levels.
- **Early Detection**: Identify potential health risks at an early stage using predictive analytics.
- **Data-Driven Insights**: Extract meaningful patterns from health and travel-related data.
- **Personalized Recommendations**: Provide preventive measures based on predicted risk levels.

---

## Architecture

The system architecture is structured into multiple layers:

1. **Input Layer**  
   - User inputs including travel history, health parameters, demographics, and lifestyle factors.

2. **Data Processing Layer**  
   - Data cleaning, encoding categorical variables, handling missing values, and normalization.

3. **Feature Engineering Layer**  
   - Feature selection using correlation analysis and statistical methods (e.g., Cramer's V).  
   - Transformation and scaling of features.

4. **Model Layer**  
   - Machine learning classification models such as Logistic Regression, Random Forest, or Neural Networks.  
   - Model training, tuning, and optimization.

5. **Output Layer**  
   - Health risk classification (Low, Medium, High).  
   - Preventive recommendations and alerts.

---

## Methodology

The methodology follows a structured machine learning pipeline:

1. **Data Collection and Preprocessing**  
   <img src="readme_pictures/fig3.png" alt="Data Preprocessing">
   - Collected structured dataset from multiple sources  
   - Handled missing values and encoded categorical features  
   - Normalized and scaled data  

2. **Exploratory Data Analysis (EDA)**  
   <img src="readme_pictures/fig4.png" alt="EDA">
   - Performed univariate and bivariate analysis  
   - Visualized feature distributions and correlations  
   - Identified key patterns and trends  

3. **Feature Engineering**  
   - Selected important features using Random Forest importance and correlation metrics  
   - Applied feature transformation techniques  

4. **Model Training and Evaluation**  
   - Trained multiple classification models  
   - Evaluated performance using accuracy, precision, recall, and F1-score  
   - Used cross-validation and hyperparameter tuning  

   <img src="readme_pictures/fig5.png" alt="Model Training">

---

## Results

- **Performance Metrics**:
  - Achieved strong classification performance across multiple models  
  - High accuracy and balanced precision-recall scores  

- **Evaluation Analysis**:
  - Confusion Matrix and Classification Reports validate model effectiveness  
  - ROC-AUC curves demonstrate strong predictive capability  

<img src="readme_pictures/results.png" alt="Results">

---

## Implementation Details

1. **Data Preparation**
   - Cleaned dataset and handled inconsistencies  
   - Encoded categorical variables for model compatibility  

2. **Feature Selection**
   - Identified significant features using statistical methods and model-based importance  

3. **Model Development**
   - Implemented supervised learning models for classification  
   - Tuned hyperparameters for optimal performance  

4. **Evaluation**
   - Compared model performance across different algorithms  
   - Selected best-performing model for deployment  

---

## Future Scope

- Integration with real-time health monitoring systems  
- Deployment as a web-based application  
- Incorporation of deep learning models for improved accuracy  
- Expansion to include more diverse and large-scale datasets  

---

## Contact Information

For inquiries or collaboration:

Email: arshiyatyagii@gmail.com  
LinkedIn: https://www.linkedin.com/in/arshiyatyagi  

