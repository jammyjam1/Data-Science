# Analysis Contents

## Exploratory Data Analysis

The 01_Exploratory_Data_Analysis.ipynb notebook covers the following:

Loading and initial exploration of historical customer data and pricing data.
Descriptive statistics including data types, summary statistics, and variable distributions.
Data visualization using various plots and charts to understand the data distribution and relationships.

### Data Visualization and Analysis with Python
This Python script uses data visualization techniques to analyze and visualize various aspects of a dataset related to customer churn in a company.

#### Stacked Bar Plots

The plot_stacked_bars() function creates stacked bar plots to visualize the distribution of churned and retained customers across different categories.

Churning status: Shows the percentage of customers who have churned versus those retained.
Sales channel: Illustrates the distribution of churned customers across different sales channels. It identifies that customers who churn are present across multiple sales channels, including a category labeled as "MISSING" with a 7.6% churn rate. The "MISSING" category, indicating missing values, could be a significant feature for predictive modeling.

#### Histograms for Consumption Data

The script utilizes histograms via the plot_distribution() function to analyze the distribution of consumption-related attributes:

**cons_12m:** Displays the distribution of annual consumption.

**cons_gas_12m:** Visualizes gas consumption for customers who have gas service.

**cons_last_month:** Shows the distribution of consumption for the last month.

**imp_cons:** Analyzes the importance of consumption data.

## Observations and Insights

Skewness in Consumption Data: The histograms reveal that consumption data is highly positively skewed, suggesting a long right tail towards higher values. This skewness indicates the presence of outliers, particularly towards the higher end of the consumption distribution.
Outliers Detection: To further analyze outliers and understand the data distribution, a boxplot can be used. It showcases key statistical measures like minimum, first quartile (Q1), median, third quartile (Q3), and maximum values. This plot assists in identifying the presence of outliers and assessing the symmetry and dispersion of the data.
Use in Model Building

Understanding the distribution and characteristics of churn-related features like sales channels and consumption data is crucial for developing predictive models. Features such as "MISSING" in the sales channel data and outlier detection in consumption data can significantly impact model performance and prediction accuracy.

Include these explanations in your README.md to help others understand how the code conducts data visualization and its implications for modeling customer churn. Feel free to add code snippets, visuals, or further explanations to enhance clarity and comprehension.

## Hypothesis Verification
The 02_Hypothesis_Verification.ipynb notebook investigates the hypothesis of price sensitivity's correlation with churn. 
It defines price sensitivity, performs calculations, and explores the relationship between price and churn indicators.

