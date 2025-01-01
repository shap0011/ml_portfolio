---
layout: post
title:  "Practice with Pandas"
date:   2024-12-11 13:26:19 -0500
categories: jekyll update
author: "Olga Durham"
---

# Practice with Pandas

[Click to open the file...](https://github.com/shap0011/machine_learning_fall_2024/blob/main/Forbes_Billionaire_Homework.ipynb)

This section, the `Forbes_Billionaire_Homework.ipynb` file, showcases in-class practice with the Pandas library. It focuses on analyzing and manipulating a dataset containing information about billionaires from the Forbes 2020 list.

<details>
  <summary>Click to see details</summary>

  <ul>
  <li><strong>Mounting Google Drive in Google Colab:</strong>Enables seamless access to files stored in Google Drive for data loading.</li>
  <li><strong>Importing the Pandas Library</strong></li>
  <li><strong>Loading the <code>real_estate.csv</code> Dataset into a DataFrame</strong></li>
  <li><strong>Displaying Basic Dataset Information:</strong>
    <ul>
      <li>Use <code>.head()</code> and <code>.tail()</code> to view subsets of the data.</li>
    </ul>
  </li>
  <li><strong>Identify the Name at the 0th Index:</strong>
    <ul>
      <li>Display the name assigned to the 0th index in the DataFrame.</li>
    </ul>
  </li>
  <li><strong>Print the Dataset Dimensions:</strong>
    <ul>
      <li>Output the number of rows and columns in the dataset.</li>
    </ul>
  </li>
  <li><strong>Display Record Counts:</strong>
    <ul>
      <li>Show the last record using the <code>.tail(1)</code> function.</li>
      <li>Display the total number of rows (records).</li>
      <li>Display the total number of columns (attributes).</li>
    </ul>
  </li>
  <li><strong>Check Data Types:</strong>
    <ul>
      <li>Display the data types of all fields.</li>
      <li>Identify the data type of the <code>Source</code> variable.</li>
    </ul>
  </li>
  <li><strong>Check for Missing Values:</strong>
    <ul>
      <li>Use <code>.isna().sum()</code> and <code>.isnull().sum()</code> to identify missing values.</li>
    </ul>
  </li>
  <li><strong>Analyze Data Values:</strong>
    <ul>
      <li>Use <code>.value_counts()</code> to inspect values in specific columns.</li>
    </ul>
  </li>
  <li><strong>Check Column Types:</strong>
    <ul>
      <li>Verify the types of the columns.</li>
    </ul>
  </li>
  <li><strong>Basic Statistics:</strong>
    <ul>
      <li>Print descriptive statistics using the <code>.describe()</code> function.</li>
    </ul>
  </li>
  <li><strong>Identify the Youngest Billionaire:</strong>
    <ul>
      <li>Find and display the youngest billionaire in the dataset.</li>
    </ul>
  </li>
  <li><strong>Sort and Reset the Index:</strong>
    <ul>
      <li>Sort the dataset by <code>Age</code> in ascending order using <code>.sort_values()</code> and reset the index.</li>
    </ul>
  </li>
  <li><strong>Create a New Column:</strong>
    <ul>
      <li>Add a column called <code>Year_of_birth.</code></li>
    </ul>
  </li>
  <li><strong>Filter Billionaires Born in 1996:</strong>
    <ul>
      <li>Select records of billionaires born in 1996.</li>
    </ul>
  </li>
  <li><strong>Count Billionaires Born in 1996:</strong>
    <ul>
      <li>Display the total number of billionaires born in 1996 using the <code>.count()</code> function.</li>
    </ul>
  </li>
</ul>

</details>

<p>Through practical exercises, the dataset is explored using Pandas functions to extract insights, such as identifying the youngest billionaire, handling missing data, creating new columns, and filtering data based on specific criteria.</p>

