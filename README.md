Data Analytics: Customer Segmentation and Store Trial Evaluation

This repository contains the solutions for two tasks provided by the client for a category review and store trial evaluation. The goal is to derive actionable insights on customer purchasing behavior and evaluate store trial performance. The analysis is done using R (with Python considered as an additional tool). The solutions include data cleaning, feature engineering, customer segmentation, and performance evaluation.

Tasks Overview

Task 1: Customer Segmentation and Purchasing Behavior

In this task, we aim to understand customer purchasing behavior, particularly focusing on chip purchases. We perform the following:
	•	High-Level Data Checks: This includes summarizing data, finding outliers, and correcting data formats.
	•	Feature Engineering: We create new features like pack size and brand name from the data.
	•	Metric Definition: We define key metrics to evaluate customer purchasing behaviors and understand the drivers of chip spending for different customer segments.
	•	Strategic Recommendation: Based on the analysis, we derive insights and provide strategic recommendations for the Category Manager to apply commercially.

Task 2: Store Trial Performance Evaluation

This task focuses on evaluating the performance of store trials performed in stores 77, 86, and 88, compared with control stores. The analysis includes:
	•	Metrics: Analysis of total sales revenue, number of customers, and average number of transactions per customer for each store.
	•	Control Store Selection: A method to compare trial stores against control stores is developed using Pearson correlations or a magnitude distance metric.
	•	Comparison: We compare the performance of trial stores with control stores to determine if there is a significant difference in sales during the trial period. We analyze if the change is driven by more purchasing customers or increased purchases per customer.
