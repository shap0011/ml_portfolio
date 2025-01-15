---
layout: post
title:  "Model Training"
date:   2025-01-14 13:26:19 -0500
categories: jekyll update
author: "Olga Durham"
---

# Model Training

[Click to open the file...](https://github.com/shap0011/machine_learning_fall_2024/blob/main/Real_Estate_Solution.ipynb)

This project, the <code>Real_Estate_Solution.ipynb</code> file, leverages scikit-learn to build and evaluate predictive models, focusing on real estate price prediction using techniques like Linear Regression, Decision Trees, and Random Forests.

<details>
  <summary>Click to see details</summary>
  <br>
<h4>scikit-learn</h4>
<p>scikit-learn (sklearn) offers simple and efficient tools for predictive data analysis. It is built on essential Python libraries, including NumPy, SciPy, and Matplotlib.</p>
<ul>
  <li><strong>Mounting Google Drive in Google Colab:</strong>
    <ul>
      <li>Enables seamless access to files stored in Google Drive for data loading.</li>
    </ul>
  </li>
  <li><strong>Importing Required Libraries:</strong>
    <ul>
      <li><strong>Pandas:</strong> For manipulating and analyzing data in DataFrames.</li>
      <li><strong>NumPy:</strong> For numerical computations.</li>
      <li><strong>Matplotlib.pyplot:</strong> For data visualization.</li>
      <li>Enable inline plotting within the notebook to visualize results interactively.</li>
    </ul>
  </li>
  <li><strong>Importing the Data (<code>final.csv</code>):</strong>
    <ul>
      <li>Load the dataset into a Pandas DataFrame.</li>
    </ul>
  </li>
  <li><strong>Exploring the Dataset:</strong>
    <ul>
      <li>Display the first five records using the <code>.head()</code> function.</li>
      <li>Display the last five records using the <code>.tail()</code> function.</li>
      <li>View the DataFrame's dimensions using the <code>df.shape</code> attribute.</li>
    </ul>
  </li>
</ul>

<h2>Linear Regression Model</h2>

1. Import the Linear Regression model from <code>sklearn.linear_model</code>.  
2. Separate input features into <code>x</code>.  
3. Store the target variable in <code>y</code>.  

<h2>Train-Test Split</h2> 

1. Import the <code>train_test_split</code> function from <code>sklearn.model_selection</code>.  
2. Split the dataset into training and testing subsets.  
3. Train the Linear Regression model.  
4. Display the model's coefficients (<code>coef_</code>) and intercept.  
5. Make predictions on the training dataset.  
6. Evaluate the model using the Mean Absolute Error (MAE) metric from <code>sklearn.metrics</code>.  

<h2>Decision Tree Model</h2>   

1. Import the Decision Tree Regressor from <code>sklearn.tree</code>.  
2. Create an instance of the Decision Tree class.  
3. Train the Decision Tree model.  
4. Make predictions using the test dataset.  
5. Evaluate the model using MAE.

<ul>
  <li><strong>Checking for Overfitting or Generalization:</strong>
    <ul>
      <li>Make predictions on the training dataset.</li>
      <li>Evaluate the model's performance using MAE to determine if it overfits or generalizes well.</li>
    </ul>
  </li>
  <li><strong>Visualizing the Decision Tree:</strong>
    <ul>
      <li>Retrieve the feature names.</li>
      <li>Plot the Decision Tree, including feature names.</li>
      <li>Save the visualization as <code>tree.png</code>.</li>
    </ul>
  </li>
</ul>

<h2>Random Forest Model</h2> 

1. Import the Random Forest Regressor from <code>sklearn.ensemble</code>.  
2. Create an instance of the Random Forest model.  
3. Train the Random Forest model.  
4. Make predictions on the training and testing datasets.  
5. Evaluate the model's performance using MAE.  

<h2>Pickle for Model Serialization</h2>  

1. Import the <code>pickle</code> module to save the trained model.  
2. Save the model using <code>pickle.dump()</code>.  
3. Load the saved model using <code>pickle.load()</code>.  
4. Use the loaded model to make predictions on new data.  

</details>

<p>Through model training and evaluation, including feature engineering and error analysis, the project aims to achieve a robust real estate prediction model, integrating tools like Pickle for serialization to ensure reproducibility and deployment..</p>