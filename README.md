# ARISA Machine Learning Medical Sector Assignment Paper – Cholesterol-lowering Supplement Classification

## Objective

The purpose of this exercise is to develop a machine learning classification model that determines whether a patient needs a cholesterol-reducing supplement. You will:

1. Use train_cholesterol.xlsx to train and evaluate your model.
2. Split the dataset into training and testing subsets.
3. Build a classification model to predict if a patient needs a supplement.
4. Test the model on the predict_cholesterol.xlsx dataset (20 new patients).
5. Submit the results for the 20 patients.

## Dataset

Each row in the dataset represents a patient with multiple attributes (features) that influence cholesterol levels. The dataset consists of the following attributes:

1. **Age** (Numeric): Patient's age in years. Importance: Age is a major risk factor for high cholesterol, as metabolism slows with age.

2. **Gender** (Categorical: Male/Female): Biological sex of the patient. Importance: Cholesterol levels tend to vary between men and women, especially after menopause.

3. **BMI (Body Mass Index)** (Numeric): A measure of body fat based on height and weight. Importance: Higher BMI is often linked to higher cholesterol levels.

4. **Total Cholesterol** (Numeric): The overall level of cholesterol in the blood (mg/dL). Importance: A high value (>240 mg/dL) is a strong indicator of cardiovascular risk.

5. **LDL Cholesterol (Low-Density Lipoprotein)** (Numeric): The "bad" cholesterol that contributes to artery blockage. Importance: Higher LDL (>160 mg/dL) increases the risk of heart disease.

6. **HDL Cholesterol (High-Density Lipoprotein)** (Numeric): The "good" cholesterol that helps remove excess cholesterol. Importance: Higher HDL (>60 mg/dL) is beneficial, while low levels can be a risk factor.

7. **Triglycerides** (Numeric): A type of fat in the blood that stores excess energy from food. Importance: High levels (>200 mg/dL) are associated with increased heart disease risk.

8. **Physical Activity** (Categorical: Low/Moderate/High): The level of exercise or movement the patient engages in. Importance: Regular physical activity can reduce cholesterol levels.

9. **Dietary Habits** (Categorical: Healthy/Moderate/Unhealthy): The patient's nutrition habits. Importance: Diet plays a major role in cholesterol levels.

10. **Family History** (Categorical: Yes/No): Whether the patient has a family history of high cholesterol. Importance: Genetic predisposition can influence cholesterol levels.

11. **Need Supplement (Target Variable)** (Binary: 0 = No, 1 = Yes):
    - 1 (Yes) = The patient needs a supplement to reduce cholesterol.
    - 0 (No) = The patient does not need a supplement.

## Delivery

Please upload the Jupyter Notebook containing the Python code you use to resolved the exercise, and the Excel File with the results of the 20 samples.

The files should have this naming convention, `predict_cholesterlo_surname_name.ipynb`, and `predict_cholesterol_surname_name.xlsx`.

## Evaluation

The final score will be a combination of classification evaluation accuracy, based on the number of correct answers out of 20, and code review, assessed by the sophistication of the code.