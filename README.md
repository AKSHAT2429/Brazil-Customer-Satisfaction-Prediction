```markdown
# Customer Satisfaction Enhancement in Brazilian E-Commerce

## Overview

In the rapidly evolving landscape of online shopping, understanding and improving customer satisfaction are paramount for long-term business growth. This project delves into the Brazilian E-Commerce Public Dataset from 2016 to 2018, employing advanced techniques and machine learning to extract insights that can positively impact customer experiences. The primary goal is to provide online businesses with practical information to enhance customer happiness.

## Table of Contents
1. [Introduction](#Introduction)
2. [Dataset Description and Preprocessing](#dataset-description-and-preprocessing)
3. [Data Visualization](#data-visualization)
4. [Structuring Data for Model Performance](#structuring-data-for-better-model-performance)
5. [Model Selection](#model-selection)
6. [Hyperparameter Tuning](#hyperparameter-tuning)
7. [Model Results](#model-results)
8. [Feature Importance](#feature-importance)
9. [Conclusion](#conclusion)

## Introduction
In the fast-paced world of online shopping, customer satisfaction is crucial for sustained business growth. This report explores the Brazilian E-Commerce Public Dataset, spanning 2016 to 2018, with a focus on using advanced techniques and machine learning to enhance customer happiness.

## Dataset Description and Preprocessing
- Merged 7 relevant datasets into one dataframe.
- Created additional columns for time durations and product volume.
- Calculated distances between sellers and customers using geopandas.
- Imputed missing values and dropped rows with critical missing information.
- Conducted one-hot encoding for 'order_status' and target encoding for 'product category name.'

## Data Visualization
Utilized visualizations at various stages to gain insights into algorithm behavior and performance. Feature importance graphs and convolutional neural networks' performance curves enhanced interpretability and decision-making.

## Structuring Data for Better Model Performance
Addressed label imbalance by transforming the problem into binary classification. Binarized labels based on a threshold, improving model performance and capturing the context of the data better.

## Model Selection
Implemented four models:
1. Logistic Regression
2. Random Forest
3. XGBoost
4. Neural Network

## Hyperparameter Tuning
Conducted hyperparameter tuning for all models using grid search cross-validation, improving model performance and preventing overfitting/underfitting.

## Model Results
Achieved significant improvements over the baseline model:
- Logistic Regression: 0.751 (Development), 0.748 (Test)
- Random Forest: 0.912 (Development), 0.884 (Test)
- XGBoost: 0.910 (Development), 0.884 (Test)
- Neural Network: 0.844 (Test)

## Feature Importance
Highlighted key features influencing customer satisfaction:
- 'Order_status,' 'delivery_delay,' and 'delivery_time' were crucial.
- 'Product_category_encoded' indicated varying satisfaction levels across product categories.

## Conclusion
In conclusion, this project provides practical insights for online businesses to improve customer satisfaction. By leveraging advanced techniques and machine learning, we navigate through data analysis, model selection, and feature importance analysis. The refined models offer significant improvements over the baseline, paving the way for a better understanding of customer satisfaction dynamics in the realm of Brazilian e-commerce.

### How to Use This Repository
1. Clone the repository: `git clone <repository_url>`
2. Navigate to the project directory: `cd Brazil-Customer-Satisfaction-Prediction`
3. Install dependencies: `pip install -r requirements.txt`
4. Explore the Jupyter Notebooks for data analysis and model implementation.
5. Refer to the project report for detailed insights and findings.

Feel free to reach out for any questions or collaborations. Happy coding! 🚀
```
