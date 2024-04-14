# Festival-Data-Analysis
This analysis explores various aspects of sales data, including data cleaning, visualization, and insights generation. Here's a breakdown of the steps and visualizations conducted:

**Data Cleaning:**

The sales data is loaded from a CSV file into a Pandas DataFrame named Sale. The DataFrame is examined for missing values using .isnull().sum() and .info() methods. Missing values in the 'Amount' column are identified. Data Exploration and Cleaning Continued:

Rows with missing values in the 'Amount' column are removed using .dropna().
The data types of the 'Amount' column are converted to integers. The column names are cleaned up to improve readability using .columns assignment. A summary of descriptive statistics for numerical columns is generated using .describe().
**Data Aggregation and Visualization:**

A pivot table is created to analyze the relationship between age groups and marital status, with the total purchase amount as the value. The top-selling product categories are identified by aggregating sales amounts and visualized using a bar plot. The count of orders is visualized using a countplot, revealing the distribution of order counts.
Gender distribution among customers is visualized using a countplot with labels displayed on top of the bars. The count of customers in each age group by gender is visualized using a countplot with hue representation. The total sales amount per age group is calculated and visualized using a bar plot.
The total number of orders per state is calculated and visualized using a bar plot, with x-axis labels rotated for better readability. The relationship between marital status, gender, and purchase amount is analyzed and visualized using a bar plot with hue representation. Customizing Visualizations:

The figure size for Seaborn plots is set to (25, 10) using sns.set(rc={'figure.figsize' :(25,10)}) to enhance visibility.
A count plot of occupations is customized with sorted order and rotated x-axis labels.
Final Visualization:

The top-selling product categories are visualized with a bar plot, with x-axis labels rotated for better readability.
This analysis provides insights into various aspects of sales data, including customer demographics, product preferences, and regional sales distribution, aiding in decision-making and strategy formulation.

