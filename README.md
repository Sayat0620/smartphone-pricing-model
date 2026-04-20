# Smartphone Specifications and Market Price Analysis

## Project Overview
A statistical study was conducted to evaluate the relationship between technical specifications and market prices across major smartphone brands (Apple, Samsung, Xiaomi).

## Dataset
A custom dataset of 50 popular smartphone models (2021–2025) was compiled, including hardware metrics (Antutu scores, RAM, Storage) and retail prices in EUR.

## Tech Stack
* **Statistics:** Python (SciPy, Statsmodels)
* **Testing:** Welch’s t-test, One-way ANOVA, Shapiro-Wilk test
* **Modeling:** Multiple Linear Regression

## Methodology
* **Hypothesis Testing:** **Welch’s t-test** was performed to investigate if wireless charging significantly impacts the price of budget-segment phones.
* **Brand Comparison:** **One-way ANOVA** was utilized to compare performance metrics (Antutu scores) across different manufacturers at similar price points.
* **Regression Modeling:** A **Multiple Linear Regression** model was constructed to quantify the impact of individual hardware specs on the final retail price.

## Key Results
* **Key Drivers:** Hardware performance (Antutu) and storage capacity were identified as the strongest predictors of price.
* **Market Insight:** It was determined that wireless charging has lost its "premium" status in the budget segment and does not significantly increase device cost.
* **Model Accuracy:** The regression analysis revealed that while technical specs are important, brand perception remains a significant factor in pricing.

## Team Contribution
This project was completed individually. Tasks included data collection, statistical hypothesis testing, and building the regression model.
