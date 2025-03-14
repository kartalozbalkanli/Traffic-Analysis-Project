# Traffic Accidents & Tickets Analysis Project
Data Science Project for the Analysis of Traffic Accidents &amp; Tickets in Turkey

## Project Overview
* This project aims to analyze the relationship between the increase rate of traffic accidents and traffic tickets, and the increase rate of automobiles in Turkey over the past few years. The goal is to explore whether there has been a decrease in driver skill as the number of vehicles has increased. Using data visualisation tools, correlations and patterns between variables will be studied.

## Motivation
* Since traffic accidents are one of the primary reasons of death in Turkey, I was compelled to choose this subject to have a further understanding of the reasons of traffic related incidents. The results gathered might even give insights to predict future trends.

## Objectives
* To identify trends in traffic accidents and traffic tickets in relation to the increase in automobile numbers.
* To investigate if there is a correlation between the increase in automobiles and traffic-related incidents.
* To explore the potential decline in driver skill as indicated by the rate of accidents and tickets relative to the rise in vehicles.

## Datasets
The primary datasets used in this project will come from the following sources:

1. **TUIK (Turkish Statistical Institute):**<br/><br/> 
   Yearly datas on:
   * The amount of vehicles registered,
   * The amount of total accidents,
   * The injury amounts rates of accidents,
   * The death rates of accidents,
   * The age groups of these injury & death rates,
   * The faults causing these accidents will be analyzed and stuided.

   
2. **Gendarmerie General Command:**<br/><br/>
   Monthly and yearly datas on:
   * Spread of accident over different months,
   * Types of faults causing the accidents,
   * Number of traffic tickets given,
   * Reasons for the traffic tickets given,
   * Number of drivers licenses revoked,
   * Number of cars banned from traffic will be analyzed and studied.
   
## Sample Data

Below is an example of how the dataset might look after cleaning and merging data from TUIK and the Gendarmerie General Command:

| Year | Total Vehicles | Traffic Accidents | Injuries | Fatalities | Driver Error % | Other Faults % | Total Tickets | % Tickets to Drivers | % Tickets to Car Plates | Licenses Revoked | Cars Banned from Traffic |
|------|--------------|------------------|----------|------------|---------------|----------------|--------------|------------------|---------------------|-----------------|----------------------|
| 2020 | 23,500,000  | 405,000          | 275,000  | 5,800      | 88%           | 12%            | 12,500,000   | 60%              | 40%                 | 15,000          | 10,500               |
| 2021 | 24,200,000  | 420,000          | 285,000  | 5,950      | 87%           | 13%            | 13,200,000   | 58%              | 42%                 | 16,500          | 11,000               |
| 2022 | 25,100,000  | 435,000          | 295,000  | 6,100      | 85%           | 15%            | 14,000,000   | 57%              | 43%                 | 18,000          | 11,800               |

This table is a simplified example of what the structured dataset might contain. The actual dataset will be more detailed and include additional variables for deeper analysis.
