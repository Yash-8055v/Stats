# Experiment 5: Resampling Techniques & Confidence Interval Estimation

## Aim

To implement **bootstrap and permutation resampling techniques** on the Pima Indians Diabetes Dataset for estimating confidence intervals and analyzing statistical differences between groups.

## Dataset

**Pima Indians Diabetes Dataset**

* Number of observations: 768
* Contains diagnostic information for female patients.
* The `Outcome` variable indicates whether the patient is diabetic.

## Objectives

* Apply bootstrap resampling techniques.
* Estimate sampling distributions.
* Construct confidence intervals.
* Apply permutation testing.
* Analyze statistical differences between groups.
* Interpret resampling results for statistical decision making.

## Technologies Used

* Python 3.x
* Pandas
* NumPy
* SciPy
* Matplotlib
* Seaborn
* Google Colab / Jupyter Notebook

## Resampling Techniques

### 1. Bootstrap Resampling

Bootstrap sampling repeatedly creates samples from the original dataset **with replacement**.

For every bootstrap sample, a statistic such as the mean is calculated.

The resulting values form an approximate sampling distribution, which can be used to estimate a confidence interval.

A **95% percentile bootstrap confidence interval** can be obtained using the 2.5th and 97.5th percentiles of the bootstrap distribution.

### 2. Permutation Test

A permutation test evaluates whether an observed difference between two groups could have occurred by chance.

In this experiment:

* Data is divided into two groups based on `Outcome`.
* The difference between group means is calculated.
* Group labels are randomly shuffled repeatedly.
* The difference in means is calculated for every permutation.
* The resulting values form the null distribution.

## Procedure

1. Load the Pima Indians Diabetes Dataset.
2. Select a numerical variable such as Glucose or BMI.
3. Generate repeated bootstrap samples with replacement.
4. Calculate the selected statistic for every bootstrap sample.
5. Construct a bootstrap confidence interval.
6. Divide the data into two groups based on Outcome.
7. Calculate the observed difference between group means.
8. Randomly permute group labels repeatedly.
9. Calculate the difference in means for every permutation.
10. Compare the observed difference with the permutation distribution.
11. Interpret the statistical result.

## Bootstrap Result

The **mean** was selected as the statistic for bootstrap resampling.

A **95% confidence interval** was obtained for the population mean.

The bootstrap distribution was centered close to the original sample mean, indicating that the estimate was reasonably stable.

## Permutation Test Result

The observed difference was calculated as the difference between the mean values of:

* Outcome 0
* Outcome 1

The permutation test can be used to determine whether the observed group difference is statistically significant.

At a significance level of `0.05`:

* `p-value < 0.05` → statistically significant difference
* `p-value ≥ 0.05` → insufficient evidence of a statistically significant difference

## Effect of Increasing Repetitions

Increasing the number of bootstrap or permutation repetitions makes the estimated distribution, p-value, and confidence interval more stable and accurate, with less random variation.

## Conclusion

Bootstrap and permutation resampling techniques were implemented on the Pima Indians Diabetes Dataset. Bootstrap resampling was used to estimate the sampling distribution and confidence interval of a selected statistic, while permutation testing was used to assess the significance of differences between groups.

## Screenshot
<img width="1016" height="771" alt="image" src="https://github.com/user-attachments/assets/a5fc1bf5-607a-44d3-a019-08b7334d5bf4" />
<img width="843" height="461" alt="image" src="https://github.com/user-attachments/assets/0c64b142-7042-462a-b2f6-f784a58f689f" />

