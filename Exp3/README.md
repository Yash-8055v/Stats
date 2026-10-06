# Experiment 3: Correlation Analysis, Distance Measures & Data Preprocessing

## Aim

To implement correlation analysis, distance measures, and basic data preprocessing techniques on the **Pima Indians Diabetes Dataset** to identify relationships between variables and prepare data for further analysis.

## Dataset

**Pima Indians Diabetes Dataset**

* Number of observations: 768
* Dataset contains medical diagnostic information of female patients.
* The `Outcome` variable indicates whether the patient is diabetic.

## Objectives

* Apply correlation measures to analyze relationships between variables.
* Calculate distance measures between observations.
* Identify and handle invalid or missing values.
* Apply normalization or standardization.
* Interpret the obtained statistical results.

## Technologies Used

* Python 3.x
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab / Jupyter Notebook

## Statistical Methods

### 1. Correlation Analysis

Pearson correlation is used to measure the strength and direction of the linear relationship between two variables.

The correlation coefficient ranges from:

`-1 ≤ r ≤ 1`

* `r ≈ 1` → Strong positive relationship
* `r ≈ -1` → Strong negative relationship
* `r ≈ 0` → Weak or no linear relationship

A correlation heatmap is used to visualize relationships among variables.

### 2. Distance Measures

The following distance measures are implemented:

#### Euclidean Distance

Measures the straight-line distance between two observations.

#### Manhattan Distance

Measures the sum of absolute differences between corresponding features.

#### Cosine Distance

Measures the difference in direction between two data vectors.

## Data Preprocessing

Invalid zero values in medical attributes such as:

* Glucose
* BloodPressure
* SkinThickness
* Insulin
* BMI

are treated as missing values.

**Median imputation** is used to replace missing values because it is less affected by extreme values.

Normalization or standardization is then applied so that features with larger numerical ranges do not dominate distance calculations.

## Procedure

1. Load the Pima Indians Diabetes Dataset.
2. Identify invalid or missing values.
3. Replace selected invalid values with missing values.
4. Apply median imputation.
5. Calculate the correlation matrix.
6. Visualize correlations using a heatmap.
7. Calculate Euclidean, Manhattan, and Cosine distances.
8. Apply normalization or standardization.
9. Compare data before and after preprocessing.
10. Interpret the results.

## Key Findings

* Age and Pregnancies generally show a relatively strong positive relationship.
* Glucose and Outcome show an important positive relationship.
* No strong negative correlation is present in the dataset.
* Scaling is important because variables such as Insulin have a much larger numerical range.

## Conclusion

Correlation analysis, distance measures, and data preprocessing techniques were implemented on the Pima Indians Diabetes Dataset. Correlation analysis helped identify relationships between medical variables, while distance measures quantified similarity and dissimilarity between observations. Preprocessing improved the consistency and suitability of the dataset for statistical analysis and machine learning applications.

## Screenshot
<img width="899" height="620" alt="image" src="https://github.com/user-attachments/assets/df9580b7-5531-4711-bec0-cbaf18a90ac6" />
