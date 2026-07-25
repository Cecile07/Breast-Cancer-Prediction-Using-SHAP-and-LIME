# Breast Cancer Prediction Using Machine Learning with Explainable AI (SHAP & LIME)

## Overview

This project presents an end-to-end **Machine Learning** solution for predicting whether a breast tumor is **benign** or **malignant** using clinical diagnostic features from the **Breast Cancer Wisconsin Dataset**. In addition to building an accurate classification model, the project incorporates **Explainable Artificial Intelligence (XAI)** techniques using **SHAP** and **LIME** to provide transparent and interpretable predictions.

The objective is to demonstrate how machine learning models can support healthcare professionals by delivering accurate predictions while explaining the reasoning behind each prediction.

## Objectives

* Develop a reliable breast cancer classification model.
* Perform data preprocessing and exploratory data analysis (EDA).
* Train and evaluate a Random Forest classifier.
* Interpret model predictions using SHAP and LIME.
* Demonstrate the importance of Explainable AI in healthcare applications.

## Dataset

**Dataset:** Breast Cancer Wisconsin Dataset

The dataset contains clinical measurements computed from digitized images of breast mass cell nuclei.

**Target Classes**

* **0** → Benign
* **1** → Malignant

**Number of Features:** 30

Example features include:

* Radius Mean
* Texture Mean
* Perimeter Mean
* Area Mean
* Smoothness Mean
* Compactness Mean
* Concavity Mean
* Concave Points Mean
* Symmetry Mean
* Fractal Dimension Mean

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SHAP
* LIME
* Joblib
* Jupyter Notebook

## Machine Learning Workflow

1. Data Loading
2. Data Exploration
3. Data Preprocessing
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Model Training
7. Model Evaluation
8. Prediction
9. Explainable AI using SHAP
10. Explainable AI using LIME

## Model

**Algorithm**

* Random Forest Classifier

**Evaluation Metrics**

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC (if generated)

## Explainable AI (XAI)

### SHAP (SHapley Additive exPlanations)

SHAP provides both **global** and **local** explanations by measuring the contribution of each feature to the model's predictions.

Implemented visualizations include:

* Feature Importance Bar Plot
* Beeswarm Plot
* Waterfall Plot

### LIME (Local Interpretable Model-agnostic Explanations)

LIME explains individual predictions by approximating the model locally, helping users understand why a specific prediction was made.

## Results

The Random Forest classifier successfully classified breast tumors into benign and malignant categories with strong predictive performance.

By integrating SHAP and LIME, the project provides transparent explanations that highlight the clinical features influencing each prediction, making the model more trustworthy and suitable for healthcare decision support.

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

## Installation

Clone the repository:

```bash
git clone https://github.com/Cecile07/Breast-Cancer-Prediction-XAI.git
```

Navigate to the project directory:

```bash
cd Breast-Cancer-Prediction-XAI
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and run all cells.

## Future Improvements

* Compare additional machine learning algorithms.
* Perform hyperparameter optimization.
* Deploy the model as a web application using Streamlit or Flask.
* Integrate additional Explainable AI techniques.
* Extend the project with deep learning models for comparison.

## Author

** Mbuyi Cecile Ngoie**

M.Sc. Information Technology | AI & Machine Learning Enthusiast

GitHub: https://github.com/Cecile07

LinkedIn: https://www.linkedin.com/in/cecile-mbuyi-ngoie

## License

This project is licensed under the **MIT License**.
