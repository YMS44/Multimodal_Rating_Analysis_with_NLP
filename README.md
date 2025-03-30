# README: Multimodal Rating Analysis with NLP

## 1. Project Overview

This project applies Natural Language Processing (NLP) and structured data analysis to classify text-based data. The goal is to compare multiple machine learning models and determine the best-performing model for text classification.

## 2. Approach

- Load and preprocess structured & unstructured data.
- Extract text-based features using TF-IDF.
- Combine structured and unstructured features for a combined model.
- Train and evaluate models: Random Forest, GradientBoosting .
- Evaluate using metrics: Accuracy, F1-score, and Confusion Matrix.

## 3. Environment Setup

To set up the environment, install dependencies using:

```bash
pip install -r requirement.txt

```

## 4. Running the Code

Execute the Jupyter Notebook:

```bash
jupyter notebook Multimodal_Rating_Analysis.ipynb
```

Ensure the dataset (`Artificial_Data.xlsx`) is placed in the same directory as the notebook in 'data' folder.

## 5. Key Findings

- **Random Forest achieved 25% accuracy** but required hyperparameter tuning.
- **Gradient Boosting and XGBoost outperformed Random Forest** with optimized parameters.
- **Feature engineering (TF-IDF, sentiment analysis, categorical encoding) significantly impacted performance.**

## 6. Repository Structure

```
|-- data/                # Dataset files
|-- notebook[Code file]  # Jupyter Notebooks
|-- README.md            # Project documentation
|-- Project Report.pdf   # Project Report 
|-- requirement.txt     # Required Python packages
```


