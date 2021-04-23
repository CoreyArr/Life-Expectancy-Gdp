

# *Life-Expectancy-GDP EDA*

## Author
### Corey Arrington

## Project Goals 

- Explore data set to discover trends, anomalies, and correlations to rates.
- Clean and optimize data set for visualizations.
- Create clear and insightful visualizations to describe and showcase findings.



## Table of Contents

<details>
    <summary>Open</summary>

        1. File Descriptions
        2. Technologies Used
        3. Executive Summary

</details>

## File Descriptions

<details>
    <summary>Open</summary>

- insurance.csv: data pre-clean
- Medical Insurance Project.ipynb: Jupyter Notebook on data analysis

</details>

## Technologies Utilized

<details>
    <summary>Open</summary>

        1. Python3
        2. Pandas
        3. Matplotlib
        4. Seaborn
        5. Numpy
</details>

 ## Executive Summary


<details>
    <summary>Open</summary>
    <h3>Data Cleaning</h3>
    <h4>Primary Goal</h4>
    <p>My goals in this project were to demonstate my ability to abilities as an analyst while exploring new methods and tools for data visualizations. I did this by identifying any trends or correlations, looking for anomalies, then finally optimizing the data for visualizations.    
  </p>
  

### Library Imports
<details>
    <summary>Part 1</summary>
    <h3>Importing required libraries and loading into dataframe</h3>
    <p>The required libraries included the utilization of primarily pandas, matplotlib, and seaborn.</p>

</details>

<details>
    <summary>Part 2</summary>
    <h3>Early EDA</h3>
    <p>This portion focused primarily on understanding the key statistics and evaluation of the dataframe. These findings were as follows:
    <h5>Max Values</h5>
<p>The max values show a high of 81 in Life expectancy at birth and 1.810000e+13 in GDP.</p>

<h5>Min Values</h5>
<p>The min values show a low of 44 in Life expectancy at birth and 4.415703e+09 in GDP.</p>

<h5>Average Values</h5>
<p>The average values show an average of 72.7 in Life expectancy at birth and 3.880499e+12 in GDP.</p>
</details>
<details>
    <summary>Part 3</summary>
    <h3>Data Visualizations</h3>
    <h5>Histogram: Life Expectancy at Birth </h5>
<img src="https://github.com/CoreyArr/Life-Expectancy-Gdp/blob/main/Images/LifeExpectancy_Hist.png?raw=true" alt="Histogram: Life Expectancy at Birth">
   ---
    <h5>Histogram: GDP</h5>
<img src="https://github.com/CoreyArr/Life-Expectancy-Gdp/blob/main/Images/GDP_Hist.png?raw=true" alt="Histogram: GDP">
    ---
    <h5>Heatmap: Correlation</h5>
<img src="https://github.com/CoreyArr/Life-Expectancy-Gdp/blob/main/Images/Heatmap.png?raw=true" alt="Heatmap: Correlation">
   ---
    <h5>Scatterplot: Averages</h5>
<img src="https://github.com/CoreyArr/Life-Expectancy-Gdp/blob/main/Images/ScatterAVG.png?raw=true" alt="Scatterplot: Averages">
    ---
    <h5>Line Chart: GDP</h5>
<img src="https://github.com/CoreyArr/Life-Expectancy-Gdp/blob/main/Images/GDP_Line.png?raw=true" alt="Line Chart: GDP">
</p>
    ---
    <h5>Line Chart: Life expectancy</h5>
<img src="https://github.com/CoreyArr/Life-Expectancy-Gdp/blob/main/Images/LifeExpectancy_Line.png?raw=true" alt="Line Chart: Life expectancy">
</p>
    ---
     <h5>Bar Plot: Life expectancy</h5>
<img src="https://github.com/CoreyArr/Life-Expectancy-Gdp/blob/main/Images/LifeExpecrancy_Bar.png?raw=true" alt="Bar Plot: Life expectancy">
</p>
    <h5>Bar Plot: GDP</h5>
<img src="https://github.com/CoreyArr/Life-Expectancy-Gdp/blob/main/Images/GDP_Bar.png?raw=true" alt="Bar Plot: GDP">
</p>
    ---
    <h5>Scatter Plot: Life expectancy vs GDP</h5>
<img src="https://github.com/CoreyArr/Life-Expectancy-Gdp/blob/main/Images/ScatterCombined.png?raw=true" alt="Scatter Plot: Life expectancy vs GDP">
</p>
    ---
    <h5>Scatter Plot: Life expectancy vs GDP</h5>
<img src="https://github.com/CoreyArr/Life-Expectancy-Gdp/blob/main/Images/Scatter_Seperated.png?raw=true" alt="Scatter Plot: Life expectancy vs GDP">
</p>
    ---
    
</details>

<details>
    <summary>Part 4</summary>
    <h3>Summarizing Findings</h3>
    <h4>Who pays more in medical insurance and why?</h4>
    <p>
        The data shows a strong correlation between life expectancy and GDP at 34%. The year also correlates to life expectancy, but that's to be expected since technology and medicaine improve over, thus increasing life expectancy. I find it interesting that the country with the lowest average GDP also shares the lowest average life expectancy while the country with the highest average GDP doesn't have the hightest average life expectancy.</p>
    <div>
    </div>
</details>
