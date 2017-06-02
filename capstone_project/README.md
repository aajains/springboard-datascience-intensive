# Likelihood of a flight getting cancelled

Commerical flights get delayed quite often but cancelled much less frequently. Even though the flight cancellation rate is not high, that one rare event causes a lot of troubles to passengers in terms of rescheduling their travel plans. It would be helpful to passsengers if they knew the chance that their flights will be cancelled or not. Travel planner and booking companies such as booking.com, expedia.com, kayak.com, priceline.com, etc.. can use a model capable of prediction the likelihood of the cancellation of a flight. They can then inform their customers well in advance, even before the airlines management inform the passengers, about the probability of the cancellation of their upcoming flight. The goal of this project is to develop such a predictive model for only U.S. domestic flights operating at selected airports.  


The flight data is acquired from the [Bureau of Transportation Statistics](https://www.transtats.bts.gov/DL_SelectFields.asp?Table_ID=236&DB_Short_Name=On-Time). This data contains information about each flights and their on-time performance, including delay, cancellation and diversion details. For this study, the data is acquired only for the years 2015 and 2016. 


Often the flight cancellations are caused due to bad weather conditions. Therefore, it is also important to have the hourly weather data at selected airports for 2015 and 2016. We use [wunderground.com API](https://www.wunderground.com/weather/api) to collect all the weather data. 
