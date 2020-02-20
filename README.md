# Project 2: Meteorology Instrument Package Assignment
Robert Reiten
19 February 2020
Meteorology Package

Code Link
https://github.com/Rmr1197/project2/blob/master/Project%202%20Code.ipynb

## Problem Statement

We are to answer questions that involve the use of meteorology instruments that measure wind speed and rain rate. The questions are as follows.

4) For each site, plot wind speed (in m/w) and rain rate (in mm/hr). Find these time windows: when it is windy and rainy, when it is rainy but not windy, when it is windy but not rainy, when it is not windy not rainy. Show each time period on your plot (for example, use different colors and have a legend to show which region each color represents)

5) Plot the cross-correlation function between wind speed at both sites? What is the highest correlation? What is the time lag?

6) Plot the cross-correlation function between rain rate at both sites? What is the highest correlation? What is the time lag? 

7) Is there any relationship between the time lag of wind speed and rain rate?

8) In another plot, calculate and plot the monthly average of the wind speed and rain rate for each site
What pattern do you see? Explain.
Which month had the highest rain rate? Which month had the lowest rain rate? 
Which month had the highest wind speed? Which month had the lowest wind speed? 
	
## Solution

### 4) Wind Speed and Rain Rate

<img src="https://github.com/Rmr1197/project2/blob/master/Images/1.PNG" height="250" width="350"><img src="https://github.com/Rmr1197/project2/blob/master/Images/2.PNG" height="250" width="350">

		Figure 1 & 2: Wind speed and rain rate plotted for both sites

Wind speed between the two sites seems to exert some patterns. Looking first at the rain rate. Around the months of March to June, the rain rate increases steadily for both. Where they differ is around the months of June to September, where offshore has a high rain rate and the shelf has a low rain rate. This makes sense because of evaporation in high temperatures creating more water in the air for precipitation over the ocean [Climate Central]. Wind speed appears to be higher this time offshore as well. This can be attributed to the sea breeze. Sea breeze is the wind caused by uneven heating of land and sea during day and night, which causes winds to blow near the shore [Sea and Land Breezes]. 

### 4) Cases of Wind and Rain

<img src="https://github.com/Rmr1197/project2/blob/master/Images/3.PNG" height="250" width="350"><img src="https://github.com/Rmr1197/project2/blob/master/Images/4.PNG" height="250" width="350">

		Figure 3 & 4: Different combinations of wind and rain cases
		
### 5) Cross-correlation of Wind

<img src="https://github.com/Rmr1197/project2/blob/master/Images/5.PNG" height="250" width="350"><img src="https://github.com/Rmr1197/project2/blob/master/Images/6.PNG" height="250" width="350">

		Figure 5 & 6: Overlayed wind velocity and Cross correlation representation 
		
The highest correlation value found was 0.6314. This mathematically states that there is some correlation between the two sites. This is to be expected as both areas are relatively close in the Pacific Ocean, and are affecteed by the same prevailing winds. These winds typically blow east-west due to the coriolis effect [National Geographic]. We expect these winds to affect both areas almost the same, but may have slightly different values due to sea breezes mentioned earlier affecting the more coastally located shelf site. 

### 6) Cross-correlation of Rain

<img src="https://github.com/Rmr1197/project2/blob/master/Images/7.PNG" height="250" width="350"><img src="https://github.com/Rmr1197/project2/blob/master/Images/8.PNG" height="250" width="350">

		Figure 7 & 8: Overlayed rain rate and Cross correlation representation 
	
The rain values had a maximum correlation value of 0.3516. This is lower than the wind value. This is presumably due to the evaporation in the air less inland on days of higher heat, causing higher precipitation, as mentioned previously. The rain rate correlation, contrary to the wind speed, had a lag of 124 days. This seems like an abnormally high lag value. This value could be a seasonal effect, where we may see higher rainfall in the ocean than closer to shore in Summer, but vice versa in the colder seasons.

### 7)

There does not seem to be any relationship between the lag of wind speed and rain rate based on the calculations. The lag values are 124 days apart, which is approximately a 34% difference over the whole year. 

### 8) Monthly averages of Wind and Rain

<img src="https://github.com/Rmr1197/project2/blob/master/Images/9.PNG" height="250" width="350"><img src="https://github.com/Rmr1197/project2/blob/master/Images/10.PNG" height="250" width="350">

		Figure 9 & 10: Monthly average of wind and rain
		
## References

National Geographic Society, “wind,” National Geographic Society, 13-Nov-2012. [Online]. Available: https://www.nationalgeographic.org/encyclopedia/wind/. [Accessed: 20-Feb-2020].

“Ocean Observatories Initiative.” Ocean Observatories Initiative, oceanobservatories.org/.

S. Ackerman, “Sea and Land Breezes,” WXWISE Sea Breeze. [Online]. Available: http://cimss.ssec.wisc.edu/wxwise/seabrz.html. [Accessed: 20-Feb-2020].

“Warmer Air Means More Evaporation and Precipitation,” Climate Central, 06-Sep-2017. [Online]. Available: https://www.climatecentral.org/gallery/graphics/warmer-air-means-more-evaporation-and-precipitation. [Accessed: 20-Feb-2020].
