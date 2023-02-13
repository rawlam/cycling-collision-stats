# Project 1 - Cycling: How to Beat Collision Statistics



## Background


The importance of maintaining a healthy lifestyle, both physically and mentally, has been at the forefront for many people. In turn, people have been using cycling as a method of transportation, to not only maintain a healthy lifestyle, but from an economical and environmental perspective as well. There are inherent risks involved with cycling and safety is of utmost concern for cyclists. 


Our team is comprised of three upcoming data analysts who have worked in unification to identify characteristics and conditions that may impact cycling safety, analyze potential conditions and find any relationship within the data. Lastly, we have applied this by using findings to promote safer cycling conditions for all cyclists, both current and upcoming. 



## Project Summary: Questions and Assumptions


Our aim of this project was ascertain the following questions and made the associated assumptions:
1. What are the most common characteristics of cyclists involved in collisions?
* Cyclists involved in collisions occurred at a higher rate in males between the ages of 20-30 years.

2. What are the characteristics of other parties involved in cycling collisions?
* Other parties involved in collisions occurred at a higher rate in females between the ages of 40-50 years. 

3. What are external characteristics that influence cycling collisions?
* External characteristics, such as night-time and wet-roads, increased the risk of cycling collisions. 



## Analysis


Upon granted request, data was obtained through a valid API key from CycleStreets API (v2), which is a modern JSON interface to the routing engine and other CycleStreets Components. This enabled us to create a script obtaining 28,000+ rows of data. 

**Central London:** Pulled data and created plots to showcase general cycling collision data. 
* Map of all collisions from 1999 to 2021 in Central London
* Time Series: Number of total casualties from 1999 to 2021
* Frequency of casualties in 2021
* Total of each severity type from 1999 to 2021
* Total casualties by month from 1999 to 2021
* Types of overall casualities
* Map of fatal collisions in Central London


**Fatal Collisions:** Created plots to explore the relationships between fatal cycling collisions and the cyclists, other parties and external conditions.
* Cyclist: Sex and age
* Other Parties: Sex and age 
* External Conditions: Speed limit, road type, weather condition, light condition, road surface condition


**Conclusion:** Since the chi-square value of 36015.22 exceeds the critical value of 5.99, we conclude that the results are statistically significant. 



## Limitations


The following are limitations within the dataset:
* Does not consider the gender spectrum
* Bias of boundary selection for Central London
* Potential inconsistencies of data reporting
* Hit and run collisions



## Next Steps


Next steps ...



## Acknowledgements


Many thanks go to the following:
* CycleStreets API
* UofT Data Analytics including the teacher and teaching assistants 



## References 


* The Collision data API provided information on collisions based on STATS19 data between the years 1999 and 2021 inclusive. The Collision report API provided data for a single collision location from the STATS19 data.
    * Both above APIs are accessed at: https://www.cyclestreets.net/api/v2/collisions.location/. 


- - -
