# Fitness Gym Customer Churn Analysis

This project focuses on analyzing customer churn at a fitness gym. The primary objective is to identify patterns and insights that can help the gym improve customer retention and, ultimately, increase profitability.

## Table of Contents
- [Preprocessing](#preprocessing)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Prediction Models](#prediction-models)
- [User Clustering](#user-clustering)
- [General Conclusions](#general-conclusions)
- [Recommendations](#recommendations)

## Preprocessing
- The dataset contains 4000 entries, with each row representing a customer along with their characteristics.
- Common assumptions: 0 indicates "no," 1 indicates "yes," with gender being an exception (0 represents "female" and 1 represents "male").
- Data was transformed to lowercase for consistency.

## Exploratory Data Analysis (EDA)
- No missing values or duplicates were found in the dataset, indicating clean data.
- Mean values and standard deviations were analyzed for various features and visualized, revealing the dataset's diverse conditions.
- Churn analysis shows that many customers are loyal, with no churn.

## Prediction Models
- The dataset was divided into training and validation sets (80/20) using `train_test_split()`.
- Two initial models, logistic regression and random forest, were trained.
- Later, decision tree and gradient boosting models were trained, with balanced accuracy due to class imbalance.
- ROC_AUC was used to assess model strength, with Random Forest outperforming Logistic Regression.

## User Clustering
- The optimal number of clusters was determined to be 4.
- A K-means clustering model was trained with 4 clusters.
- Cluster labels were saved in the "cluster" column.
- Churn rates were calculated, and Cluster 4 was identified as the most loyal.

## General Conclusions
- The project successfully analyzed customer churn at the fitness gym.
- Data preprocessing ensured clean, consistent data.
- EDA revealed interesting insights, such as a diverse customer base and the need for churn reduction strategies.
- Prediction models, including logistic regression, random forest, decision tree, and gradient boosting, were developed and evaluated.
- User clustering identified the most loyal cluster (Cluster 4).

## Recommendations
- Develop targeted strategies for retaining older customers, such as introducing premium services.
- Focus on customer acquisition and retention for younger customers with short-term contracts.
- Encourage obtaining customer phone numbers to facilitate communication and retention efforts.
- Offer special services or promotions to customers living far from the gym.
- Encourage partner sign-ups and refer-a-friend programs to increase overall customer spending and retention.

For any questions or additional details, please contact the project contributors.
