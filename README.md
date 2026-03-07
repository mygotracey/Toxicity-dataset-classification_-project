Toxicity Prediction Using Machine Learning
Project Overview

This project builds a machine learning model to classify chemical compounds as Toxic or Non-Toxic using molecular descriptor data. The workflow includes Exploratory Data Analysis (EDA), data preprocessing, feature selection, class balancing using SMOTE, and training an ensemble model (Random Forest) with cross-validation.

Dataset

The dataset contains molecular descriptor features used to predict toxicity.

Target column: Class

Class labels:

0 → Non-Toxic

1 → Toxic

Project Workflow

Data loading and inspection

Exploratory Data Analysis (EDA)

Missing value analysis

Data preprocessing

Train-test split

Class balancing using SMOTE

Feature selection

Model training using Random Forest

Model validation using Cross-Validation

Model evaluation using classification metrics

Evaluation Metrics

The model performance is evaluated using:

Precision

Recall

F1-Score

Accuracy

Confusion Matrix

Tools & Libraries

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Imbalanced-learn (SMOTE)

How to Run

Clone the repository

Install required libraries

Run the Jupyter Notebook or Python script step by step

pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn

Author

Tracey Muthoni
