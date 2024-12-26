---
layout: post
title:  "Standardization of Normal Variables"
date:   2024-12-13 13:26:19 -0500
categories: jekyll update
author: "Olga Durham"
---

[Click to open the file...](https://github.com/shap0011/machine_learning_fall_2024/blob/main/Z_score_Statistics.ipynb)

In the `Z_score_Statistics.ipynb` file, I perform standardizing normal variables using the Z-score method. This file includes the following steps: 

<details>
  <summary>Click to see details</summary>

<ul>
  <li><strong>Mounting Google Drive in Google Colab</strong>: Access files stored in Google Drive to enable seamless data loading.</li>
  <li><strong>Importing Libraries and Loading the Dataset</strong>: : Load the necessary Python packages and read the <code>scores.csv</code> file into a DataFrame.</li>
  <li><strong>Visualizing the Data Distribution</strong>:
    <ul>
      <li>Use the Seaborn library for visualization.</li>
      <li>Plot the distributions of <code>SAT</code> and <code>ACT</code> scores.</li>
    </ul>
  </li>
  <li><strong>Calculating Mean and Standard Deviation</strong>:
    <ul>
      <li>Compute the mean and standard deviation for <code>SAT</code> and <code>ACT</code> scores.</li>
      <li>Determine the Z-score for the highest scorer in <code>SAT</code> and <code>ACT</code> among all applicants.</li>
    </ul>
  </li>
  <li><strong>Applying the Z-Score to All Scores</strong>: Standardize the entire table by applying the Z-score formula to all values.</li>
  <li><strong>Fit-Transform Using StandardScaler</strong>:
    <ul>
      <li>Import <code>StandardScaler</code> from <code>sklearn.preprocessing</code>.</li>
      <li>Initialize the scaler and apply it to the <code>SATscore</code> and <code>ACTscore</code> columns using <code>fit</code> and <code>transform</code> methods, or utilize <code>fit_transform</code> directly. </li>
      <li>Display the updated DataFrame to confirm standardization.</li>
    </ul>
  </li>
</ul>

</details>
<br>
<p>This project highlights the use of Z-score standardization and the application of Python libraries to prepare data for further analysis.</p>
