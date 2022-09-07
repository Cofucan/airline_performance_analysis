# Airline On-Time Performance Analysis

### by Uche Ofia

## Dataset

The dataset used in this exploration is a large dataset from [Bureau of Transportation Statistics](https://www.transtats.bts.gov/Fields.asp?gnoyr_VQ=FGJ) and [Harvard](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7) which records consists of flight arrival and departure details for all commercial flights within the USA, from October 1987 to April 2008. This is a large dataset: there are nearly 120 million records in total, and takes up 1.6 gigabytes of space compressed and 12 gigabytes when uncompressed. The data comes originally from RITA where it is described in detail.

For this exploration, I mostly focused on the peroid of 2000 to 2008. Some of the data/variables include arrival delay (min), departure delay (min), day of flight, month of flight, flight carrier, airport, distance and many other variables.

## Summary of Findings

During my exploration of the dataset, I analyzed the 4 factors in the dataset that contribute to flight cancellations and saw that consistently across the years, the most contributing factor is carrier delays. I also tried to analyze the number of flights that were delayed and those that were diverted, as well as those that were delayed and saw that there is a rapid increase in the number of cancelled flights across the years.

I explored the relationship between cancelled flights and the airline companies and I saw that based on the total number of cancelled flights per year, there are a few companies that always come out on top. Though this might indicate a poor service by the company, it might also be that that company is a very big flight carrier and so they have a much larger network of flights which makes all their numbers go up.

## Key Insights for Presentation

In the presentation, I try to show insigts from my exploration of cancelled flights including the most contributing factors to flights being cancelled. I also present findings on airline carriers (compnaies) and to show which carriers have a higher number of cancelled or diverted flights.

Some interesting discoveries I made include the fact that there was a very large number of flights that were not delayed but instead left earlier than scheduled. Even if this were to happen, I wouldn't expect it to be more than a couple of minutes since anyone that is boarding a flight is expected to be at the airport a few minutes before departure time. But I found that there are flights that departed as early as 2 hours and some even up to 5 hours before scheduled.

## **Project Files**

1. [Part I Exploration](Part_I_exploration.html)
2. [Part II Slide Deck](Part_II_slide_deck.html)