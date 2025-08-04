# ❤️ Heart Disease Prediction – KNIME Project

## 🧾 Project Overview

This project uses the **KNIME Analytics Platform** to build a predictive model that classifies whether a patient is at risk of heart disease based on clinical and demographic features. The workflow applies machine learning algorithms to structured health data, focusing on preprocessing, training, and evaluating classification models to support early detection and medical decision-making.


## 📁 Dataset

- **Source:** [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)  
- **Features:** 14 attributes including age, sex, chest pain type, cholesterol, blood pressure, max heart rate, and more  
- **Target:** Presence of heart disease (`0 = No`, `1 = Yes`)


## ⚙️ Tools & Technologies

- **Platform:** KNIME Analytics Platform  
- **Algorithms Used:**  
  - Decision Tree  
  - Logistic Regression  
  - Random Forest  
- **Nodes Used:** CSV Reader, Normalizer, Column Filter, Partitioning, Scorer, Learner & Predictor Nodes


## 🔍 Workflow Steps

1. **Data Import & Exploration**
   - Loaded dataset using CSV Reader  
   - Explored missing values and feature distributions

2. **Data Preprocessing**
   - Normalized numerical features  
   - Encoded categorical variables  
   - Partitioned dataset into training and testing sets (e.g., 70:30)

3. **Model Training**
   - Trained multiple models: Decision Tree, Logistic Regression, Random Forest  
   - Evaluated using cross-validation and confusion matrix

4. **Evaluation**
   - Compared accuracy, precision, recall, and F1-score  
   - Used ROC curves to assess model performance

## 📊 Results

| Model             | Accuracy | Precision | Recall | F1-Score |
|------------------|----------|-----------|--------|----------|
| Logistic Regression | ~85%   | 82%       | 83%    | 82%      |
| Random Forest       | ~88%   | 85%       | 86%    | 85%      |
| Decision Tree       | ~80%   | 78%       | 77%    | 77%      |

> ✅ **Random Forest** gave the best overall performance.


## 📸 Sample Workflow Screenshot

*(Add a screenshot of your KNIME workflow here)*


## 🚀 How to Run

1. Install [KNIME Analytics Platform](https://www.knime.com/downloads).
2. Clone or download this repository.
3. Open the `.knwf` file in KNIME.
4. Execute the workflow and inspect the results in the output and visualization nodes.


## 📌 Future Enhancements

- Add hyperparameter tuning using KNIME’s optimization loops  
- Integrate with Python scripts for advanced model comparison  
- Visualize key risk factors using feature importance

