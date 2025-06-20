# Diabetes Diagnosis and Prediction using AI
## Project Description
This project uses machine learning to predict diabetes based on health parameters from the Pima Indians Diabetes Dataset. It includes data exploration, preprocessing, model training, evaluation, and a web interface for predictions.
## Features
- Multiple ML models for diabetes prediction (Random Forest, SVM, Logistic Regression, XGBoost)
- Comprehensive data analysis and visualization
- Model evaluation and comparison
- Web interface for predictions
  ## Installation
1. Clone this repository
2. Install requirements: `pip install -r requirements.txt`
3. Run Jupyter notebooks in the `notebooks/` directory to explore the data and train models
4. Run the web app: `python app/app.py`

## Dataset
The dataset contains 768 records with 8 health features and 1 outcome variable:
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (0 = no diabetes, 1 = diabetes)

## Results
Model performance comparison:
| Model               | Accuracy | Precision | Recall | F1 Score | ROC AUC |
|---------------------|----------|-----------|--------|----------|---------|
| Random Forest       | 0.74     | 0.63      | 0.65   | 0.64     | 0.83    |
| Logistic Regression | 0.75     | 0.66      | 0.61   | 0.64     | 0.82    |
| SVM                 | 0.74     | 0.66      | 0.58   | 0.62     | 0.80    |
| XGBoost             | 0.71     | 0.58      | 0.67   | 0.62     | 0.78    |


