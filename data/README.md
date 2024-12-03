# Sepsis Prediction Using Demographic and Clinical Features

## Overview
This project aims to predict the likelihood of sepsis in patients based on various demographic and clinical features such as age, BMI, previous pregnancies, and other relevant factors. The project applies machine learning techniques within the CRISP-DM framework to build a robust predictive model.

---

## 1. Business Understanding
The goal of this project is to build a machine learning model that predicts the likelihood of sepsis in patients. Understanding the key factors that contribute to sepsis can help healthcare professionals make timely decisions and improve patient outcomes.

---

## 2. Data Understanding
The dataset contains both demographic and clinical features of patients, including:

- PRG: A categorical variable possibly encoded as numeric.
- PL: Plasma glucose levels (numerical).
- PR: A health-related metric (numerical).
- SK: A numerical variable possibly indicating a clinical measurement.
- TS: A numerical variable with values ranging from 0 to 800.
- M11: A numerical feature (likely a score or measurement).
- BD2: Another numerical feature, ranging from 0 to 2.4.
- Age: Age of the patient (numerical).
- Insurance: A binary variable indicating insurance status (0 for no insurance, 1 for insurance).
- Sepsis: The target variable indicating the presence of sepsis (1 for positive, 0 for negative).

The goal of this analysis is to predict the likelihood of a patient developing sepsis based on the given features. The target variable, **Sepsis**, is the key focus of the model, with values indicating the presence or absence of sepsis.



## 3. Data Preparation
Data was cleaned, transformed, and preprocessed to handle missing values, categorical variables, and outliers. Feature selection techniques have been applied to determine which features are most important for the predictive model.


## 4. Modeling
Different machine learning models have been applied to predict sepsis, including:

- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machine (SVM)
- Gradient Boosting

Hyperparameter tuning has been performed using cross-validation to optimize model performance.



## 5. Evaluation
The model has been evaluated based on various metrics:

- Accuracy
- Precision
- Recall
- F1-Score

The model's performance will be compared across different algorithms to determine which one best predicts the likelihood of sepsis.



## 6. Deployment
The final model will be deployed for use in healthcare settings, providing real-time sepsis predictions based on patient data.



## 7. Hypothesis Testing

### Null Hypothesis (H₀):
There is no significant relationship between the patient's demographic and clinical features (such as age, BMI, and previous pregnancies) and the likelihood of sepsis.

### Alternative Hypothesis (H₁):
There is a significant relationship between the patient's demographic and clinical features and the likelihood of sepsis.



## 8. Conclusion
This project aims to create a predictive model for sepsis using demographic and clinical features. By employing the CRISP-DM methodology, we ensure a structured approach to data understanding, preparation, modeling, and evaluation. The hypothesis testing guides the selection of relevant features, helping improve the accuracy and interpretability of the model.



## 9. Link to My Sepsis App
You can access the deployed app and explore the model in action [here](http://127.0.0.1:8000/docs).



## 10. Screenshots of the Application
Below are some screenshots of the app interface:

![alt text](<Screenshot 2024-12-02 144121.png>)
![alt text](<Screenshot 2024-12-02 144210.png>)
![alt text](<Screenshot 2024-12-02 144238.png>)
![alt text](<Screenshot 2024-12-02 144405.png>)
![alt text](<Screenshot 2024-12-02 144518.png>)
![alt text](<Screenshot 2024-12-02 143011.png>)



## 11. Setup

### Requirements:
1. Python 3.7 or higher
2. Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`, `flask` (for deployment), and others used for model building and deployment.

### Installation:
To install the required libraries, run:

```bash
pip install -r requirements.txt


Author
Justina Abena Owusua

Feel free to reach out via LinkedIn(https://www.linkedin.com/in/justina-abena-owusua),
Email(justinaabenaowusua@gmail.com)


License
This project is licensed under the MIT License 
