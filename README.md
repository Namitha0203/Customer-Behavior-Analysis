## Project Overview
This project analyzes customer behavior using statistical and mathematical tools in Python.
The primary goal is to identify patterns in spending, factors influencing churn, and differences across demographic and marketing groups.

The dataset includes the following fields:

# CustomerID

# Gender

# Region

# PurchaseAmount

# ProductCategory

# Churn (Yes/No)

# CampaignGroup (A/B)

The analysis covers descriptive statistics, hypothesis testing, normality checks, and confidence interval estimation.

## Technologies Used
Python

Pandas

NumPy

SciPy

Matplotlib

Seaborn

## Objectives
* Understand customer spending patterns

* Detect outliers and distribution characteristics

* Compare spending across demographic groups

* Identify relationships between product category and churn

* Evaluate marketing campaign performance

* Apply statistical tests to validate insights

* Estimate confidence intervals for key metrics

## Key Findings
1. PurchaseAmount Summary Statistics
The mean, median, and mode were calculated to understand central tendency.

The mean and median were not identical, indicating slight skewness.

2. Outliers in PurchaseAmount
Using the IQR method, several high-value outliers were detected.

These represent a small group of customers with unusually high spending.

3. Skewness & Kurtosis
The distribution is right-skewed, confirmed by both histogram and skewness value.

Kurtosis indicated heavier tails than a normal distribution.

4. Gender vs PurchaseAmount
A t-test showed no statistically significant difference in average spending between male and female customers.

Both genders spend similarly on average.

5. ProductCategory vs Churn
A Chi-Square Test of Independence was performed.

The result showed a significant relationship between product category and churn.

Some categories have higher churn rates than others.

6. Regional Differences in Spending
A One-Way ANOVA test was conducted.

Results showed significant variation in PurchaseAmount across regions.

Certain regions have consistently higher spending levels.

7. Campaign A vs Campaign B
Campaign performance was compared using a t-test.

One campaign showed a higher average PurchaseAmount, but the statistical significance depends on the p-value.

This helps identify the more effective marketing strategy.

8. Normality of PurchaseAmount
Histogram plot shows that PurchaseAmount does not follow a perfect normal distribution.

The distribution is skewed, but the Central Limit Theorem allows normal-based tests for large samples.

9. Central Limit Theorem Insights
Even though the raw data is skewed, the sampling distribution of the mean becomes normal.

This justifies using t-tests, ANOVA, and confidence intervals.

The mean is a stable and reliable measure for this dataset.

10. 95% Confidence Interval for Mean PurchaseAmount

The interval provides a range in which the true average PurchaseAmount is likely to fall with 95% confidence.



## Conclusion
This project provides a comprehensive statistical understanding of customer behavior.
Key insights include:

Spending varies significantly by region and product category.

Gender does not influence spending.

Campaign performance differs and can be statistically evaluated.

The Central Limit Theorem enables reliable inference despite skewed data.

Churn is influenced by product category, offering actionable business insights.

These findings can help businesses improve customer retention, targeted marketing, and product strategy.