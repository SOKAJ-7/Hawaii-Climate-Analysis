# Hawaii-Climate-Analysis

## Overview
The purpose of this analysis is to determine the viability of a 'Surf n' Shake' shop on the island of Oahu. This prospective shop is an ambition of mine (for the purposes of this analysis) and I need to convince a potential investor that this shop will succeed. The problem is that the investor has already lost an investment on a previous surf shop due to not accounting for poor weather in December and the resultant decrease of sales. The purpose of this project is to preform statistical analysis on the weather data from Hawaii dating back to 2010, and hopefully put the concerns of our investor to rest. To do this we will be using python and SQL lite to query and analyze our data.

## Results
Three takeaways from this analysis are as follows:

-December will be only four degrees farenheit colder on average than in June. The average temperature in December is 71 F while in June the average temperature is 75 F. Both of these average temperatures are fairly warm so it's reasonable that both surfing and enjoying ice cream could be popular based off temperature alone.

-There will be more slow days in December. While the average temperatures are similar between June and December, there could be more days under 70 F in December as the coldest 25% of days in December are all under 69 F. In June, the 25th percentile for temperature is still 73 F. Logically, there will be more days of extreme cold in December, relatively speaking.

-The spread of temperature will be similar between June and December. Both of the months' temperature records have a standard deviation close to 3. December's is slightly higher at 3.74 so there may be slightly higher variance in temperature during Decemeber but it should not be too extreme so as to impact business.

Figures 1 (June) & 2 (December) below demonstrate the basic statistical analysis of the temperature patterns of December and June.

![June_temps](https://user-images.githubusercontent.com/93050931/148696122-e3d30fff-6f69-4956-9936-d4fa830ca191.PNG)

(Figure 1)

![December_temps](https://user-images.githubusercontent.com/93050931/148696133-8346248d-93a8-4b6c-a365-55d13b634202.PNG)

(Figure 2)



## Summary
