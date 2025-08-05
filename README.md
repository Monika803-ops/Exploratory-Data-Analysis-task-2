# Task 2: Life Expectancy Data Analysis

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
   Loaded the dataset using Pandas and printed the first few rows, shape, summary statistics, and missing values.

2. **Missing Value Handling**  
   Filled missing values in numeric columns with their respective column means.

3. **Histograms**  
   Plotted histograms of all numeric features to understand their distributions.

4. **Boxplots**  
   Created boxplots for:
   - Life expectancy for men
   - Life expectancy for women

5. **Correlation Heatmap**  
   Computed and visualized the correlation matrix to identify strong positive or negative relationships between variables.

6. **Scatter Plots with Plotly**  
   Plotted GDP vs life expectancy for both men and women, colored by country status.

7. **Status-wise Boxplots**  
   Compared life expectancy between Developed and Developing countries using boxplots for both genders.

## Libraries Used

- `pandas`
- `matplotlib`
- `seaborn`
- `plotly`

## How to Run

1. Make sure the dataset file `Life Expectancy Data v2.csv` is in the same folder as the Python script.
2. Install required libraries (if not already installed):
   ```bash
   pip install pandas matplotlib seaborn plotly
