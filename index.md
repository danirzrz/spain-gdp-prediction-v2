
![Predicting Spain's Economic Trends Using World Bank Data](https://github.com/danirzrz/spain-gdp-prediction-v2/blob/main/spain_economy_banner.jpg)

# 📊 Predicting Spain’s Economic Future with Data Science

**Can data science help us understand and forecast the economic future of a country?**  
In this project, I explored key indicators from the World Bank to analyze and predict Spain’s GDP using machine learning. Here's what I discovered.

---

## 🔍 What drives Spain’s GDP?

Using a wide range of development indicators from 2015 to 2024, I analyzed which variables are most correlated with GDP. Among the top indicators were **energy use per capita**, **population**, and **life expectancy**—all of which reflect infrastructure, demographic trends, and public health.

A heatmap of correlations revealed strong relationships between GDP and several metrics, helping guide feature selection for modeling.

![Correlation of Indicators with GDP](https://github.com/danirzrz/spain-gdp-prediction-v2/blob/main/correlation_with_gdp.png)

---

## 📈 How has GDP evolved over time?

Spain’s GDP has shown fluctuations over the past decade, with notable dips during global disruptions and recoveries in recent years. The line plot below illustrates these trends clearly.

![GDP Over Time](https://eu-prod.asyncgw.teams.microsoft.com/v1/objects/0-weu-d21-912082417ac0720c9de8e471d6617139/views/original/generated_image.png)

---

## 💡 Can we predict GDP using other indicators?

Yes! I trained three models to predict GDP:

| Model              | R² Score | RMSE (Error)       |
|--------------------|----------|--------------------|
| Linear Regression  | 0.9441   | \$44.6 billion     |
| Ridge Regression   | **0.9514** | **\$41.57 billion** |
| Random Forest      | 0.8872   | \$63.3 billion     |

The **Ridge Regression model** performed best, showing excellent predictive power and the lowest error. This suggests that regularization helped capture the relationships without overfitting.

---

## 🌍 What is the impact of a hypothetical change in key indicators?

To test the model’s predictive capabilities, I created a hypothetical scenario:

- **Population** increases by 5%
- **Energy use per capita** decreases by 5%
- **Life expectancy** rises by 1 year

Using the trained **Random Forest model**, the predicted GDP under this scenario was significantly higher than the actual value for 2024.

![GDP Prediction Under Hypothetical Scenario](https://eu-prod.asyncgw.teams.microsoft.com/v1/objects/0-weu-d15-57d9f7ba0cb112da6f31348c122db3aa/views/original/generated_image.png)

---

## 🧠 Final thoughts

This project shows how data science can uncover meaningful insights and simulate future outcomes. While models aren’t perfect, they offer a powerful lens for understanding complex systems like national economies.

---

## 🔍 GitHub repository for the code
👉 Spain GDP Prediction on GitHub
