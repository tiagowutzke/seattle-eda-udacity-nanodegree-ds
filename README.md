# Seattle EDA

This repository contains an Exploratory Data Analysis (_aka_EDA) for the project 1 of Udacity Data Science Nanodegree.

The EDA consists in drawing some business question, then analyze data in order to answer these questions and drawing conclusions about them.

## Libraries used

The starter kit to work with data and dataset in python
- pandas
- numpy

Data visualization
- seaborn
- matplotlib

## Business question

1 - Are there any seasonality regarding to the booking prices?

2 - A good response rate from hosts leads to their place have a higher booking frequency?

3 - Do the positive reviews leads to higher prices and booking frequency?

## Conclusions

- There are three periods in the year which we can see a higher volume of booking than the rest of the year:
    - In early 2016: vacation period
    - Early April: Spring season motivates people to visit Seattle
    - Early July: 4th July holiday
- We are unable to draw any conclusions regarding price seasonality and price correlations since there are no variability in the price throughout the year
- Theere's no correlation in occupancy percentage and response rate. Neither between occupancy percentage and review score. The unique evidence is the superhosts have higher score ratings and response rates than the standard host. However that's likely an obvius conclusion - these probabily are requirements to a host reach a superhost level.

