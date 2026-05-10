<img width="1400" height="738" alt="1_HiwX6vul8c4PBEueq3yBMw" src="https://github.com/user-attachments/assets/fbd2d2cf-f63c-43db-9475-21bca2d443e1" />

# Customer-Profitability-Analysis

RFM Analysis - Case Study - Book : Aslani A, Business Analytics with Management Science Models and Methods, Pearson Education, 2015. https://ptgmedia.pearsoncmg.com/images/9780133760354/samplepages/9780133760354.pdf

This project focuses on customer segmentation and campaign profitability analysis using the RFM (Recency, Frequency, Monetary) methodology. The analysis was performed in Python and visualized in Power BI in order to identify the most valuable customer segments for a future marketing campaign.

## Academic Context

This project was originally developed as part of an MSc assignment in Business Analytics and Data Science at the University of Macedonia.

The analysis was completed in Python instead of the originally proposed software environment, with permission from the course instructor, Mr. Georgiou. Permission was also granted to further expand and publicly share the project on GitHub for educational and portfolio purposes.

## Quiz


## Project Objectives

Perform customer segmentation using RFM analysis

Evaluate customer profitability through Expected Profit calculations

Identify the most valuable customer groups for campaign targeting

Visualize customer behavior and campaign profitability using Power BI

Python

pandas

numpy

Power BI

Jupyter Notebook


## The dataset contains customer transaction information, including:

Passport Number (Customer ID)

Date of Visit

Sales Amount

Transaction Number

## The original dataset was aggregated at customer level in order to calculate:

Recency

Frequency

Monetary value

Methodology



## 1. Data Preparation

Data import and inspection

Missing value checks

Datatype validation

## 2. RFM Analysis

Customers were segmented into score classes based on:

Recency score

Frequency score

Monetary score

The score thresholds were defined according to the assignment requirements.

## 3. Expected Profit Calculation

Expected profit was calculated using the following formula:

Expected_profit = (0.45 * Monetary) - 5.75

where:

0.45 represents the average expected campaign response probability
5.75 represents the average campaign incentive cost per customer


## 4. Profitability Evaluation

Customers were grouped by:

R_score

F_score

M_score

in order to evaluate:

Total expected profit

Customer distribution

Most profitable customer segments

Key Findings

Customers with high Monetary scores generate the majority of the expected profit.

Highly frequent customers contribute disproportionately more value despite being fewer in number.

Recently active customers appear to be the most promising targets for future marketing campaigns.

Low Monetary score customers generate minimal or even negative expected profitability.

Dashboard

## The project also includes a Power BI dashboard visualizing:

Expected Profit by Recency Score

Expected Profit by Frequency Score

Expected Profit by Monetary Score

Key business insights and campaign targeting conclusions

Reference

## PowerBI

<img width="1957" height="1098" alt="Dashboards" src="https://github.com/user-attachments/assets/90256bdf-6713-450c-a18e-d4bdf7cbb741" />


## The original dataset and case study are based on:

Aslani A, Business Analytics with Management Science Models and Methods, Pearson Education, 2015.

https://ptgmedia.pearsoncmg.com/images/9780133760354/samplepages/9780133760354.pdf
