# Customer Churn Analysis

This project analyzes customer cancellation behavior using Python and data analysis tools.

The goal is to identify patterns that explain why customers cancel services and generate insights that could help reduce churn rates.

---

# Technologies Used

- Python
- Pandas
- Plotly
- Jupyter Notebook

---

# Project Structure

The project follows these steps:

1. Data Import
2. Data Cleaning
3. Exploratory Data Analysis
4. Data Visualization
5. Insights and conclusions

---

# Data Cleaning

Missing values were removed to ensure dataset consistency.

```python
tabela = tabela.dropna()
```
---

# Exploratory Analysis

The cancellation rate was analyzed using frequency counts.

```python
tabela["cancelou"].value_counts()
```
Histograms were generated to understand how variables affect churn.

---

# Key Insights

- Customers with monthly plans cancel more frequently
- Late payments increase cancellation probability
- Customers with many support interactions are more likely to cancel

---

# Future Improvements

- Build a machine learning model to predict churn
- Create dashboards for visualization
- Automate reports

---

# Author

Developed as part of a data analysis learning project.

---