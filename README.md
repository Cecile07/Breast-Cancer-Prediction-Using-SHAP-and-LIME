# Breast Cancer Prediction Using Machine Learning with Explainable AI (SHAP & LIME)

## Overview

This project presents an end-to-end **Machine Learning** solution for predicting whether a breast tumor is **benign** or **malignant** using clinical diagnostic features from the **Breast Cancer Wisconsin Dataset**. The project combines supervised machine learning with **Explainable Artificial Intelligence (XAI)** techniques to produce accurate, transparent, and interpretable predictions.

A **Random Forest Classifier** was trained to classify tumors, while **SHAP (SHapley Additive Explanations)** and **LIME (Local Interpretable Model-agnostic Explanations)** were used to explain the model's predictions. Model performance was evaluated using multiple classification metrics, including the **ROC Curve** and **ROC-AUC**, to assess its discriminative ability.

This project demonstrates how explainable machine learning can support healthcare professionals by providing both reliable predictions and meaningful insights into the factors influencing each decision.

---

## Project Highlights

- End-to-end supervised Machine Learning pipeline
- Breast cancer classification using the Breast Cancer Wisconsin Dataset
- Data preprocessing and exploratory data analysis (EDA)
- Random Forest Classifier for prediction
- Model evaluation using multiple performance metrics
- ROC Curve and ROC-AUC analysis
- Explainable AI using SHAP and LIME
- Global and local model interpretation
- Reproducible workflow implemented in Jupyter Notebook

---

## Objectives

- Develop a robust machine learning model for breast cancer prediction.
- Perform data preprocessing and exploratory data analysis.
- Train and evaluate a Random Forest classifier.
- Interpret model predictions using SHAP and LIME.
- Improve transparency and trust in AI-based healthcare applications.

---

## Dataset

**Dataset:** Breast Cancer Wisconsin Dataset

The dataset contains clinical measurements computed from digitized images of fine needle aspirates (FNA) of breast masses.

### Target Classes

| Value | Diagnosis |
|:-----:|-----------|
| 0 | Benign |
| 1 | Malignant |

### Dataset Information

- **Samples:** 569
- **Features:** 30 numerical features
- **Target Variable:** Diagnosis (Benign / Malignant)

### Example Features

- Radius Mean
- Texture Mean
- Perimeter Mean
- Area Mean
- Smoothness Mean
- Compactness Mean
- Concavity Mean
- Concave Points Mean
- Symmetry Mean
- Fractal Dimension Mean

---

## Technologies Used

| Category | Tools & Libraries |
|----------|-------------------|
| Programming Language | Python |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Explainable AI | SHAP, LIME |
| Model Serialization | Joblib |
| Development Environment | Jupyter Notebook |

---

## Machine Learning Workflow

1. Data Loading
2. Data Exploration
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Prediction on New Samples
10. Explainability using SHAP
11. Explainability using LIME

---

## Machine Learning Model

### Algorithm

- Random Forest Classifier

### Evaluation Metrics

The model was evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- ROC-AUC Score

---

## Explainable AI (XAI)

### SHAP (SHapley Additive Explanations)

SHAP explains predictions by measuring the contribution of every feature to the model's output. It provides both **global** and **local** explanations, making the model easier to understand.

Implemented SHAP visualizations include:

- SHAP Feature Importance Bar Plot
- SHAP Beeswarm Plot
- SHAP Waterfall Plot

### LIME (Local Interpretable Model-agnostic Explanations)

LIME explains individual predictions by approximating the model locally with an interpretable model. This helps users understand why a particular prediction was made for a specific patient.

---

## Results

The Random Forest classifier successfully classified breast tumors into **benign** and **malignant** categories with excellent predictive performance.

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC Curve
- ROC-AUC Score

The integration of **SHAP** and **LIME** provides transparent explanations of the model's decisions by highlighting the clinical features that most influence each prediction. This enhances model interpretability and demonstrates the importance of Explainable AI for trustworthy healthcare applications.

---

## Sample Visualizations

The project includes the following visualizations:

- Exploratory Data Analysis (EDA)
- Correlation Heatmap
- Feature Distribution Plots
- Confusion Matrix
- ROC Curve
- SHAP Feature Importance Plot
- SHAP Beeswarm Plot
- SHAP Waterfall Plot
- LIME Local Explanation

---

## Repository Structure

```text
Breast-Cancer-Prediction-XAI/
│
├── data/
├── notebooks/
├── models/
├── results/
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Cecile07/Breast-Cancer-Prediction-XAI.git
```

Navigate to the project directory:

```bash
cd Breast-Cancer-Prediction-XAI
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and run all cells to reproduce the complete machine learning workflow.

---

## Future Improvements

- Compare additional machine learning algorithms.
- Perform hyperparameter optimization.
- Develop a web application using Streamlit or Flask.
- Integrate additional Explainable AI techniques.
- Compare traditional machine learning models with deep learning approaches.
- Deploy the trained model for real-time prediction.

---

## Author

**Cecile Mbuyi Ngoie**

**M.Sc. Information Technology**  
**AI | Machine Learning | Explainable AI (XAI)**

**GitHub:** https://github.com/Cecile07

**LinkedIn:** https://www.linkedin.com/in/cecile-mbuyi-ngoie

---

## License

This project is licensed under the **MIT License**.
