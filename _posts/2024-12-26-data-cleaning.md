---
layout: post
title:  "Data Cleaning"
date:   2024-12-16 13:26:19 -0500
categories: jekyll update
author: "Olga Durham"
---

# Data Cleaning

[Click to open the file...](https://github.com/shap0011/machine_learning_fall_2024/blob/main/Data_Cleaning_Solution.ipynb)

In <code>Data_Cleaning_Solution.ipynb</code>, I focus on identifying and addressing issues in the dataset, such as handling missing values, detecting and removing outliers, and ensuring data consistency to prepare it for effective model building.

<details>
  <summary>Click to see details</summary>

<ul>
  <li><strong>Mounting Google Drive in Google Colab:</strong>
    <ul>
      <li>Access files stored in Google Drive to enable seamless data loading.</li>
    </ul>
  </li>
  <li><strong>Importing Libraries and Loading the Dataset:</strong>
    <ul>
      <li>Import the necessary Python libraries:
        <ul>
          <li><strong>NumPy</strong>: For numerical computing.</li>
          <li><strong>Pandas</strong>: For data manipulation.</li>
          <li><strong>Matplotlib</strong>: For visualization.</li>
          <li><strong>Seaborn</strong>: For enhanced visualization.</li>
        </ul>
      </li>
      <li>Load the <code>real__estate.csv</code> file into a DataFrame.</li>
    </ul>
  </li>
  <li><strong>Displaying Basic Dataset Information:</strong>
    <ul>
      <li>Use  <code>.head()</code>,  <code>.tail()</code>, and  <code>.sample()</code> to view subsets of the data.</li>
    </ul>
  </li>
  <li><strong>Displaying Formal Summary Statistics:</strong>
    <ul>
      <li>Summarize numerical features using the <code>.describe()</code> function.</li>
    </ul>
  </li>
  <li><strong>Handling Missing Data:</strong>
    <ul>
      <li>Display unique values for <code>basement</code> and <code>property_type</code>. </li>
      <li>Recognize that <strong>NaN</strong> values for <code>basement</code> indicate properties without a basement.</li>
      <li>Replace <code>NaN</code> values with <code>0</code> using the <code>.fillna()</code> function.</li>
      <li>Convert the <code>basement</code> column data type to integer.</li>
    </ul>
  </li>
  <li><strong>Removing Outliers:</strong>
    <ul>
      <li>Import the <code>warnings</code> module to suppress warnings during visualization.</li>
      <li>Create violin plots for <code>beds</code>, <code>sqft</code>, and <code>lot_size</code> to identify potential outliers.</li>
      <li>Sort the <code>lot_size</code> column and display the top 5 largest values.</li>
      <li>Examine rows with unusually large lot sizes.</li>
      <li>Remove observations where <code>lot_size</code> exceeds <strong>500,000 sqft</strong>, as they are deemed outliers.</li>
    </ul>  
  </li>
  <li><strong>Saving the Cleaned Dataset:</strong>
    <ul>
      <li>Save the cleaned DataFrame as <code>cleaned_df.csv</code>.</li>
      <li>Verify the saved file by reloading it with Pandas.</li>
    </ul>  
  </li>
</ul>

</details>
<br>
<p>This section highlights my ability to clean and preprocess data systematically, culminating in the creation of a cleaned dataset stored as <code>cleaned_df.csv</code>, which serves as the foundation for further analysis and model development.</p>
