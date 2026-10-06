# Experiment 9: Model Validation and Explainability

## Aim

To apply model evaluation, Bayesian inference concepts, and explainable AI techniques to interpret and understand machine learning predictions on the Pima Indians Diabetes Dataset.

## Objectives

* Evaluate the reliability of machine learning predictions.
* Apply cross-validation techniques.
* Analyze model calibration.
* Apply Explainable AI techniques to understand model predictions.
* Identify important features influencing predictions.

## Dataset

**Pima Indians Diabetes Dataset**

The dataset contains diagnostic information for 768 female patients.

The target variable is:

* `Outcome = 0` → Non-diabetic
* `Outcome = 1` → Diabetic

## Tools & Technologies

* Python 3.x
* Google Colab / Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* SHAP
* LIME

## Techniques Used

* k-Fold Cross-Validation
* Performance Evaluation
* Calibration Curve
* Brier Score
* SHAP
* LIME

## Methodology

1. Load and preprocess the Pima Indians Diabetes Dataset.
2. Divide the dataset into training and testing sets.
3. Train a suitable classification model.
4. Perform 5-fold stratified cross-validation.
5. Calculate accuracy and F1-score.
6. Calculate the Brier Score and generate a calibration curve.
7. Apply SHAP or LIME to explain model predictions.
8. Identify important features influencing predictions.
9. Interpret and document the results.

## Results

### Cross-Validation

* Mean Accuracy: `0.7747`
* Standard Deviation: `0.0147`

### Brier Score

* Brier Score: `0.1679`

The lower Brier Score indicates better probabilistic predictions.

### Important Features

According to the SHAP feature-importance analysis:

1. **Glucose** — `0.961686`
2. **BMI** — `0.547771`
3. **Pregnancies** — `0.337378`

Glucose had the highest influence on the model's predictions.

## Individual Prediction

For one selected test observation:

* Actual Outcome: `0` (Non-diabetic)
* Predicted Outcome: `1` (Diabetic)
* Predicted Probability: `61.67%`

SHAP analysis showed that Glucose and Pregnancies increased the prediction toward the diabetic class, while BMI pushed the prediction toward the non-diabetic class.

## Conclusion

The classification model was evaluated using cross-validation and calibration analysis to understand its performance and reliability. SHAP or LIME was used to identify the features influencing individual predictions. The experiment demonstrated the importance of model performance, probability reliability, and interpretability in machine learning systems.

## Screenshots
<img width="1105" height="564" alt="image" src="https://github.com/user-attachments/assets/804ed768-7e53-4860-9500-ba7dbd579ff9" />
<img width="953" height="408" alt="image" src="https://github.com/user-attachments/assets/0c071001-5b3c-44f8-bdb0-4b2afa3da13f" />
<img width="728" height="681" alt="image" src="https://github.com/user-attachments/assets/b66dc987-7f0b-47d8-8a07-244a86a0be56" />

