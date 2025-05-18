# Price-Optimization-with-Python

**Overview**
This project explores how data-driven strategies can help refine pricing decisions by analyzing internal sales data against competitor benchmarks. By leveraging data visualization and machine learning specifically a Random Forest Regression model—we aimed to identify the price point that would optimize revenue while staying competitive in the market.

The analysis combines exploratory insights with predictive modeling to understand pricing dynamics, simulate outcomes across various price ranges, and ultimately recommend the most profitable pricing strategy.

**Project Objectives**

* Analyze the relationship between price and sales quantity
* Compare pricing trends across our store and competitors
* Develop a predictive model to estimate expected revenue
* Simulate potential outcomes across different price points
* Recommend an actionable and profitable price strategy

**Key Takeaways**

1. **Understanding Pricing Patterns**
   Our store’s price distribution showed wider variability, while the competitor maintained more consistent pricing, particularly in the KSh 140–160 range hinting at a more deliberate pricing strategy on their part.

2. **Sales Behavior at Different Prices**
   Scatter plots revealed irregular sales trends in our store, whereas the competitor’s pricing was closely associated with higher and more stable revenue, suggesting better price anchoring.

3. **Building the Predictive Model**
   A Random Forest Regression model was trained to predict total sales revenue using price data. It achieved an R² of 0.84 and a low mean squared error of 548.26, confirming the model’s reliability in forecasting revenue.

4. **Optimizing Price through Simulation**
   We tested price points from KSh 130 to 190 and used the model to predict the corresponding sales amount. The simulation pointed to **KSh 168** as the optimal price, forecasting a potential revenue of **KSh 71,181.60**.

5. **Benchmarking Against Competitors**
   A final comparison was conducted across our current average price, the competitor’s price, and the optimized price. Results confirmed that adopting the KSh 168 pricing could yield higher revenue while still remaining competitive.

