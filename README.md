# Heart Disease Prediction using Logistic Regression

## Project Description

This machine learning project predicts whether a patient is likely to have heart disease based on medical and lifestyle features.

The goal of the project is to understand classification modeling, feature influence, and evaluation techniques using Logistic Regression.

This project demonstrates a complete machine learning workflow from data analysis to model evaluation.

---

## Dataset Features

The model uses the following input variables:

* Age → Age of the patient
* Sex → Gender (0 = Female, 1 = Male)
* ChestPainType → Type of chest pain
* RestingBP → Resting blood pressure
* Cholesterol → Serum cholesterol level
* FastingBS → Fasting blood sugar (0 = Normal, 1 = High)
* MaxHR → Maximum heart rate achieved
* ExerciseAngina → Exercise-induced angina
* Oldpeak → ST depression induced by exercise
* ST_Slope → Slope of peak exercise ST segment

Target Variable:

* HeartDisease

  * 0 → No heart disease
  * 1 → Heart disease present

---

## Project Workflow

1. Data loading and inspection
2. Exploratory data visualization
3. Feature and target selection
4. Train-test split
5. Feature scaling using StandardScaler
6. Logistic Regression model training
7. Model evaluation using:

   * Accuracy Score
   * Confusion Matrix
   * Classification Report
8. Manual prediction testing
9. Model saving using Pickle

---

## Visualization Used

* Scatter plots to understand feature vs disease relation
* Correlation heatmap to observe feature relationships

---

## Model Performance

The model performance is evaluated using classification metrics such as accuracy, precision, recall and F1-score to understand prediction quality.

---

## Key Insights

* Higher Oldpeak values are associated with increased risk of heart disease
* Lower maximum heart rate can indicate potential cardiac issues
* Chest pain type and exercise-induced angina influence prediction
* Age and cholesterol also contribute to disease probability

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## How to Run the Project

1. Download the dataset and project notebook/script
2. Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the notebook or Python script
4. Observe model evaluation results and predictions

---

## Future Improvements

* Try Decision Tree and Random Forest models
* Perform hyperparameter tuning
* Deploy the model using Streamlit or Flask
* Use real clinical datasets for advanced analysis

---

## Author

Machine Learning Practice Project
Heart Disease Prediction using Logistic Regression
