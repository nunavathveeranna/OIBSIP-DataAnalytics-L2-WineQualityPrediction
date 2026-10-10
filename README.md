# Wine Quality Prediction

## Project Overview
This project predicts wine quality categories using machine learning based on the wine's physicochemical properties. The dataset is loaded directly from Kaggle using KaggleHub, without manually downloading the CSV file.

## Objectives
- Analyze wine quality scores and chemical properties.
- Perform Exploratory Data Analysis (EDA) using visualizations and a correlation heatmap.
- Handle missing values and duplicate records.
- Group wine quality scores into Low, Medium, and High categories.
- Train and compare multiple machine learning classification models.
- Identify important features influencing wine quality predictions.

## Dataset
- **Source:** [Wine Quality Dataset – Kaggle](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset)
- **Loading Method:** KaggleHub
- **Features:** Fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, sulfur dioxide, density, pH, sulphates, and alcohol.
- **Target Variable:** Wine quality category.

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- KaggleHub

## Machine Learning Models
1. **Random Forest Classifier** – Combines multiple decision trees to make predictions.
2. **SGD Classifier** – Uses stochastic gradient descent for model optimization.
3. **Support Vector Classifier (SVC)** – Classifies samples by learning decision boundaries.

## Methodology
1. Load the dataset directly from Kaggle.
2. Inspect the dataset and perform data cleaning.
3. Conduct EDA using feature distributions and correlation analysis.
4. Create Low, Medium, and High wine quality categories.
5. Split the data into training and testing sets using stratified sampling.
6. Train the three classification models.
7. Evaluate models using accuracy, precision, recall, F1-score, classification reports, and confusion matrices.
8. Analyze Random Forest feature importance.
9. Compare model performance and select a candidate for deployment based on macro F1-score.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- Macro F1-score
- Weighted F1-score
- Confusion Matrix

## How to Run
1. Open Google Colab or Jupyter Notebook.
2. Install the required dependencies:

   `pip install kagglehub[pandas-datasets] pandas numpy scikit-learn seaborn matplotlib`

3. Run the notebook cells in sequence.
4. Review the evaluation metrics, visualizations, and example prediction.

## Expected Outcome
The project demonstrates how machine learning can classify wine into quality categories based on its chemical properties. It also compares different classification algorithms and identifies the features most influential to the predictions.

## Applications
- Wine quality assessment support.
- Analysis of relationships between chemical properties and quality.
- Comparison of machine learning approaches for classification.

## Note
Model performance depends on the dataset, preprocessing, and model configuration. The selected model should be validated further before real-world use.

## Author
Developed as part of a machine learning internship task.