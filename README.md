# Project Name
> BoomBike Assignment
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
> ####Problem Statement:
BoomBikes wants to increase its revenue after the COVID-19 pandemic. The company want to figure out what factors affect the demand for shared bikes. 
They want to know:

- Which factors are important in predicting how many people will use their bikes? 
- How accurately can these factors predict bike demand? 
To do this, they've collected a lot of data on daily bike usage and factors like weather and people's behavior across the US market. 
The goal is to understand what makes people want to use their bikes and use this information to boost their business when the pandemic ends.

> ####Business Goal:
The business goal is to create a model that can predict how many people will use shared bikes based on different factors. This model will help the company's management understand how bike demand changes with various features like weather and customer behavior. By using this model, they can adjust their business strategy to meet customer expectations and demand levels. Additionally, it will be a valuable tool for understanding how bike demand works in a new market.

> ####Data Used:
- "day.csv" 
- The Data has 730 Rows and 16 Columns
- The Data is for year 2018 and 2019

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- There is high demand in summer and fall than that of spring and winter. Spring has lowest demand among all seasons
- The demand increases as weather gets clear
- Bike demand is more in Jun , Jul , Aug and Sep
- 'temp’ and ‘atemp’ has highest correlation with ‘cnt’ (target variable)
- Top 3 features are
	1. yr : Coefficient => 0.2368     P-value=> 0.000 VIF => 2.03
	2. holiday :  Coefficient => -0.0913     P-value=> 0.001 VIF => 1.04
	3. temp :   Coefficient =>  0.3551     P-value=> 0.000 VIF => 4.30


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.23.5
- pandas - version 1.5.3
- matplotlib - version 3.7.1
- seaborn - version 0.12.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
The Project work is performed by Mr. B. M. Shivagunde


## Contact
Created by [@bshivagunde] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->