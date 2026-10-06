# Experiment 4: Statistical Inference, Estimation & Hypothesis Testing

## Aim

To apply statistical estimation and hypothesis testing techniques to the **Pima Indians Diabetes Dataset** and draw conclusions about population characteristics using sample data.

## Dataset

**Pima Indians Diabetes Dataset**

* Number of observations: 768
* Contains diagnostic information for female patients.
* The `Outcome` variable indicates whether the patient is diabetic.

## Objectives

* Apply statistical estimation techniques.
* Estimate population characteristics using sample data.
* Construct confidence intervals.
* Formulate null and alternative hypotheses.
* Perform statistical hypothesis tests.
* Interpret p-values and statistical decisions.

## Technologies Used

* Python 3.x
* Pandas
* NumPy
* SciPy
* Matplotlib
* Seaborn
* Google Colab / Jupyter Notebook

## Statistical Methods

### 1. Point Estimation

A sample statistic is used to estimate an unknown population parameter.

For example, the sample mean is used as an estimate of the population mean.

### 2. Confidence Interval

A confidence interval provides a range of plausible values for a population parameter.

A **95% confidence interval** is constructed for the population mean glucose level.

### 3. Hypothesis Testing

A hypothesis test evaluates a claim about a population.

* **Null Hypothesis (H₀):** Initial assumption.
* **Alternative Hypothesis (H₁):** Claim being investigated.

Significance level:

`α = 0.05`

Decision rule:

* If `p-value < 0.05`, reject H₀.
* If `p-value ≥ 0.05`, fail to reject H₀.

### 4. t-Test

A t-test is used to compare means.

In this experiment, a **one-sample t-test** is used to determine whether the population mean glucose level differs from 120 mg/dL.

### 5. Chi-Square Test

The chi-square test can be used to investigate the association between categorical variables.

## Procedure

1. Load the Pima Indians Diabetes Dataset.
2. Select appropriate variables.
3. Calculate point estimates such as sample mean and sample proportion.
4. Construct confidence intervals.
5. Formulate null and alternative hypotheses.
6. Select an appropriate statistical test.
7. Calculate the test statistic and p-value.
8. Compare the p-value with the significance level.
9. Make a statistical decision.
10. Interpret the result in the context of the dataset.

## Results

### Estimated Population Mean

The sample mean glucose level was:

**120.89 mg/dL**

### 95% Confidence Interval

The obtained confidence interval was:

**(118.62, 123.16) mg/dL**

This indicates that the true population mean glucose level is estimated to lie within this interval with 95% confidence.

### Hypothesis Test

The hypotheses were:

* **H₀:** μ = 120 mg/dL
* **H₁:** μ ≠ 120 mg/dL

Significance level:

`α = 0.05`

Obtained p-value:

**0.4412**

Since:

`0.4412 > 0.05`

the null hypothesis is **not rejected**.

## Conclusion

Statistical inference, estimation, and hypothesis testing techniques were applied to the Pima Indians Diabetes Dataset. Sample statistics were used to estimate population characteristics, confidence intervals were constructed, and hypothesis testing was performed to determine whether sufficient statistical evidence existed to support the selected claim.

## Screenshot
<img width="839" height="295" alt="image" src="https://github.com/user-attachments/assets/77547a97-07b1-4835-9894-95ac9b6f1dff" />
<img width="640" height="350" alt="image" src="https://github.com/user-attachments/assets/0f123326-dab3-4dd0-a053-4f8121b79190" />
