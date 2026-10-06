# Experiment 8: Clustering and Dimensionality Reduction

## Aim

To apply clustering and dimensionality reduction techniques to the Pima Indians Diabetes Dataset to discover hidden patterns and visualize relationships among patients.

## Objectives

* Apply clustering techniques to discover patterns in a high-dimensional dataset.
* Apply dimensionality reduction for visualization and analysis.
* Interpret the discovered clusters using suitable evaluation measures.

## Dataset

**Pima Indians Diabetes Dataset**

The dataset contains medical information for 768 female patients. The `Outcome` variable indicates diabetes status and is excluded during unsupervised learning.

## Tools & Technologies

* Python 3.x
* Google Colab / Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Techniques Used

### K-Means Clustering

K-Means was used to group patients based on similarities in their medical attributes.

### Elbow Method

The Elbow Method was used to determine a suitable number of clusters.

### Silhouette Score

The Silhouette Score was used to evaluate the quality and separation of the clusters.

### Principal Component Analysis (PCA)

PCA was used to reduce the dimensionality of the dataset and visualize observations in a two-dimensional space.

## Methodology

1. Load the Pima Indians Diabetes Dataset.
2. Select relevant numerical features.
3. Handle invalid or missing values.
4. Standardize the selected features.
5. Apply K-Means clustering.
6. Use the Elbow Method to select the number of clusters.
7. Evaluate the clustering using Silhouette Score.
8. Apply PCA for dimensionality reduction.
9. Visualize the observations in two-dimensional space.
10. Analyze and interpret the discovered clusters.

## Results

* Selected number of clusters: `k = 3`
* Silhouette Score: `0.144814`

The PCA analysis showed some grouping among the clusters, although there was overlap between them.

### Important PCA Features

**PC1:**

* Glucose
* BMI
* SkinThickness
* Age
* BloodPressure

**PC2:**

* Pregnancies
* Age
* BMI
* SkinThickness

## Conclusion

K-Means clustering was used to group patients based on similarities in their medical attributes, while PCA reduced the dimensionality for visualization. The clusters showed some differences in medical characteristics but did not completely separate diabetic and non-diabetic patients.

## Screenshots
<img width="895" height="567" alt="image" src="https://github.com/user-attachments/assets/ea639351-7b0f-4a39-89a8-4eb84fcbdf70" />

<img width="784" height="483" alt="image" src="https://github.com/user-attachments/assets/427405e1-b713-4daf-a29e-e179428aa7ca" />

