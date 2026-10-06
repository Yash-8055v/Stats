# Experiment 6: Regression Models

## Aim

To develop regression models for predicting a continuous variable using the Pima Indians Diabetes Dataset and evaluate their performance using appropriate statistical metrics.

## Objectives

* Develop a regression model to predict a continuous health-related variable.
* Evaluate the performance of the regression model using statistical measures.
* Analyze residuals and interpret the model results.

## Dataset

**Pima Indians Diabetes Dataset**

The dataset contains medical information for 768 female patients. In this experiment, **BMI** is selected as the continuous target variable, while other medical attributes are used as input features.

## Tools & Technologies

* Python 3.x
* Google Colab / Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Methodology

1. Load the Pima Indians Diabetes Dataset.
2. Select BMI as the target variable and relevant medical attributes as predictors.
3. Preprocess missing or invalid values.
4. Split the dataset into training and testing sets.
5. Develop and train a regression model.
6. Generate predictions on the test data.
7. Evaluate the model using statistical performance measures.
8. Analyze residuals and compare actual and predicted values.
9. Interpret the results and identify limitations.

## Evaluation Metrics

The regression model was evaluated using:

* **Mean Absolute Error (MAE)**
* **Mean Squared Error (MSE)**
* **Root Mean Squared Error (RMSE)**
* **R² Score**

### Results

* MAE: `0.334462`
* MSE: `0.171697`
* RMSE: `0.414363`
* R² Score: `0.245932`

RMSE provides a useful interpretation because it is expressed in the same units as BMI and represents the typical magnitude of prediction error.

## Conclusion

A regression model was developed to predict BMI using the Pima Indians Diabetes Dataset. The model was evaluated using regression metrics, and residual analysis was performed to understand prediction errors and model limitations.

## Screenshots
<img width="694" height="559" alt="image" src="https://github.com/user-attachments/assets/0305efe9-bfdd-422c-b815-71e360536842" />
<img width="662" height="475" alt="image" src="https://github.com/user-attachments/assets/625eaf56-076a-4dec-b4ca-d99012035759" />
<img width="614" height="478" alt="image" src="https://github.com/user-attachments/assets/3f3af91d-ae86-426d-b64b-1ff226f0e3a3" />

