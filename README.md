# Housing Price Prediction

## Introduction
This repository focuses on predicting housing prices using historical data and recommending the most suitable locations for investment based on user preferences. By analyzing past housing price fluctuations, the system aims to forecast future trends and assist users in making informed investment decisions.

## Details
* Programming Language: Python
* Topic: Housing Price Prediction

## Summary
The project collects historical housing price data and leverages it to recommend the most promising investment locations tailored to the user's needs. Users input their preferred area, budget, and risk tolerance, and the system outputs recommendations on which areas to invest in, assists in calculating risks and returns, and identifies regions where housing prices align with the investor's criteria.

## Design Principles
The system operates based on the following principles:
1. **Prediction using Historical Data**: Utilizing past housing price fluctuations to predict future trends.
2. **User Inputs**: Users can input their preferred area, budget, and risk tolerance.
3. **Output**: Recommendations on which areas to buy properties, assistance in risk and return calculations, and identification of regions where housing prices match the investor's criteria.

## Logical Workflow
The backend logic follows these steps:
1. Web Scraping: Collecting housing price data.
2. Data Processing: Organizing the collected data.
3. Classification by Year: Grouping data by year.
4. Statistical Analysis: Calculating the standard deviation and average growth rate per square meter.
5. Segmentation: Segregating data by district or street.
