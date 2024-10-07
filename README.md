# European-Wine-Analysis
# Project Overview
This project, titled European Wine Analysis, was developed as part of our second-semester coursework for the "Data Mining and Visualization" course. The aim of this project is to provide insights into the relationships between wine ratings, price, and other variables across Europe using a dataset of wine reviews and ratings. The analysis was performed using the R programming language, applying techniques such as Exploratory Data Analysis (EDA) and predictive modeling.

# Case Description
The European Wine Analysis project is focused on understanding wine ratings and their relationship to pricing across several European countries. The dataset used includes wine reviews from various countries, but this analysis is narrowed down to European countries only, such as France, Italy, Spain, Portugal, and others.

Our project aims to assist restaurant owners in selecting wines that provide excellent quality at an affordable price. We believe that offering the right selection of wines can enhance the dining experience for customers, while also maximizing profit for restaurant owners. To do this, we conducted exploratory data analysis to understand the relationships between several features, including ratings (points), price, variety, and region.

# Objectives
- Analyze wine ratings and pricing in Europe to determine relationships between quality and cost.
- Help restaurant owners by identifying wines that provide high quality at a reasonable price.
- Build a predictive model to estimate wine ratings based on other features, such as price and region.
- Provide visualization of the data to facilitate understanding of important insights.

# Project Steps and Features
The project was divided into several steps, covering both exploratory data analysis and predictive modeling:
1. Data Collection
- We used a dataset containing wine reviews from different regions. The dataset was filtered to include only European countries, such as France, Italy, Spain, Greece, and Germany.
- Variables included in the dataset were Points (Rating), Variety, Price, Country, Region, and more.

2. Understanding Variables and Cleaning the Dataset
- We performed a summary analysis to understand the dataset's structure, including the number of missing values, data types, and descriptive statistics.
- Missing values were handled carefully: Variables with high percentages of missing values, such as Region 2, were removed. Duplicate rows and NA values were also removed to improve data quality.

3. Data Visualization and Analysis
- We used ggplot2 and other libraries to create various visualizations.
- Correlation Analysis: We examined relationships between points (ratings) and other variables such as price, variety, and region using methods like ANOVA, Spearman correlation, and Chi-square tests.
- We visualized relationships to understand how wine ratings are influenced by factors such as price and country of origin.

4. Key Insights from EDA
- Rating vs. Price: Our analysis showed that wines with higher ratings tend to be more expensive. However, this relationship is not always perfectly linear, and there are exceptions.
- Country Analysis: We identified that the top wine-producing countries based on the number of wines in the dataset were Italy, France, and Spain.
- Best Deal Wines: We identified the top wines that offered the best value based on a combination of high ratings and low prices. For example, Red Blend from Italy was identified as an affordable wine with a high rating.

5. Predictive Modeling
- We built a predictive model to predict wine ratings based on features such as price and country using Random Forest and Linear Regression models.
- The predictive model performed relatively poorly, with an accuracy of only 21.6%, as the data did not follow a normal distribution and contained many outliers. The scatter plots showed that the data points were not closely clustered around the prediction line, indicating low accuracy.

# Tools and Technologies Used
- Language: R Programming
- Libraries: ggplot2, dplyr, randomForest, caret, tidyr, and others.

# Challenges
- Missing Values: Handling missing values was challenging, as several variables had significant missing data, requiring careful decisions about whether to impute or remove them.
- Outliers and Data Distribution: The price variable contained many outliers, making predictive modeling difficult. The lack of normal distribution among key variables impacted model accuracy.
- Predictive Model Performance: The predictive model's accuracy was not satisfactory, indicating that further work is needed to improve the model by trying different techniques, feature engineering, or more sophisticated machine learning algorithms.

# Conclusion
The European Wine Analysis project provided valuable insights into how wine ratings and prices are related, helping us identify wines that are both high quality and affordable. However, the predictive modeling component still requires further refinement, as the current accuracy is not sufficient for practical use. This project was a great learning experience in data analysis, visualization, and modeling using R, and it highlighted the complexities of working with real-world data.
