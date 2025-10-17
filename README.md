# What factors influence the price of a vehicle?

**Assignment notebook:** https://github.com/vincentwenger/vehicle_price_factors/blob/main/prompt_II.ipynb

## What is the problem?
This project aims to understand what factors of the vehicle will drive the price of the vehicle. The goal is to understand what factors make a car more or less expensive.

## What is the data?
This data is a dataset from Kaggle. The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure the speed of processing.

## What are the findings?

The findings are that :
- <ins>For bar coupons:</ins>
  - The more frequent the drivers go to a bar each month, the more likely they are to accept the coupons
  - Drivers with a lower income and who go often to cheap restaurants are less likely to accept the coupons
- <ins>For Carry out & Take away coupons:</ins>
  - Drivers who are more likely to accept the coupons are male drivers, who are 50 years old or more, who go home or to no urgent place, don't travel with kid(s), around 2PM or 6PM, when it doesn't rain.
  - Drivers with lower level of education, with lower income, with a job in construction, building maintenance or healthcare practitioners are more likely to accept the coupon
  - Drivers who don't go more than 8 times a month to Bars or Coffeehouses or who never buy takeaway food or never go to cheap restaurants are more likely to accept the coupons
  - Coupons are better accepted when it has more time before it expires
- <ins>For Coffee House coupons:</ins>
  - Drivers who are more likely to accept the coupons are drivers, who are below 21 years old, who go to no urgent place, travel with friend(s) or partner, around 10AM, when it doesn't snow and the temperature is hot.
  - Drivers with lower level of education, with lower income, with a job in building maintenance or healthcare practitioners are more likely to accept the coupon
  - Drivers who don't go more than 8 times a month to Bars, go at least 3 times a month to Coffee Houses, or order at least once a month Take away food, or go at least once a month to cheap or expensive restaurants are more likely to accept the coupons
  - Coupons are better accepted when it has more time before it expires
- <ins>For Cheap restaurant coupons:</ins>
  - Drivers who are more likely to accept the coupons are drivers, who are less than 50 years old, who go to no urgent place, travel with friend(s) or partner, around 2PM or 6PM, when it is sunny and the temperature is not too cold.
  - Drivers who don't go more than 8 times a month to Bars or Coffee Houses, or never order takeaway food, or go at least 4 times a month to cheap restaurants or at least once a month to expensive restaurants are more likely to accept the coupons
  - Drivers are more likely to accept the coupon when the geographical distance doesn't exceed 25 minutes drive
  - Coupons are better accepted when it has more time before it expires
- <ins>For Expensive restaurant coupons:</ins>
  - Drivers who are more likely to accept the coupons are drivers, who are less than 50 years old, who go to no urgent place, travel with partner, around 10AM or 6PM, when weather is sunny and the temperature is not too cold.
  - Single or unmarried partners drivers with lower level of education, or with higher income, or with a job in Production occupations are more likely to accept the coupon
  - Drivers who go more than 8 times a month to Bars or cheap restaurants or expensive restaurants or who order more than 8 times a month Take away food are more likely to accept the coupons
  - Coupons are better accepted when it has more time before it expires

## What do I recommend?

- In general, it is better to create coupons which have more time before they expire
- Distribute bar coupons only to people who go to bars often
- Distribute Carry out & Take away coupons :
  - in places where people are older, with no kids around
  - when it doesn't rain
  - near places with construction zones or hospitals, or near residential neighborhoods where people with lower income live
- Distribute Coffee House coupons:
  - in places with young people who are less than 21
  - near residential neighborhoods where people with lower income live
  - when it doesn't snow and the temperature is hot.
- Distribute Cheap restaurant coupons:
  - when weather is sunny and the temperature is not too cold
  - to people who go to restaurants often and never order take away food
  - to restaurants which are not located too far from the drivers
- Distribute Expensive restaurant coupons:
  - when weather is sunny and the temperature is not too cold
  - to single or unmarried drivers with higher income
  - who people who already go often to bars and restaurants
