# Market Research of Los Angeles Establishments

## Table of Contents
- [Introduction](#introduction)
- [Data Description](#data-description)
- [Data Analysis](#data-analysis)
    - [Investigation of Establishment Types](#investigation-of-establishment-types)
    - [Proportion of Chain and Non-Chain Establishments](#proportion-of-chain-and-non-chain-establishments)
    - [Proportion of Chain and Non-Chain Establishments by Type](#proportion-of-chain-and-non-chain-establishments-by-type)
    - [Features of Chain Establishments](#features-of-chain-establishments)
    - [Average Number of Seats for Each Restaurant Type](#average-number-of-seats-for-each-restaurant-type)
    - [Extracting Street Names](#extracting-street-names)
    - [Top Ten Streets for the Number of Establishments](#top-ten-streets-for-the-number-of-establishments)
    - [Streets with Only One Restaurant](#streets-with-only-one-restaurant)
    - [Distribution of Seats in Restaurants on Top Ten Streets](#distribution-of-seats-in-restaurants-on-top-ten-streets)

## Introduction
In this project, we conducted market research on establishments in Los Angeles to gather insights for opening a small cafe with robot servers. We analyzed a dataset of Los Angeles establishments to understand the current market conditions and trends.

## Data Description
The dataset (`rest_data_us.csv`) includes the following columns:
- `name`: Name of the establishment
- `chain`: Indicates if the establishment is part of a chain (TRUE/FALSE)
- `type`: Type of establishment (e.g., Cafe, Restaurant, Fast Food)
- `address`: Address of the establishment
- `number`: Number of seats in the establishment

## Data Analysis

### Investigation of Establishment Types
We began by analyzing the distribution of different establishment types in Los Angeles. The majority of establishments are restaurants, followed by fast food and cafes.

### Proportion of Chain and Non-Chain Establishments
We explored the proportion of chain and non-chain establishments. Approximately 62% of establishments are non-chain.

### Proportion of Chain and Non-Chain Establishments by Type
The proportion of chain establishments varies by establishment type. Fast food, cafes, and bakeries tend to be chains, while bars and restaurants are more likely to be non-chain.

### Features of Chain Establishments
We analyzed the features of chain establishments and found that many chain restaurants have fewer seats.

### Average Number of Seats for Each Restaurant Type
We calculated the average number of seats for each restaurant type. Restaurants and bars have the highest average number of seats, while cafes and bakeries have the lowest.

### Extracting Street Names
We extracted street names from the address column and created a new column with the extracted values.

### Top Ten Streets for the Number of Establishments
We identified the top ten streets with the highest number of establishments. Sunset is the most popular street.

### Streets with Only One Restaurant
We identified streets with only one restaurant. These streets likely host specialty or unique establishments.

### Distribution of Seats in Restaurants on Top Ten Streets
We analyzed the distribution of the number of seats in establishments on the top ten streets. Restaurants on popular streets tend to have fewer seats.

## Conclusion
Our market research provides valuable insights for opening a small cafe with robot servers in Los Angeles. The analysis of establishment types, chain proportions, street popularity, and seat distributions helps us understand the market landscape and make informed business decisions.
