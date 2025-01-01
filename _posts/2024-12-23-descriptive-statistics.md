---
layout: post
title:  "Descriptive Statistics"
date:   2024-12-12 13:26:19 -0500
categories: jekyll update
author: "Olga Durham"
---

# Descriptive Statistics

[Click to open the file...](https://github.com/shap0011/machine_learning_fall_2024/blob/main/Goodlife_Fitness_Solution.ipynb)

In the `Goodlife_Fitness_Solutions.ipynb` file, I perform a descriptive analysis to create customer profiles for each GoodLife Fitness membership option. This analysis explores key statistical insights and visualizations, covering the following topics:  

<details>
  <summary>Click to see details</summary>
  <ul>
  <li><strong>Importing Libraries and Loading the Dataset</strong>: Import the necessary Python packages and load the <code>GoodlifeFitness.csv</code> dataset.</li>
  <li><strong>Basic Data Exploration</strong>: Print basic information about the dataset, check for null values, and review the data's structure.</li>
  <li><strong>Univariate Analysis</strong>:
    <ul>
      <li>Examine the five-number summary statistics.</li>
      <li>Analyze the dataset's summary, including descriptive stats for categorical data.</li>
    </ul>
  </li>
  <li><strong>Visualization of Numerical Distributions</strong>:
    <ul>
      <li>Plot the distribution of numerical columns such as <code>Age</code>.</li>
      <li>Create boxplots to identify outliers in <code>Age</code>.</li>
    </ul>
  </li>
  <li><strong>Categorical Data Analysis</strong>:
    <ul>
      <li>Determine value counts for each categorical column, including <code>Type</code>.</li>
      <li>Calculate the percentage distribution of user types using normalization.</li>
    </ul>
  </li>
  <li><strong>Bivariate Analysis</strong>: Visualize relationships, such as plotting a boxplot to compare <code>Income</code> with <code>Membership Type</code>.</li>
  <li><strong>Multivariate Analysis</strong>:
    <ul>
      <li>Use <code>pd.crosstab</code> to analyze data across <code>Gender</code> and <code>Type</code>.</li>
      <li>Apply <code>pd.pivot_table</code> to explore data by <code>Income</code> and <code>Type</code>. </li>
      <li>Create scatter plots using Pandas for further insights.</li>
    </ul>
  </li>
</ul>

</details>
<br>
<p>This case study demonstrates the application of descriptive statistics and visualization techniques to uncover actionable insights regarding fitness memberships.</p>
