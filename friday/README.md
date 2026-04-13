# Day 40 (Friday) -  ShopSense Analysis

## Description

This task applies the TF-IDF representation to a dataset of product reviews from ShopSense, a product review aggregation platform. The dataset contains reviews from various categories, including Electronics, Health & Beauty, Home & Kitchen, and more. The task evaluates two approaches against three hard engineering constraints: new product categories with no retraining, ~15% Hindi-English mixed language reviews, and inference latency under 20 ms per review.

## Key Learnings

- TF-IDF-based models are suitable for production systems with latency constraints.
- TF-IDF-based models are robust to new product categories with no retraining.
- TF-IDF-based models are robust to ~15% Hindi-English mixed language reviews.

### Steps to Run

1. Open a terminal and navigate to the directory containing this README file.
2. Run the command `jupyter notebook` to start the Jupyter notebook server.
3. Open a web browser and navigate to `http://localhost:8888` to access the Jupyter notebook interface.
4. Select the `shopsense_analysis.ipynb` notebook and click the "Run" button to execute the code in each cell in order.
5. Observe the output of each cell to verify that the code is working correctly.

## File:- 

### [`shopsense_analysis.ipynb`](./shopsense_analysis.ipynb)
