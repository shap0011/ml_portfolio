---
layout: post
title:  "Exploratory Data Analysis (EDA)"
date:   2024-12-15 13:26:19 -0500
categories: jekyll update
author: "Olga Durham"
---

# Exploratory Data Analysis (EDA)

[Click to open the file...](https://github.com/shap0011/machine_learning_fall_2024/blob/main/EDA_Solution.ipynb)

In the `EDA_Solution.ipynb` file, I explore and analyze a real estate transaction dataset to uncover insights, identify patterns, and prepare the data for building a predictive pricing model.

<details>
  <summary>Click to see details</summary>
  
<ul>
  <li><strong>Mounting Google Drive in Google Colab</strong>: Access files stored in Google Drive to enable seamless data loading.</li>
  <li><strong>Importing Libraries and Loading the Dataset</strong>: 
    <ul>
      <li>Import the necessary Python libraries:
        <ul>
          <li><strong>NumPy</strong> for numerical computing.</li>
          <li><strong>Pandas</strong> for data manipulation.</li>
          <li><strong>Matplotlib</strong> for visualization.</li>
          <li><strong>Seaborn</strong> for enhanced visualization.</li>
        </ul>
       </li> 
      <li>Load the <code>real_estate.csv</code> file into a DataFrame.</li>
    </ul>
  </li>
  <li><strong>Displaying Basic Dataset Information</strong>:
    <ul>
      <li>Print the dataset using <code>.head()</code> to view the first five rows.</li>
      <li>Display the last five rows of the dataset.</li>
      <li>Check the dataset's dimensions using the <code>.shape</code> attribute.</li>
    </ul>
  </li>
  <li><strong>Exploring Feature Data Types</strong>:
     <ul>
      <li>Print the column data types using <code>.dtypes</code>.</li>
    </ul> 
  </li>
  <li><strong>Plotting Feature Distributions</strong>:
    <ul>
      <li>Use <strong>Seaborn's Pairplot</strong> to display distributions of numeric features.</li>
      <li>Plot a histogram grid using the same method.</li>
    </ul>  
  </li>
  <li><strong>Displaying Formal Summary Statistics</strong>:
    <ul>
      <li>Summarize numerical features with the <code>.describe()</code> function.</li>
      <li>Summarize non-numerical features using <code>.describe(include='object')</code>. </li>
      <li>Observe missing values in the dataset.</li>
    </ul>  
  </li>
  <li><strong>Exploring Segmentations</strong>:
    <ul>
      <li>Use segmentation to observe the relationship between categorical and numeric features:
        <ul>
          <li>Plot a <strong>box plot</strong> of <code>sqft</code> by <code>property_type</code> using Seaborn.</li>
          <li>Plot a <strong>box plot</strong> of <code>price</code> by <code>property_type</code> using Seaborn.</li>
        </ul>
      </li>
    </ul>  
  </li>
  <li><strong>Analyzing Correlations</strong>:
    <ul>
      <li>Calculate correlations between numeric features using the <code>.corr(numeric_only=True)</code> function.</li>
    </ul>  
  </li>
  <li><strong>Visualizing Correlation Grids</strong>:
    <ul>
      <li>Plot a heatmap of annotated correlations using Seaborn.</li>
    </ul>  
  </li>
  <li><strong>Observing Minimum Lot Size</strong>:
    <ul>
      <li>Use <code>.loc</code> to filter <code>lot_size</code> for properties of type <code>Condo</code>.</li>
      <li>Use <code>.loc</code> to filter <code>lot_size</code> for properties of type <code>Bungalow</code>.</li>
    </ul>  
  </li>
</ul>

</details>
<br>
<p>This project creates a regression model to predict property transaction prices with a mean absolute error (MAE) of under $70,000, providing a data-driven alternative to traditional appraisal methods.</p>
