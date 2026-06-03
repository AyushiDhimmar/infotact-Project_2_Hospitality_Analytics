# Hospitality Booking Analytics Dashboard

## Project Overview

This project analyzes hotel booking behavior, customer segments, cancellation patterns, and revenue-related metrics using SQL and Power BI. The goal is to identify booking trends and uncover the key factors contributing to reservation cancellations.

## Business Problem

Hotel cancellations directly impact occupancy planning and revenue forecasting. Understanding cancellation drivers can help hotels reduce revenue loss and improve booking strategies.

## Dataset Information

- Source: Hotel Booking Demand Dataset
- Records: ~119,000 hotel bookings
- Hotel Types: City Hotel and Resort Hotel
- Features: Booking dates, lead time, customer type, market segment, deposit type, ADR, cancellations, and more.

## Data Cleaning

- Removed duplicates and inconsistencies.
- Standardized categorical values.
- Handled missing values.
- Created cleaned analytical dataset.

## Exploratory Data Analysis

- Analyzed booking distribution by month.
- Examined hotel type performance.
- Evaluated customer segment behavior.
- Investigated cancellation patterns.

## Feature Engineering

- Created booking season categories.
- Generated lead time categories.
- Built dashboard-ready analytical dataset.

## Predictive Modeling

Several machine learning models were trained to predict booking cancellations.

Models evaluated:

- Logistic Regression
- Random Forest Classifier

Model performance was assessed using:

- Accuracy Score
- Classification Report
- Confusion Matrix

The modeling phase helped identify patterns associated with reservation cancellations and supported the dashboard insights.

## Dashboard Development

### Page 1: Hospitality Booking Analytics Dashboard

- KPI Cards
- Monthly Booking Trend
- Hotel Type Distribution
- Cancellation Analysis
- ADR Analysis
- Customer Type Analysis

### Page 2: Cancellation Root Cause Analysis

- Highest Cancellation Segment
- Highest Cancellation Deposit Type
- Highest Cancellation Customer Type
- Cancellation breakdowns by segment, deposit type, lead time, hotel, and customer type.

## Key Insights

(Reference insights.md)

## Recommendations

- Review policies associated with high-risk segments.
- Reassess Non-Refund booking strategy.
- Monitor long lead-time reservations.
- Develop retention strategies for high-risk customer groups.

## Conclusion

The dashboard provides an interactive view of booking performance and cancellation behavior, enabling data-driven decision-making for hotel operations and revenue management.
