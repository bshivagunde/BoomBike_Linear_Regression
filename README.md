# BoomBike Assignment

A US bike-sharing provider, BoomBikes, has been facing challenges in revenue due to the ongoing COVID-19 pandemic. This README provides an overview of the project and its findings.

## Table of Contents
- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)

## General Information

### Problem Statement
BoomBikes aims to increase its post-pandemic revenue and understand the factors affecting bike demand. Key questions include:
- Which factors predict bike usage?
- How accurately can these factors predict demand?

### Business Goal
Our goal is to create a predictive model for bike demand based on various factors. This model will aid in adapting business strategies to meet customer expectations and demand levels.

### Data Used
- **Data File:** [day.csv](link-to-data.csv)
- **Data Description:** 730 Rows, 16 Columns
- **Years Covered:** 2018 and 2019

## Conclusions

- Seasonal demand trends: Summer and fall have higher demand.
- Weather impact: Clear weather correlates with increased demand.
- Peak demand months: June, July, August, and September.
- Top 3 predictive features:
  1. `yr`: Coefficient => 0.2368, P-value => 0.000, VIF => 2.03
  2. `holiday`: Coefficient => -0.0913, P-value => 0.001, VIF => 1.04
  3. `temp`: Coefficient => 0.3551, P-value => 0.000, VIF => 4.30

## Technologies Used
- numpy - version 1.23.5
- pandas - version 1.5.3
- matplotlib - version 3.7.1
- seaborn - version 0.12.2

## Acknowledgements
This project was conducted by Mr. B. M. Shivagunde.

## Contact
Created by [@bshivagunde](https://github.com/bshivagunde) - Feel free to contact me!
