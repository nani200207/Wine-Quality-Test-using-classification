# Wine Quality Classification Project

## Project Overview
This project implements machine learning classification techniques to predict wine quality using a dataset of white wines. The implementation includes exploratory data analysis, data preprocessing, model training, and evaluation using Support Vector Machine (SVM) and Random Forest classifiers.

## Prerequisites
- Python 3.7+
- Required Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - imbalanced-learn

## Installation
1. Clone the repository
2. Install required dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn


## Dataset
- Source: UCI Machine Learning Repository
- File: winequality-white.csv
- Location: Place the dataset in the same directory as the script or update the file path in the code

## Usage
Run the script directly

## Key Features
- Exploratory Data Analysis (EDA)
- Class Distribution Visualization
- Correlation Heatmap
- Data Scaling
- Repeated K-Fold Cross-Validation
- Class Imbalance Handling
- Model Performance Evaluation
- Confusion Matrix
- Feature Importance Visualization (for Random Forest)
- ROC Curve (for SVM)

## Methodology
1. Load and inspect dataset
2. Split data into training and testing sets
3. Scale features
4. Perform cross-validation on SVM and Random Forest
5. Handle class imbalance using over and under sampling
6. Select best performing model
7. Evaluate model on test set

## Output
The visualizations are:
- Class Distribution
- Correlation Heatmap
- Confusion Matrix
- Feature Importance
- ROC Curve


