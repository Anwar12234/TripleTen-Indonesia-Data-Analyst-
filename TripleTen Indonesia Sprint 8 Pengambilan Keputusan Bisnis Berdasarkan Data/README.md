# A/B Testing Online Shop

## Table of Contents

- [Introduction](#introduction)
- [Preprocessing Data](#preprocessing-data)
- [Prioritizing Hypotheses](#prioritizing-hypotheses)
- [Analyzing A/B Testing](#analyzing-ab-testing)
- [Conclusion](#conclusion)

## Introduction

In this project, we aim to optimize the revenue of our online shop through careful data analysis. By formulating strategic hypotheses and conducting A/B testing, we intend to identify the most effective changes that can be made to our online shop to maximize revenue.

## Preprocessing Data

In this section, we load and preprocess the necessary datasets:

- Importing required libraries
- Loading the hypothesis dataset and examining its information
- Loading the orders dataset, handling missing values, and eliminating duplicate visitors
- Loading the visitors dataset, handling missing values, and converting date columns to datetime format

## Prioritizing Hypotheses

In this section, we prioritize hypotheses using ICE and RICE frameworks:

- Using the ICE framework to prioritize hypotheses based on Impact, Confidence, and Effort
- Using the RICE framework to prioritize hypotheses based on Reach, Impact, Confidence, and Effort

## Analyzing A/B Testing

This section focuses on analyzing A/B testing results:

- Visualizing cumulative revenue for both groups
- Plotting average order size for both groups
- Visualizing the relative difference in cumulative average order sizes
- Analyzing daily conversion rates for both groups
- Creating scatterplots to explore orders per user and order revenues
- Performing statistical significance tests for conversion rates and average order sizes

## Conclusion

Based on the analysis, we draw the following conclusions:

- There is no statistically significant difference in conversion rates between Group A and Group B, both with raw and filtered data.
- There is no statistically significant difference in average order sizes between Group A and Group B, both with raw and filtered data.
- Conversion rates show a consistent pattern, but no significant improvements are observed.
- Average order sizes exhibit some variation, with Group B showing higher values in certain periods.

Considering the results, we recommend that the A/B testing be stopped as there is no clear indication of significant improvements in conversion rates or average order sizes.

For a detailed step-by-step explanation and code implementation, please refer to the Jupyter Notebook in this repository.
