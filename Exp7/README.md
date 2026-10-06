# Experiment 7: Classification Models

## Aim

To build supervised classification models for predicting diabetes outcomes using the Pima Indians Diabetes Dataset and evaluate their performance using appropriate classification metrics.

## Objectives

* Build supervised classification models to predict diabetes outcomes.
* Evaluate and interpret classification model performance.
* Compare different classification algorithms.

## Dataset

**Pima Indians Diabetes Dataset**

The dataset contains medical information for 768 female patients.

The target variable is:

* `Outcome = 0` → Non-diabetic
* `Outcome = 1` → Diabetic

## Tools & Technologies

* Python 3.x
* Google Colab / Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Classification Models

The following supervised learning models were implemented:

* Logistic Regression
* k-Nearest Neighbors (KNN)
* Decision Tree

## Methodology

1. Load the Pima Indians Diabetes Dataset.
2. Separate input features and the target variable.
3. Handle invalid or missing values.
4. Split the dataset into training and testing sets using a stratified split.
5. Apply suitable preprocessing and feature scaling where required.
6. Train the classification models.
7. Generate predictions on the test data.
8. Construct the confusion matrix.
9. Calculate classification performance metrics.
10. Compare and interpret the results.

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC

For diabetes prediction, **Recall** is particularly important because it measures how many actual diabetic patients are correctly identified and helps reduce false negatives.

## Confusion Matrix

The Logistic Regression confusion matrix produced:

* True Positive (TP): `27`
* False Negative (FN): `18`

## Conclusion

Supervised classification models were developed to predict diabetes outcomes. The models were evaluated using confusion matrix, accuracy, precision, recall, F1-score, and ROC-AUC. The experiment demonstrated that different evaluation metrics provide different perspectives on classification performance.

## Screenshots

<img width="752" height="623" alt="image" src="https://github.com/user-attachments/assets/2c34b082-eb94-4729-8c4c-7a48f9d226e2" />
<img width="624" height="447" alt="image" src="https://github.com/user-attachments/assets/2e58664a-dbd2-4209-8a16-08cf22fb395f" />
<img width="603" height="462" alt="image" src="https://github.com/user-attachments/assets/e98dee03-1ea7-4dc3-ba40-eb8bea856070" />


