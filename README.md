# Customer Coupon Acceptance Rate Analysis

## Overview

This project is based on a survey on drivers who driving through town and a coupon is delivered to their cell phone for a nearby restaurant. 
The questions under analysis are:
* Would customer accept that coupon and take a short detour to the restaurant? 
* Would customer accept the coupon but use it on a subsequent trip? 
* Would customer ignore the coupon entirely? 
* What if the coupon was for a bar instead of a restaurant? 
* What about a coffee house?
* Would customer accept a bar coupon with a minor passenger in the car?
* Would customer's age play any role on acceptance?
* Would weather impact the rate of acceptance? What about the time of day?

The goal of this project is to use visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those who did not.

## Dataset

This data comes from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk.
The attributes of this data set include:
1. User attributes
    -  Gender: male, female
    -  Age: below 21, 21 to 25, 26 to 30, 50+ etc
    -  Marital Status: single, married partner, unmarried partner, Divorced, or widowed
    -  Number of children: 0, 1, or more than 1
    -  Education: high school, bachelors degree, associates degree, or graduate degree etc
    -  Occupation
    -  Annual income
    -  Number of times that he/she goes to a bar
    -  Number of times that he/she buys takeaway food
    -  Number of times that he/she goes to a coffee house
    -  Number of times that he/she eats at a restaurant with average expense less than \\$20 per person
    -  Number of times that he/she goes to a bar
    
2. Contextual attributes
    - Driving destination: home, work, or no urgent destination
    - Direction same/opp - The user can see whether the venue is in the same/opp direction as the destination.
    - Weather: sunny, rainy, or snowy
    - Temperature: 30F, 55F, or 80F
    - Time of the day: 7AM, 10AM, 2PM, 6PM or 10PM
    - Passenger: alone, partner, kid(s), or friend(s)

3. Coupon attributes
    - time before it expires: 2 hours or one day
    - Y: Coupon Acceptance (1 - Yes, 0 - No)

## Approach

1. Analyze the data while viewing, describing, taking the stats
2. Investigate the dataset for missing or problematic data.
3. Look for any outliers.
4. Decide what to do about the missing data e.g drop, replace etc
5. Analyze the acceptance of coupon for different category
6. Create different visualizations for these categories
7. Draw conclusion based on observations

## Visualizations

1. [Missing Values Visualization](https://github.com/CoderNBR/Practical-Application-Mod-5/blob/main/images/MissingValuesBarPlot.png)
2. [Counts By Coupon Type](https://github.com/CoderNBR/Practical-Application-Mod-5/blob/main/images/CouponCountByType.png)
3. [Distrubution of Temperature](https://github.com/CoderNBR/Practical-Application-Mod-5/blob/main/images/TemperatureDistribution.png)
4. [Coupon Acceptance Rate by Bar Visits](https://github.com/CoderNBR/Practical-Application-Mod-5/blob/main/images/CouponAccpRateByBarVisits.png)
5. [Coupon Acceptance Rate by Driver Group I Vs Others](https://github.com/CoderNBR/Practical-Application-Mod-5/blob/main/images/CouponAccpRateDGVsOthers.png)
6. [Coupon Acceptance Rate by Driver Group II Vs Others](https://github.com/CoderNBR/Practical-Application-Mod-5/blob/main/images/CouponAccpRateDG2VsOthers.png)
7. [Coupon Acceptance Rate by Driver Groups Vs Others](https://github.com/CoderNBR/Practical-Application-Mod-5/blob/main/images/CouponAccpRateDGroupsVsOthers.png)
   


## Observations

* Drivers who visit Bar more than 3 times have more acceptance rate than who visits less than 3 times
* Younger drivers under the age of 25/30 has good acceptance to the bar coupons.
* Again, if there are no kids passengers and occupations other than farming, fishing, or forestry also have better acceptance rate
* It is also observed that drivers with  with lower income who goes to cheap restaurant more often also have comparable accetance rate

## Conclusion & Recommendation

We can infer that user attributes such as Age, Marital Status, Income etc significantly influence coupon acceptance rates. Again, social habits, particularly the frequency of bar visits, also play an important role. Hence, marketting should focus on their stragegies on customers's demographic as well as social behavioural patterns to increse the coupon acceptance.

## Repository Link (GitHub)

1. [GitHub Link for Project "Coupon Acceptance Rate Analysis"](https://github.com/CoderNBR/Practical-Application-Mod-5)
2. [Jupyter Notebook](https://github.com/CoderNBR/Practical-Application-Mod-5/blob/main/customer_coupon_analysis.ipynb)

## Future Analysis

* Impact of weather, Temperature or TimeofTheDay on acceptance rate
* Does education or occupation play any role on Drivers who accept the coupons or not
* What is the impact on the direction the customer is going






   
