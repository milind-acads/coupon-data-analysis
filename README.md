# coupon-data-analysis
Data Analysis to identify if people driving by a town would accept a coupon from local restaurants or cafes

# Customer Coupon Acceptance Prediction

## Project Overview

This project analyzes a dataset from the UCI Machine Learning repository which was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc. This can be used to understand the factors influencing customer acceptance of driving coupons. The dataset contains information about user age, user income group, passenger information, and coupon details. The goal is to identify patterns to idetify customers who will accept certain types of coupons.

## Dataset

The dataset is collected through a survey on Amazon Mechanical Turk. It includes the following features:

**Dataset Information:**
- Driver Info (Gender, Age, Marital Status, Education, Occupation, Annual Income)
- Number of Children travelling
- Frequency of visits to bars, coffee houses, restaurants, and takeaway places
- Driving Destination
- Location of User, Coupon, and Destination
- Weather
- Temperature
- Time
- Passenger

**Coupon Information:**
- Type of Coupon (Restaurant, Coffee House, Bar, etc.)
- Expiration Time
- Business Type (Restaraunt, Bar, Coffee Shop)

## Analysis

The Notebook performs the following analysis:

1. **Exploratory Data Analysis:** Find out for missing or problematic data and perform cleaning techniques (e.g., dropping irrelevant columns, replacing missing values).
2. **Visualization:** Uses bar plots and histograms to visualize the distribution of coupon types and temperature.
3. **Bar Coupon Analysis:** Investigate on bar coupons and explores acceptance rates based on factors like frequency of bar visits, age, and passenger type using pandas library and visualization tools.
4. **Independent Investigation:** Performs similar analysis as above (bar coupons) in the food coupns area (dine-in and carry away).

## Findings

The analysis reveals coupon acceptance rates with multiple factors such as frequency of visits to businesses (example bars), age, passenger type etc. In the current form, notebook focuses on bars and food coupons but same approach can be used for others like coffee shops.

## Usage

To run this notebook, you will need:

1. Install Jupyter Notebook on workstation or access Google Colab.
2. Clone this repository.
3. Open the Notebook and execute the cells. Here is the link of this notebook: https://github.com/milind-acads/coupon-data-analysis/blob/main/prompt.ipynb

