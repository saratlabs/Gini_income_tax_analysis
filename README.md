**Income Tax vs Gini Coefficient Study**

Exploring How Progressive Taxation Impacts Income Inequality

**Overview**
*This project investigates the relationship between income tax rates and income inequality (measured via the Gini coefficient) across four countries: Germany, Netherlands, Sweden, and India.*
*Due to limited access to clean longitudinal data, we used simulated datasets for the years 2000 to 2023, aiming to demonstrate how multivariate regression can capture key policy effects.*

**Techniques Used**

1. Simulated Data Generation

2. Multivariate Linear Regression

3. Gini Index (Pre-Tax vs Post-Tax)

4. Data Visualization (Seaborn, Matplotlib)

5. Statistical Interpretation & Reporting

Project Structure
gini_income_tax_analysis/
│
├── data/
│   ├── simulated_gini_data.csv
│   ├── simulated_tax_rates.csv
│   └── merged_data.csv
│
├── outputs/
│   ├── gini_trend_plot.png
│   ├── tax_rate_plot.png
│   ├── tax_vs_gini_scatter.png
│   ├── correlation_matrix.png
│   ├── regression_predictions.png
│   ├── tax_vs_gini_with_fit.png
│   └── regression_summary.txt
│
├── 01_data_simulation.ipynb
├── 02_exploratory_data_analysis.ipynb
├── 03_regression_model.ipynb
└── 04_result_summary.ipynb


**Key Findings**

Metric	Value
R² Score	0.8060
RMSE	0.0266

*A 1% increase in income tax rate leads to a 0.0041 reduction in the post-tax Gini coefficient.*

*India shows structurally higher inequality (+6.9 Gini points) even after adjusting for tax rates.*

*Model shows good fit and statistical validity for simulated policy analysis.*

**Conclusion**

Progressive taxation plays a significant role in reducing income inequality.
However, country-specific structural policies are equally critical.
This project demonstrates how even lightweight econometric models can generate actionable public policy insights.

Author
Sai Sarat Chandra
📍 Chennai, India | 🎓 Economics | 💼 Data Science Learner
