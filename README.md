# E-Commerce Sales Analysis

This project analyzes e-commerce sales data, examining monthly sales patterns, sales by category, and top revenue-generating products to provide actionable insights. The analysis was performed using Python with libraries such as Pandas, Matplotlib, and Seaborn for data manipulation and visualization.

## Project Overview

- **Objective**: To analyze sales data to understand monthly trends, sales by category, and identify top products by revenue.
- **Data Source**: CSV file containing monthly sales for various product categories.
- **Tools**: Python (Pandas, Matplotlib, Seaborn), Jupyter Notebook.

## Data Preparation

1. **Data Loading**: Loaded data using Pandas `pd.read_csv`.
2. **Data Cleaning**:
   - Renamed columns for clarity (e.g., `sales_month_1` to `Jan`).
   - Verified column data types with `df.dtypes`.
   - Checked unique values in `category` using `df['category'].unique()` to understand the variety of categories.

## Analysis Questions

Here are some analytical questions explored in this project:

1. What are the monthly sales trends across different product categories?
2. Which categories generate the highest and lowest sales?
3. What are the top 10 products by revenue?
4. Is there a correlation between product price and review score?
5. What is the average review score by category?

## Visualizations

Various visualizations were created to support the analysis, including:

- **Line Chart**: Monthly sales trends by category.
- **Horizontal Bar Chart**: Top 10 products by revenue.
- **Scatter Plot**: Correlation between product price and review score.
- **Bar Chart**: Total sales by category, arranged from highest to lowest.
- **Pie Chart**: Proportion of average review score by category.

## Key Insights

Some insights derived from the analysis:

1. **Monthly Trends**: Certain months show higher sales peaks, indicating potential seasonal influences.
2. **Category Performance**: Specific categories consistently outperform others in sales.
3. **Top Products**: The top 10 products by revenue show high-performing items in specific categories.
4. **Price vs. Reviews**: Moderate correlation found between product price and review score.
5. **Review Scores**: The average review score by category highlights customer satisfaction across product types.

## Conclusion

This analysis provides valuable insights into e-commerce sales patterns, enabling data-driven decisions to optimize product offerings and pricing strategies. Future recommendations include incorporating additional data on customer demographics and seasonal factors for a deeper understanding.

## Usage

To replicate this analysis:

1. Clone the repository and open the Jupyter notebook.
2. Ensure all necessary Python libraries are installed (`Pandas`, `Matplotlib`, `Seaborn`, and optionally `Plotly` for interactive visuals).
3. Run the notebook cells to load the data, perform the analysis, and generate the visualizations.

---

**Note**: This project is part of a broader data analysis portfolio, utilizing Python and data visualization techniques to gain actionable insights.

## Contact

For questions or feedback, feel free to reach out!

