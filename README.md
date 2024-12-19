# Homesite Quote Conversion Prediction

## Description

Decision-making often requires understanding the likelihood of success. This principle applies to quoting home insurance prices as well. Homesite, a prominent provider of homeowners insurance, currently lacks a dynamic conversion rate model to predict whether a quoted price will result in a purchase. 

Using an anonymized dataset of customer and sales activity, including property and coverage information, Homesite presents the challenge of predicting which customers will accept a given quote. By accurately forecasting these conversion rates, Homesite aims to evaluate the impact of pricing changes, optimize customer segmentation strategies, and maintain a balanced portfolio of customer segments.

This project leverages machine learning to develop a robust predictive model that provides actionable insights for Homesite’s business operations.

---

## Objective

The primary objective is to predict the **QuoteConversion_Flag**, a binary indicator of whether a customer purchased a quoted policy, using the anonymized dataset provided by Homesite.

---

## Evaluation Metric

Submissions are evaluated using the **Area Under the Receiver Operating Characteristic Curve (AUC-ROC)**. This metric assesses the model's ability to distinguish between customers likely to convert and those who are not, offering a comprehensive measure of performance.

---

## Dataset Description

The dataset comprises anonymized features reflecting various aspects of customer and policy data, categorized as follows:
- **Coverage Information**: Policy coverage details.
- **Sales Information**: Data regarding the quoting and sales process.
- **Personal Information**: Anonymized customer attributes.
- **Property Information**: Details of the insured property.
- **Geographic Information**: Location-specific attributes.

### Provided Files:
1. **`train.csv`**: The training dataset, including the target variable (`QuoteConversion_Flag`).
2. **`test.csv`**: The test dataset without the target variable, used for predictions.
3. **`sample_submission.csv`**: A template submission file in the required format.

---

## Project Workflow

1. **Exploratory Data Analysis (EDA)**: Comprehensive analysis to uncover patterns, trends, and data anomalies.
2. **Data Preprocessing**: Cleaning and preparing the data by addressing missing values, encoding categorical features, and normalizing variables.
3. **Feature Engineering**: Creation of derived features to enhance the model’s predictive performance.
4. **Model Development**: Training and fine-tuning machine learning algorithms (e.g., Logistic Regression, Random Forest, Gradient Boosting).
5. **Evaluation**: Measuring performance using AUC-ROC and iteratively improving the model.
6. **Deployment**: Developing a robust, scalable solution for predicting customer conversions.

---

## Key Highlights in Report

The accompanying Excel report provides:
- Detailed exploratory data analysis, highlighting trends and insights.
- Feature importance analysis and correlation findings.
- Performance metrics across different models.
- Recommendations for future enhancements and potential business applications.

---

## Kaggle Competition

This project is part of the Kaggle competition **[Homesite Quote Conversion](https://www.kaggle.com/c/homesite-quote-conversion/overview)**. The competition provides a platform for experimenting with predictive modeling and contributing to Homesite’s business challenge.



## Video Report Explanation

https://asu.zoom.us/rec/share/3gMaNR0gmFd4eA-3hs0wclIqONjLS61ZQYFLu3RGD9G4QYl3d2cj7HyTe9Sc5b1n.PfjK9-EPCbJwBXnt?startTime=1731884300000

Passcode: !w@3AgW3
