# coupon-data-analysis
Data Analysis to identify if folks driving by a town would accept a coupon from local restaurants or cafes

# Customer Coupon Acceptance Prediction

## Project Overview

This project analyzes a dataset from the UCI Machine Learning repository to understand the factors influencing customer acceptance of driving coupons. The dataset contains information about user demographics, driving context, and coupon details. The goal is to identify patterns and characteristics that differentiate customers who accept coupons from those who don't.

## Dataset

The dataset is collected through a survey on Amazon Mechanical Turk. It includes the following features:

**User Attributes:**
- Gender
- Age
- Marital Status
- Number of Children
- Education
- Occupation
- Annual Income
- Frequency of visits to bars, coffee houses, restaurants, and takeaway places

**Contextual Attributes:**
- Driving Destination
- Location of User, Coupon, and Destination
- Weather
- Temperature
- Time
- Passenger

**Coupon Attributes:**
- Type of Coupon (Restaurant, Coffee House, Bar, etc.)
- Expiration Time

## Analysis

The Jupyter Notebook performs the following analysis:

1. **Data Exploration and Cleaning:** Investigates the dataset for missing or problematic data and applies appropriate cleaning techniques (e.g., dropping irrelevant columns, replacing missing values).
2. **Overall Coupon Acceptance:** Calculates the proportion of total observations that chose to accept the coupon.
3. **Visualization:** Uses bar plots and histograms to visualize the distribution of coupon types and temperature.
4. **Bar Coupon Analysis:** Focuses specifically on bar coupons and explores acceptance rates based on factors like frequency of bar visits, age, and passenger type.
5. **Independent Investigation:** Encourages further exploration of other coupon groups to determine the characteristics of passengers who accept those coupons.

## Findings

The analysis reveals potential correlations between coupon acceptance and factors such as frequency of visits to relevant establishments, age, passenger type, and potentially occupation and marital status. The notebook provides detailed insights into the acceptance rates for different customer segments and offers hypotheses about driver behavior.

## Usage

To run this notebook, you will need:

- Python 3
- Jupyter Notebook
- Pandas
- Seaborn
- Matplotlib

1. Clone this repository.
2. Install the necessary libraries.
3. Open the Jupyter Notebook and execute the cells.

