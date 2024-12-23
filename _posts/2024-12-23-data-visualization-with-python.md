---
layout: post
title:  "Data Visualization with Python"
date:   2024-12-13 13:26:19 -0500
categories: jekyll update
author: "Olga Durham"
---

[Click to open the file...](https://github.com/shap0011/machine_learning_fall_2024/blob/main/Data_Visualization.ipynb)

The `Data_Visualization.ipynb` file explores data visualization techniques to gain insights, identify patterns, and draw conclusions using Python.

<details>
  <summary>Click to see details</summary>
  
<h4>Visualization Libraries in Python</h4>

<ul>
  <li><strong>Seaborn</strong> and <strong>Matplotlib</strong>
    <ul>
      <li>Install or import Seaborn (<code>import seaborn as sns</code>).</li>
      <li>Import Matplotlib (<code>import matplotlib.pyplot as plt</code>).</li>
      <li>Retrieve sample datasets from the Seaborn library.</li>
      <li>Load the <code>tips</code> dataset (<code>df = sns.load_dataset('tips')</code>).</li>
      <li>Perform data exploration:
        <ul>
          <li>Check variable types.</li>
          <li>Preview the top 5 rows.</li>
          <li>Return a summary of the DataFrame.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul>

<h4>Key Visualization Tasks</h4>

<ul>
  <li><strong>Relationship Between Total Bill and Tip Amount</strong>:
    <ul>
      <li>Use a scatter plot to visualize and analyze the relationship.</li>
      <li>Determine the type of correlation (positive, negative, or none).</li>
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Strip Plot</strong>:
    <ul>
      <li>Visualize average tip amounts by day of the week and time of day:
        <ul>
          <li><code>tip</code> vs. <code>day</code></li>
          <li><code>tip</code> vs. <code>time</code></li>
        </ul>
      </li>
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Bar Plot</strong>:
    <ul>
      <li>Display average tip amounts:
        <ul>
          <li>By day of the week.</li>
          <li>By party size.</li>
          <li>By smoker status.</li>
          <li>By gender.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Pair Plot</strong>:
    <ul>
      <li>Plot pairwise relationships in the <code>tips</code> dataset.</li>
      <li>Use the <code>hue</code> parameter (e.g., by <code>sex</code>).</li>
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Distribution Plot</strong>:
    <ul>
      <li>Use <code>displot()</code> to visualize a univariate variable distribution:
        <ul>
          <li>Plot a histogram with a kernel density estimate (KDE).</li>
          <li>Calculate and annotate the mean, median, and mode.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Count Plot</strong>:
    <ul>
      <li>Visualize counts of observations in each category:
        <ul>
          <li>Create a count plot by day, with <code>time</code> as the hue.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Heatmap</strong>:
    <ul>
      <li>Display correlations as a two-dimensional heatmap:
        <ul>
          <li>Each square represents the correlation between two variables.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Scatter Plot</strong>:
    <ul>
      <li>Customize scatter plots for <code>total_bill</code> vs. <code>tip</code>:
        <ul>
          <li>Experiment with colors, opacity, and shapes of data points.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Bar Plot</strong>:
    <ul>
      <li>Create vertical bar plots to display categorical data:
        <ul>
          <li>Plot smoker and non-smoker counts using Matplotlib.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Pie Plot</strong>:
    <ul>
      <li>Visualize univariate data distribution:
        <ul>
          <li>Plot the occurrence of different days.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Exploded Pie Plot</strong>:
    <ul>
      <li>Separate one or more sectors from the pie:
        <ul>
          <li>Plot the occurrence of days with an exploded view.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Histogram</strong>:
    <ul>
      <li>Analyze the distribution and spread of continuous variables:
        <ul>
          <li>Plot a histogram for the <code>tip</code> variable.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul>

<ul>
  <li><strong>Box Plot</strong>:
    <ul>
      <li>Visualize the five-number summary:
        <ul>
          <li>Plot the boxplot of <code>total_bill</code> to check for outliers.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul> 

<ul>
  <li><strong>Subplots</strong>:
    <ul>
      <li>Create multiple plots within a single canvas:
        <ul>
          <li>Use <code>plt.subplot(numrows, numcols, plot_number)</code> to position plots.</li>
          <li>Add a strip plot to visualize <code>tip</code> vs. <code>day</code>.</li>
        </ul>
      </li>  
    </ul>
  </li>
</ul> 

</details>
<br>
<p>The project highlights the use of powerful visualization libraries like Matplotlib and Seaborn to explore, analyze, and interpret data through various graphical representations, enabling insights into patterns, relationships, and distributions within the dataset.</p>
