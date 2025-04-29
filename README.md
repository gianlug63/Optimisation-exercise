# Revenue Optimization through Sales Modelling

This repository contains a Jupyter Notebook that explores how sales are affected by pricing, product offering, and promotions using the provided datasets. The goal is to develop a data-science-driven approach to optimize revenue.

## Project Description

This project analyzes two key datasets provided by the client:

-   **Product Data:** Contains information about the products, including their characteristics.
-   **Sales Data:** Contains historical sales data for the products, including prices and units sold.

The Jupyter Notebook walks through the following steps:

1.  **Data Familiarization:** Loading and exploring the datasets to understand their structure and content. This includes:
    -   Displaying the first few rows of each DataFrame.
    -   Checking data types and handling missing values.
    -   Calculating descriptive statistics (e.g., mean, median, standard deviation).
2.  **Exploratory Data Analysis (EDA):** Creating relevant visualizations to understand the relationship between price, product characteristics, and sales. Examples might include:
    -   Scatter plots of price vs. units sold for different products.
    -   Distributions of sales for various product categories.
    -   Box plots comparing prices across different product attributes.
3.  **Simple Sales Model Development:** Building a basic model to predict units sold based on price (potentially using price elasticities). This model aims to describe the distribution or provide a point estimate of units given price and product attributes.
4.  **Model Fitting:** Training the developed model using the historical sales data.
5.  **Model Evaluation:** Assessing the performance of the model by comparing it against a simple baseline. This could involve calculating metrics like Mean Squared Error (MSE) or Root Mean Squared Error (RMSE).
6.  **Revenue Optimization Demonstration:** Illustrating how the developed model can be used to support revenue optimization. 

## Files in this Repository

-   `product_data.csv`: Contains the product-related information.
-   `sales_data.csv`: Contains the historical sales data.
-   `README.md`: This file, providing an overview of the project.


## Key Learnings

This project demonstrates the ability to:

-   Perform exploratory data analysis to understand the drivers of sales.
-   Develop a basic predictive model for sales based on price and product attributes.
-   Evaluate the performance of a data-driven model.
-   Utilize simulations to explore different business strategies for revenue optimization.
-   Interpret data science results in a practical business context.
