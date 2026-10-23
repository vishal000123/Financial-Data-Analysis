# Financial Data Analysis

A Python-based financial analytics project that explores transaction data, spending patterns, expense categories, and budget performance using data cleaning, exploratory data analysis (EDA), and visualization.

## Project Objectives

- Clean and preprocess financial datasets.
- Analyze spending across categories and expense types.
- Identify monthly spending trends.
- Compare observed transaction spending against available budget records.
- Generate visualizations and actionable financial insights.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
Financial-Data-Analysis/
├── Data/
│   ├── transactions.csv
│   ├── budgets.csv
│   └── categories.csv
├── Notebooks/
├── Reports/
│   ├── cleaned_transactions.csv
│   ├── cleaned_budgets.csv
│   ├── cleaned_categories.csv
│   └── Financial_Analysis_Report.md
├── Financial_Data_Analysis.ipynb
└── README.md
```

## Key Findings

| Metric | Result |
|---|---:|
| Total transactions | 761 |
| Total observed spending | ₹262,983.73 |
| Average transaction | ₹345.58 |
| Highest-spending category | Travel |
| Highest-spending month | November 2023 |
| Lowest-spending month | February 2022 |
| Fixed expenses | ₹126,457.04 |
| Variable expenses | ₹71,590.54 |
| Discretionary expenses | ₹64,936.15 |

## Budget Analysis

The initial analysis evaluated 197 valid budget records:
- 193 classified as within budget.
- 4 classified as over budget.

**Important limitation:** Budgets without matching transactions in their date ranges were assigned zero observed spending. These results should not be interpreted as proof that those budgets had no actual expenses.

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Open Jupyter Notebook from the project directory.
4. Open `Financial_Data_Analysis.ipynb`.
5. Run the notebook cells in order.

## Reports

The `Reports/` folder contains cleaned datasets and the financial analysis report.

## Future Improvements

- Improve budget-to-transaction matching.
- Investigate inconsistent budget date ranges and missing budget amounts.
- Add interactive dashboards.
- Introduce additional financial KPIs and forecasting.
