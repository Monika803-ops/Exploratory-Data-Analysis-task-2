# Task 2: Exploratory Data Analysis (EDA)

This project analyzes the "Life Expectancy Data v2.csv" dataset using Python libraries such as Pandas, Matplotlib, Seaborn, and Plotly. The goal is to understand trends and patterns in life expectancy across different countries, genders, and economic statuses.

## Dataset

The dataset contains life expectancy information for men and women, GDP, and country status (Developed or Developing), along with other health and economic indicators. Some values may be missing and are handled appropriately in this project.

## Objectives

- Explore the structure and basic statistics of the dataset
- Handle missing values
- Visualize data distribution using histograms and boxplots
- Analyze correlations between numerical features
- Explore the relationship between GDP and life expectancy
- Compare life expectancy based on country status

## Steps Performed

1. **Data Loading**  
   Loaded the dataset using Pandas and printed the first few rows, shape, data types, and checked for missing values.

2. **Missing Value Handling**  
   Filled missing values in all numeric columns with their column-wise mean using Pandas.

3. **Histograms**  
   Created histograms to see how numeric data is distributed across the dataset.

4. **Boxplots**  
   Created boxplots to detect outliers and compare life expectancy for:
   - Men
   - Women

5. **Correlation Heatmap**  
   Used Seaborn to generate a heatmap showing how strongly each numeric column is related to others.

6. **Scatter Plots using Plotly**  
   Created interactive scatter plots to explore:
   - GDP vs Life Expectancy (Men)
   - GDP vs Life Expectancy (Women)  
   Colored points by country status (Developed or Developing).

7. **Status-wise Boxplots**  
   Plotted separate boxplots comparing life expectancy for:
   - Men by country status
   - Women by country status

## Libraries Used

- `pandas` – for data loading and manipulation
- `matplotlib` – for plotting static charts
- `seaborn` – for statistical plots like heatmaps and boxplots
- `plotly.express` – for interactive scatter plots

## How to Run

1. Make sure Python is installed on your system.
2. Place the file `Life Expectancy Data v2.csv` in the same folder as the Python script.
3. Install the required Python libraries if not already installed:
   ```bash
   pip install pandas matplotlib seaborn plotly
