# Cancer Patient Lifetime Prediction using Machine Learning

## Overview

This project predicts the expected lifetime of cancer patients using demographic, medical, and lifestyle information. A Linear Regression model is trained on patient data to estimate survival expectancy and identify the factors that most influence patient outcomes.

---

## Problem Statement

Healthcare professionals often need to estimate patient prognosis based on multiple clinical factors. This project applies Machine Learning techniques to predict a patient's expected lifetime using health indicators and cancer-related information.

---

## Dataset Features

### Numerical Features
- Age
- BMI
- BloodPressure
- Cholesterol
- ExerciseHoursPerWeek

### Categorical Features
- CancerStage
- SmokingStatus
- FamilyHistory

### Target Variable
- ExpectedLifetime

### Excluded Feature
- PatientID

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Machine Learning Pipeline

### Data Preprocessing

#### Numerical Data
- StandardScaler

#### Categorical Data
- OneHotEncoder

### Model
- Linear Regression

### Validation
- Train/Test Split (80/20)
- 5-Fold Cross Validation

---

## Evaluation Metrics

- RMSE (Root Mean Squared Error)
- R² Score
- Cross-Validated R² Score

---

## Visualizations

### Actual vs Predicted Lifetime
Compares model predictions with actual values.

### Residual Distribution
Analyzes prediction errors.

### Residuals vs Predicted
Checks model assumptions and bias.

### Correlation Heatmap
Explores feature relationships.

### Feature Importance Analysis
Ranks features based on Linear Regression coefficients.

---

## Project Structure

├── STAML_.ipynb
├── cancer_lifetime_data.xlsx
├── README.md

---

## How to Run

1. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

2. Place the dataset in the project folder.

3. Open Jupyter Notebook.

```bash
jupyter notebook
```

4. Run all cells.

---

## Future Improvements

- Random Forest Regressor
- XGBoost Regressor
- Feature Engineering
- Hyperparameter Tuning
- Survival Analysis Models
- Deployment using Flask or Streamlit

---

## Results

The model predicts patient expected lifetime using clinical and lifestyle features. Performance is evaluated using RMSE and R² metrics along with 5-fold cross-validation.

---

## Author

Machine Learning Regression Project
Cancer Lifetime Prediction System
