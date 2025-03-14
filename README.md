# AI-Based Stroke Risk Prediction System

## Overview
The **AI-Based Stroke Risk Prediction System** is a machine learning-powered model designed to assess the likelihood of stroke occurrence based on critical health parameters. By leveraging multiple algorithms and structured data processing, this system provides highly accurate predictions, assisting in early diagnosis and prevention.

## Objective
Stroke is a leading cause of disability and death worldwide, making early risk detection crucial. This system analyzes key factors such as age, medical history, and lifestyle habits to predict stroke risk, empowering individuals and healthcare professionals to take preventive measures.

## Features
- **Multi-Model Evaluation:** Uses eight machine learning algorithms to ensure the most reliable predictions.
- **Categorical Feature Encoding:** Transforms non-numeric features into machine-readable formats for better model performance.
- **High Accuracy:** Achieves a **maximum accuracy of 94.70%** with the Random Forest model.
- **Scalable and Extensible:** Can integrate additional health parameters for more comprehensive risk assessment.

## Machine Learning Models and Performance
| Model                | Accuracy  |
|----------------------|-----------|
| **Random Forest**    | **94.70%** |
| Logistic Regression  | 94.50%     |
| Support Vector Machine (SVM) | 94.60% |
| Gradient Boosting    | 94.20%     |
| XGBoost             | 94.20%     |
| K-Nearest Neighbors (KNN) | 93.79% |
| Decision Tree       | 91.04%     |
| Naive Bayes         | 87.37%     |

**Best Performing Model:** The **Random Forest Classifier**, achieving **94.70% accuracy**, is selected as the primary model due to its robustness and reliability.

## Data Preprocessing & Feature Engineering
The system uses structured health data with the following features:

- **Numerical Features:**
  - Age
  - Average Glucose Level
  - BMI
- **Categorical Features:**
  - Gender
  - Hypertension (Yes/No)
  - Heart Disease (Yes/No)
  - Ever Married (Yes/No)
  - Work Type
  - Residence Type
  - Smoking Status

### Encoding Strategy
To make categorical data usable for machine learning, the following encoding techniques are applied:

- **Label Encoding for Binary Categories:**
  - `gender`: Male → 0, Female → 1
  - `ever_married`: No → 0, Yes → 1
  - `Residence_type`: Rural → 0, Urban → 1

- **Category Mapping for Multi-Class Features:**
  - `work_type`: {'Govt_job': 0, 'Never_worked': 1, 'Private': 2, 'Self-employed': 3, 'Children': 4}
  - `smoking_status`: {'Unknown': 0, 'Formerly Smoked': 1, 'Never Smoked': 2, 'Smokes': 3}

## Prediction Workflow
1. **Input Data:** User provides health details.

      ![image](https://github.com/user-attachments/assets/085437a2-2d2f-44d6-9d2c-d952b1306100)


2. **Data Processing:** Categorical values are encoded.
3. **Model Execution:** The pre-trained model evaluates risk probability.
4. **Prediction Output:** Displays stroke risk likelihood.

    ![image](https://github.com/user-attachments/assets/007fd9b7-32d8-4e46-aafa-3a496b4a3d15)


## Future Enhancements
🔹 Incorporating deep learning for improved accuracy.  
🔹 Expanding the dataset for better generalization.  
🔹 Integrating real-time monitoring via wearable health devices.

## Conclusion
By leveraging machine learning techniques, this system delivers **highly accurate stroke risk predictions**. The model provides a proactive approach to **early detection and preventive healthcare**, potentially reducing the impact of strokes worldwide.

## Developer
Developed by **Abhishek Kushwaha**

🔗 **LinkedIn:** [https://www.linkedin.com/in/abhishek10027](https://www.linkedin.com/in/abhishek10027)  
💻 **GitHub:** [https://github.com/abhishek10027](https://github.com/abhishek10027)  

