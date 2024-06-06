### README

# NYC Taxi and Limousine Commission Vendor Performance Analysis

## Problem Statement

The NYC Taxi and Limousine Commission (NYC TLC) seeks to analyze the performance of two vendors based on various metrics such as trip distance, passenger count, and total amount. The goal is to determine which vendor is more valuable or profitable. This analysis aims to provide insights that can help increase profit and inform recommendations on vendor selection.

## Business Problem

### Objective

To analyze vendor performance in order to increase profit and identify the key factors that affect profit.

### Questions to Address

1. Which vendor (Vendor 1 or Vendor 2) is more profitable?
2. What are the key metrics that contribute to the profitability of each vendor?

## Conclusion

### Correlation Analysis

- **Tip Amount**: Shows a strong positive correlation with profit (0.93).
- **Fare Amount**: Has a moderate positive correlation with profit (0.38).

### Temporal Trends

- **Monthly Trends**: Consistent profitability with higher profits for Vendor 2 across all months.
- **Daily Trends**: Higher profits on weekdays compared to weekends for both vendors.
- **Hourly Trends**: Peak profitability hours are similar for both vendors, typically during evening and night.

### Vendor Profitability

- **Vendor 2**: Significantly more profitable than Vendor 1, with a total profit of $169,070.63 compared to Vendor 1's $7,788.34.
- **Average Profit per Trip**: Vendor 2 has a higher average profit per trip ($2.99) compared to Vendor 1 ($1.01).

## Repository Structure

- **data/**: Contains the dataset used for the analysis.
- **notebooks/**: Jupyter notebooks for data cleaning, exploration, and analysis.
- **visualizations/**: Tableau workbooks and screenshots of the key visualizations.
- **README.md**: Overview of the project, problem statement, business problem, conclusion, and instructions.

## Instructions

1. **Clone the repository**:
    ```sh
    git clone https://github.com/rahasyae/Vendor-Performance-NYC-TLC-January-2023.git
    ```

2. **Data Preparation**:
    - The dataset is located in the `data/` directory. Ensure the CSV file is in the correct format before proceeding.

3. **Analysis Notebooks**:
    - Open the Jupyter notebooks in the `notebooks/` directory to explore and analyze the data. The notebooks include steps for data cleaning, feature engineering, and visualization preparation.

4. **Visualizations**:
    - Visit my dashboard visualization in [Tableau](https://public.tableau.com/views/VendorPerformanceNYCTLCDasboard/Dashboard1?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link)

5. **Review Findings**:
    - Review the conclusion section in this README to understand the key insights and recommendations from the analysis.

By following these steps, you can replicate the analysis and gain insights into the performance of the NYC taxi vendors. This analysis will help in making informed decisions to enhance profitability and service quality.

