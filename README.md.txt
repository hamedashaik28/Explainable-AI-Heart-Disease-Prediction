
# Explainable AI for Heart Disease Prediction

## Project Overview
This project uses machine learning to predict the presence of heart disease from clinical data. It compares three machine learning models and uses Explainable AI (XAI) techniques to understand model predictions.

## Objectives
- Analyze a heart disease dataset.
- Train and compare machine learning models.
- Evaluate model performance using classification metrics.
- Visualize model performance using ROC curves.
- Identify important clinical features.
- Use SHAP to explain model predictions.

## Dataset
- Dataset: Cleveland-style heart disease dataset
- Records before duplicate removal: 303
- Records after duplicate removal: 302
- Input features: 13
- Target: Binary heart disease label (0 or 1)

## Technologies Used
- Python
- Google Colab / Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- SHAP

## Machine Learning Models
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

## Model Results

| Model | Accuracy | Precision | Recall | F1-score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 0.787 | 0.763 | 0.879 | 0.817 | 0.865 |
| Decision Tree | 0.803 | 0.744 | 0.970 | 0.842 | 0.775 |
| Random Forest | 0.803 | 0.756 | 0.939 | 0.838 | 0.895 |

## Explainable AI
The project uses Random Forest feature importance and SHAP plots to explore which features influence the model's predictions, including explanations of individual predictions.

Feature importance and SHAP values describe model behavior. They do not establish that a feature causes heart disease.

## Limitations
- The dataset is small.
- Results depend on the chosen train-test split.
- Performance on other populations may differ.
- The models have not been clinically validated.

## Disclaimer
This project is for educational and portfolio purposes only. It is not intended for medical diagnosis or treatment decisions.
