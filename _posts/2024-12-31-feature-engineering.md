---
layout: post
title:  "Feature Engineering"
date:   2024-12-17 13:26:19 -0500
categories: jekyll update
author: "Olga Durham"
---

# Feature Engineering

[Click to open the file...](https://github.com/shap0011/machine_learning_fall_2024/blob/main/Feature_Engineering_Solution.ipynb)

This project, <code>Feature_Engineering_Solution.ipynb</code> file, focuses on feature engineering techniques, leveraging domain knowledge and data manipulation to enhance predictive modeling for real estate pricing.

<details>
  <summary>Click to see details</summary>

<ul>
  <li><strong>Mounting Google Drive in Google Colab:</strong>
    <ul>
      <li>Enables seamless access to files stored in Google Drive for data loading.</li>
    </ul>
  </li>
  <li>Importing Required Libraries:
    <ul>
      <li><strong>Pandas:</strong> For DataFrame manipulation.</li>
      <li><strong>Matplotlib:</strong> For data visualization.</li>
      <li>Enable inline plotting within the notebook.</li>
      <li><strong>Seaborn:</strong> For enhanced visualizations.</li>
    </ul>
  </li>
  <li><strong>Importing the Cleaned Dataset (<code>cleaned__df.csv</code>):</strong>
    <ul>
      <li>Load the dataset into a Pandas DataFrame.</li>
    </ul>
  </li>
  <li><strong>Exploring the Dataset:</strong>
    <ul>
      <li>Display the first two records using the <code>.head(2)</code> function.</li>
      <li>Generate summary statistics with the <code>.describe()</code> function.</li>
    </ul>
  </li>
  <li><strong>Quick EDA Hack:</strong>
    <ul>
      <li>Install the profiling library using <code>!pip install ydata-profiling</code>.</li>
      <li>Import the <code>ydata_profiling</code> package to generate a Pandas Profiling Report, including:
        <ul>
          <li>Overview</li>
          <li>Variables</li>
          <li>Interactions</li>
          <li>Correlations</li>
          <li>Missing Values</li>
          <li>Samples</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<h4>I. Domain Knowledge:</h4>

<ul>
  <li><strong>Popular Properties – 2 Bedrooms and 2 Bathrooms:</strong>
    <ul>
      <li>Create an indicator variable <code>df['popular']</code> for properties with 2 beds and 2 baths.</li>
      <li>Check the number of properties with 2 baths and 2 beds using <code>.value_counts()</code>.</li>
    </ul>
  </li>
  <li><strong>Housing Market Recession – Lowest Housing Prices (2010–2013):</strong>
    <ul>
      <li>Create a new variable <code>df['recession']</code> to identify properties sold during this period.</li>
      <li>Check how many properties were sold during the recession using <code>.value_counts()</code>.</li>
    </ul>
  </li>
</ul>

<h4>II. Interaction Features:</h4>

<ul>
  <li><strong>Feature Engineering from Domain Knowledge:</strong>
    <ul>
      <li><strong>Property Age:</strong>
        <ul>
          <li>Create a new feature, <code>df['property_age']</code>, by subtracting <code>year_built</code> from <code>year_sold</code>.</li>
          <li>Perform a sanity check by running <code>df.describe()</code> to verify the statistics for <code>property_age</code>.</li>
          <li>Identify observations where <code>property_age</code> < 0 using <code>.value_counts()</code>.</li>
          <li>Remove rows where <code>property_age</code> is less than 0 to clean the dataset.</li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<h4>III. Dummy Variables:</h4>

<ul>
  <li><strong>Creating Dummy Variables:</strong>
    <ul>
      <li>Generate dummy variables for all categorical features using the <code>pd.get_dummies()</code> function.</li>
      <li>Create dummy variables specifically for the <code>property_type</code> column.</li>
      <li>Perform a final check using the <code>df.info()</code> function.</li>
    </ul>
  </li>
  <li><strong>Saving the Dataset:</strong>
    <ul>
      <li>Save the processed dataset as <code>final.csv</code> using <code>.to_csv()</code>.</li>
    </ul>
  </li>
</ul>

</details>

<p>By creating indicator variables, engineering interaction features, and encoding categorical variables, this project prepares a refined dataset for machine learning, culminating in a clean and ready-to-train model saved as <code>final.csv</code>.</p>


