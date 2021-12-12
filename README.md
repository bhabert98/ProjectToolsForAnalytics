## Tools for Analytics – Group Project
---
### Group 6
##### Bastien Habert – bh049
##### Sadre Yaker – sy3009
---

Project 1 - Top 10 causes of 311 calls <br />
Chosen zip code: 10466 <br /> <br />
The first file (Top10.ipynb) gives some insights about the 311 calls in New York City. First, it describes the number of incidents in 2020 with respect to the different Zip Codes. Then, it provides a list the 10 most common incidents around a chosen Zip Code (10001), with the name and the number of incident of each type.

The second file (Parking.ipynb) compares the number of illegal parking in the chosen Zip Code (10001) against the overall number of illegal parking. It calculates the rate of illegal parking with respect to the total number of incidents for:
-	The chosen Zip Code
-	All the different Zip Codes 
The function higher_parking_proportion then compares each ratio against each other, and returns True if the ratio of the chosen Zip Code is larger than the one for every Zip Codes, and false in the opposite case.
