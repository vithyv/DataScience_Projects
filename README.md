# DataScience_Projects
## Assignment 5.1: Will the Customer Accept the Coupon?

Context

Imagine driving through town and a coupon is delivered to your cell phone for a restaurant near where you are driving. Would you accept that coupon and take a short detour to the restaurant? Would you accept the coupon but use it on a subsequent trip? Would you ignore the coupon entirely? What if the coupon was for a bar instead of a restaurant? What about a coffee house? Would you accept a bar coupon with a minor passenger in the car? What about if it was just you and your partner in the car? Would weather impact the rate of acceptance? What about the time of day?

Obviously, proximity to the business is a factor on whether the coupon is delivered to the driver or not, but what are the factors that determine whether a driver accepts the coupon once it is delivered to them? How would you determine whether a driver is likely to accept a coupon?

Overview

The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

Data

This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. There are five different types of coupons -- less expensive restaurants (under 20), coffee houses, carry out & take away, bar, and more expensive restaurants (
20 - $50).

## Findings of Bar Coupons Acceptance Analysis:
Based on these observations, what do you hypothesize about drivers who accepted the bar coupons?

Those who go to bar more often (i.e. more than 3 times a month) are more likely to accept bar coupons
Those who go to bar more than once a month and are older than 25 years are more likely than others to accept bar coupons
Those who go to bar more than once a month and have no kid passenger on the drive and are not in farming, fishing or forestry occupation have a higher propensity to accept the bar coupons

## Findings of Restaurent $20-50 Coupon Acceptance Analysis:
Based on these observations, what do you hypothesize about drivers who accepted the Restaurent $20-50 Coupons?

Those who visits expensive restaurents 4 or more times a month with partner as passenger and no urgent place as destination tend to accept restaurent $ 20 - 50 coupons higher rates (66.7%) compared to all others (44%).
That is a 22.7% difference in acceptance rate.

Based on earlier analysis, time of day and expiration times do also matter. For 7AM and 10PM drives are less likely to accept 
coupons for expensive restaurents. Also, recipients seem to prefer one day expiration compared to shorter durations for expensive restaurent coupons.
