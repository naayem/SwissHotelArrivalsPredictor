# Predicting Hotel Arrivals in Switzerland with Google Trends

## Abstract

This project aims to demonstrate how Google Trends data can enhance predictions made by a model initially based solely on monthly released features. The motivation behind this project is to showcase how more recent temporal datasets can improve the prediction of near-future events, particularly unusual events like crises. In this case, the focus will be on the tourism industry in Switzerland, specifically predicting hotel arrivals. We intend to illustrate how Google Trends data can refine predictions, particularly during the COVID-19 crisis.

## Research Questions

This project seeks to answer the following questions:
1. Which Google Trends queries are valuable in predicting hotel arrivals in Switzerland?
2. Can Google Trends data provide more accurate predictions during the COVID-19 crisis compared to the monthly statistics from the Switzerland Federal Office of Statistics?

## Proposed Dataset

We have selected a dataset provided by the Swiss Federal Statistical Office, titled "Hotel Accommodation: Arrivals and Overnight Stays of Open Establishments by Year, Month, Canton, and Visitors' Country of Residence." The dataset is accessible [here](link-to-dataset). It covers hotel arrivals data from 2010 onwards with a monthly frequency.

## Methods

Our approach is inspired by the paper "Predicting the Present with Google Trends." Although the paper does not provide explicit techniques, we will follow these steps:
1. Data extraction and preprocessing.
2. Estimation of correlations in previous months to determine the best parameters for our auto-regressive model (e.g., order, seasonality).
3. Application of a rolling window on our auto-regression model, training on previous months to predict one month ahead.
4. Testing the correlation with different Google Trends keywords (e.g., 'Hotel,' 'Hotel Booking,' 'Swiss Lockdown') to select the most relevant additional features.
5. Comparison of model performance with and without Google Trends features.
6. Drawing conclusions.

## Proposed Timeline

- First Week: Individual tasks
- Second Week: Model implementation
- Third Week: Writing the data story, including website creation and video production

## Team Organization

- Second Week:
  - Vincent: Data cleaning
  - Clément & Antoine: Model development and result visualization
  - Xavier: Feature selection from Google Trends

- Third Week:
  - Antoine: Writing, video shooting, and video editing
  - Clément: Setting up the project website
  - Vincent & Xavier: Storywriting

## Questions for TAs (Optional)

If you have any questions related to the proposed project, please feel free to ask.


