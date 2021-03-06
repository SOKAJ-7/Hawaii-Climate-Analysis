# Hawaii-Climate-Analysis

## Overview
The purpose of this analysis is to determine the viability of a 'Surf n' Shake' shop on the island of Oahu. This prospective shop is an ambition of mine (for the purposes of this analysis) and I need to convince a potential investor that this shop will succeed. The problem is that the investor has already lost an investment on a previous surf shop due to not accounting for poor weather in December and the resultant decrease of sales. The purpose of this project is to preform statistical analysis on the weather data from Hawaii dating back to 2010, and hopefully put the concerns of our investor to rest. To do this we will be using python and SQL lite to query and analyze our data.

## Results
Three takeaways from this analysis are as follows:

-December will be only four degrees farenheit colder on average than in June. The average temperature in December is 71 F while in June the average temperature is 75 F. Both of these average temperatures are fairly warm so it's reasonable that both surfing and enjoying ice cream could be popular based off temperature alone.

-There will be more slow days in December. While the average temperatures are similar between June and December, there could be more days under 70 F in December as the coldest 25% of days in December are all under 69 F. In June, the 25th percentile for temperature is still 73 F. Logically, there will be more days of extreme cold in December, relatively speaking. This will most likely result in more days where the public will be less inclined to eat ice cream and go surfing.

-The spread of temperature will be similar between June and December. Both of the months' temperature records have a standard deviation close to 3. December's is slightly higher at 3.74 so there may be slightly higher variance in temperature during Decemeber but it should not be too extreme so as to impact business.

Figures 1 (June) & 2 (December) below demonstrate the basic statistical analysis of the temperature patterns in these months.




![June_temps](https://user-images.githubusercontent.com/93050931/148696122-e3d30fff-6f69-4956-9936-d4fa830ca191.PNG)

Figure 1: June Temperature

![December_temps](https://user-images.githubusercontent.com/93050931/148696133-8346248d-93a8-4b6c-a365-55d13b634202.PNG)

Figure 2: December Temperature



## Summary
Based on the statistical analysis we conducted, it can be said that June will be a warmer month than December as is to be expected. However, both months have fairly high average temperatures of 75 and 71 F, respectively. If we assume 68 F (20 C) to be the minimum temperature to not impact business, it appears that 'Surf n' Shake' would be a viable business through December. Furthermore, ~75% of days in December will be over 68 F while an even higher amount of days are above 68 F in June. This means that a large majority of days in both months are warm enough to support the business. If we look at the standard deviations of this data, it can be seen that bith months show similar figures of 3.25 (June) and 3.74 (December). This is supported by the fact that the difference between maximum and minimum temperatures is larger in December than in June.

Based off of this analysis, it would seem that 'Surf n' Shake' should have no problem succeeding in December. But, there is a lot more to weather than just temperature alone. So, it would be prudent to conduct analysis on other weather patterns. Listed below are my suggestions:

-Precipitation analysis: Surfing is a strictly outdoor activity and few things drive people indoors than a rainy day. It would only make sense to compare preciptitation figures between June and December to approximate the amount of days that will be written off due to rain.


-Measurment coordinates: The weather pattern measurements will be taken from various station of which we know the coordinates of. Using this data, we can establish a relationship between weather patterns and station coordinates to determine which parts of Oahu will receive the most rainfall and/or lower temperatures. With this knowledge, we can pick a more optimal location for our business.
