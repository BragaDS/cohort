# Online Sales Analysis

## Overview
This project involves the analysis of online sales data to understand customer retention patterns over time. The key steps in the analysis include data importing, date manipulation, cohort index creation, grouping, counting, and retention visualization.

## Project Structure

- **1. Importing Libraries:**
  - Utilized Pandas for data manipulation.
  - Imported Seaborn and Matplotlib for visualization.

- **2. Data Reading:**
  - Loaded online sales data from a CSV file using Pandas.

- **3. Date Manipulation:**
  - Converted the date column to the datetime format.
  - Extracted the month.
  - Created a DataFrame with the minimum and maximum transaction dates for each customer.

- **4. Cohort Index Creation:**
  - Calculated the cohort index, representing the period in which each customer made their first transaction.

- **5. Grouping and Counting:**
  - Grouped the data by cohort and cohort index.
  - Counted the number of unique customers in each group.

- **6. Retention Visualization:**
  - Calculated retention rates for each cohort and cohort index.
  - Generated a table and a heatmap for visualization.

## Results
The analysis provides insights into customer retention trends over different cohorts, highlighting patterns and fluctuations in customer loyalty.

## Instructions
1. Ensure you have the required libraries installed using `pip install -r requirements.txt`.
2. Run the Jupyter Notebook to reproduce the analysis.

Feel free to explore the code and adapt it to your specific needs.

Happy analyzing!
