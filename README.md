# Spain Economic Analysis

This project is part of the Udacity Data Scientist Nanodegree. It analyzes Spain's economic development indicators using data from the World Bank, following the CRISP-DM methodology. The goal is to understand the relationship between various indicators and GDP, and to build predictive models.

---

## 📌 Motivation

Understanding the drivers of economic growth is crucial for policy-making and forecasting. This project explores which indicators most influence Spain's GDP, how GDP has evolved over time, and whether it can be accurately predicted using other metrics.

---

## 📚 Libraries Used

- `pandas` – Data manipulation
- `numpy` – Numerical operations
- `matplotlib` & `seaborn` – Data visualization
- `scikit-learn` – Machine learning models and evaluation
---

## 📁 Repository Structure
- `data/spain_data_wide.csv`: Cleaned dataset containing Spain's development indicators from 2015 to 2024.
- `src/Spain_Economic_Analysis.py`: Python script performing data cleaning, modeling, and visualization.
- `reports/figures/`: Folder for saving generated plots and charts.
- `README.md`: Project overview and documentation.

---

## 📊 Summary of Results

- **Top Correlated Indicators**: Energy use, population, and life expectancy show strong correlation with GDP.
- **Modeling**: Ridge Regression achieved the best performance with:
  - **R² Score**: 0.9514
  - **RMSE**: \$41.57 billion
- **Scenario Simulation**: A hypothetical increase in population and life expectancy, and decrease in energy use, led to a predicted GDP increase using the Random Forest model.

---

## 🙏 Acknowledgements

- **World Bank** – For providing the dataset.
- **Udacity** – For the Data Scientist Nanodegree framework.
- **Community Resources** – StackOverflow, Kaggle, and official documentation for troubleshooting and best practices.

---

## 🚫 Academic Integrity

This project is my own work. I have not used another student's code. External resources were used only for reference and learning.

