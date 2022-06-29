# Seattle EDA

This repository contains an Exploratory Data Analysis (_aka_EDA) for the project 1 of Udacity Data Science Nanodegree.

The EDA consists in choose a dataset. Check data inside it and drawing some business question. Then analyze data in order to answer these questions and drawing conclusions about them.

The dataset which was chosen is [Seattle Airbnb Open Data](https://www.kaggle.com/datasets/airbnb/seattle). There are three dataframes available and their description are*:
- Listings, including full descriptions and average review score
- Reviews, including unique id for each reviewer and detailed comments
- Calendar, including listing id and the price and availability for that day

*_descriptions provided by Airbnb in Kaggle dataset page_

## Stakeholders article

An article about the insights provided by the analysis is available at this [site](https://sites.google.com/view/seattleeda-udacitydsnanodegree/in%C3%ADcio)

## Libraries used

The starter kit to work with data and dataset in python 
- pandas
- numpy

Data visualization
- seaborn
- matplotlib

## Files
`Seattle EDA.ipynb`: Jupyter notebook containing the analysis

## Datasets


## Business question

1 - Is there any seasonality regarding the booking prices?

2 - A good response rate from hosts leads to their place having a higher booking frequency?

3 - Do the positive reviews lead to higher prices and booking frequency?

## Conclusions

- There are three periods in the year which we can see a higher volume of booking than the rest of the year:
    - In early 2016: vacation period
    - Early April: Spring season motivates people to visit Seattle
    - Early July: 4th July holiday
- We are unable to draw any conclusions regarding price seasonality and price correlations since there are no variability in the price throughout the year
- Theere's no correlation in occupancy percentage and response rate. Neither between occupancy percentage and review score. The unique evidence is the superhosts have higher score ratings and response rates than the standard host. However that's likely an obvius conclusion - these probabily are requirements to a host reach a superhost level.

