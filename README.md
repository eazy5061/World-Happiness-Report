# World-Happiness-Report
[![made-with-RStudio](https://img.shields.io/badge/Made%20with-RStudio-white.svg)]((https://posit.co/products/open-source/rstudio/))
[![Generic badge](https://img.shields.io/badge/STATUS-COMPLETED-green.svg)](https://shields.io/)
[![LinkedIn Connect](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/hongliang-tea/)

The aim of this project is to analyze a public dataset taken from Kaggle to find out what are the parameters that influences happiness in the world. The World Happiness Report dataset provides annual insights into global happiness rankings based on factors like GDP per capita, social support, life expectancy, freedom, generosity, and corruption perceptions. This analysis aims to explore these factors to understand what influences happiness across different countries. I will be using R programming which I learnt from Google Data Analyst course to analyze this dataset for year 2019.

<br>

## Project Goals
1. Start the project by extracting the dataset, cleaning, modelling, and deploying the model
2. To **identify** the factors/drivers that influences happiness.
3. To **conclude** the analysis and **suggest** recommendations based on the findings.

<br>

## About the Data
The dataset was extract from [www.kaggle.com](https://www.kaggle.com/datasets/unsdsn/world-happiness) and it contains 156 rows and 9 columns.

<br>

## Exploratory Data Analysis
### Heatmap
<img src="6. Heatmap.png" alt="Screenshot of dashboard" width="1000" height="800">

<b><ins>Findings:</ins></b>
<br>
Strongest Positive Correlations:
* Score and GDP per Capita (0.79): Higher GDP per capita correlates with higher Happiness Scores.
* Score and Social Support (0.78): Strong social support networks are associated with higher Happiness Scores.
* Score and Healthy Life Expectancy (0.78): Higher life expectancy correlates with higher Happiness Scores.

<br>

### Mean and Median
<img src="7. Mean and Median.png" alt="Screenshot of dashboard" width="300" height="150">

* From the calculated values, we will use the mean values of each parameters to determine those countries that are higher than average.

<br>

### Countries with higher than average happiness score, GDP, Healthy and Social
<img src="8. Tables.png" alt="Screenshot of dashboard" width="850" height="700">

<b><ins>Findings:</ins></b>
<br>
* From the table above, we can see that top 10 countries are mostly from Europe and only New Zealand is a non-Europe country. Singapore is ranked number 33.

<br>

### Relationship between Happiness Score vs GDP by countries
<img src="9. Happiness vs GDP.png" alt="Screenshot of dashboard" width="1100" height="800">

<b><ins>Findings:</ins></b>
<br>
* Based on the scattter plot above, countries with high happiness score vs GDP are mostly from Europe and only New Zealand is a non-Europe country. 

<br>

### Relationship between Happiness Score vs Social Support by countries
<img src="10. Happiness vs Social.png" alt="Screenshot of dashboard" width="1300" height="800">

<b><ins>Findings:</ins></b>
<br>
* Based on the scatter plot above for Happiness Score vs Social Support, there are a number of countries from Europe and a few non-Europe countries which are New Zealand. Australia, Canada and Costa Rica are having high scores.

<br>

### Relationship between Happiness Score vs Healthy Life Expectancy  by countries
<img src="11. Happiness vs Health.png" alt="Screenshot of dashboard" width="1300" height="800">

<b><ins>Findings:</ins></b>
<br>
* Based on the scatter plot above for Happiness Score vs Healthy Life Expectancy, there are a number of countries from Europe and a few non-Europe countries which are Canada and Costa Rica are having high scores.

<br>

## Summary
### Conclusion:
* The analysis provides valuable insights into the multifaceted nature of happiness and well-being. It emphasizes the interconnectedness of economic, social, and health factors in determining happiness.
* Policymakers or researchers can use these insights to target areas for improvement and enhance overall happiness.

<br>

### Recommendations:
* Policies aimed at increasing GDP per capita can have a significant positive impact on happiness.
* Strengthening social networks and support systems is crucial for improving happiness.
* Ensuring access to quality healthcare and promoting healthy lifestyles can boost life expectancy and overall happiness.

<br>

Connect to my LinkedIn
<br>
[![LinkedIn Connect](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/hongliang-tea/)






