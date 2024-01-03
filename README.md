# citbike-challenge

<a href="https://public.tableau.com/app/profile/evan.duffy/viz/CitiBike-Challenge_17041528829730/StationViews?publish=yes" re="nofollow">Link to Tableau Story</a>

I used the data from July 2023 in order to build this story. I had to create a new column, named "trip length", that measured the difference of each ride ID's "start at" and "ended at" columns in order to find the length of time the ride took. I had to first create a calculation within excel, paste those results as values into a new column so that they could be used to calculate it's time in minutes by multiplying the result by 1440 (amount of minutes in a day). The column was turned into a number column so that it could be read as a Measure. This took me longer than I'd like to admit but it did lead to a good bit of analysis.</br>

# The Story
![image](https://github.com/Duffye23/citibike-challenge/assets/58863493/8ddb2172-2d55-46f3-a0eb-6c0d96eaed53)</br>
I wanted to get a look at what the busiest day of the year was, and if it changed the general order of busy stations and it did. On July 26th, a crane crashed onto the street, derailing local traffic. https://www.reuters.com/world/us/crane-collapses-new-york-city-least-two-injured-2023-07-26/. This actually explains the drastic surge in casual members of the service, as people would have been diverted from public transport. The spiked usage makes a compelling case of funding CitiBike as it can be used as a vital auxiliary mode of transport in times of crisis. 

![image](https://github.com/Duffye23/citibike-challenge/assets/58863493/89d1d6ec-9b2a-4d53-9d35-ff6d33730d49)</br>
Since I looked at the busiest day of the year, it made sense to look at the least busy, especially given the sharp decline in usage. On the 16th, there was a tornado warning for New York and Connecticut. https://www.youtube.com/watch?v=aIAF3kjIigQ&ab_channel=CBSNewYork. Once again a perfectly reasonable explanation as to the phenomenon observed. It is comforting to know that there was no situation that arose on CitiBike's end that caused the dropoff.

![image](https://github.com/Duffye23/citibike-challenge/assets/58863493/3731477d-9e53-4434-aad5-e275f0a43d82)</br>
I took a holistic view of the month of July's usage and noticed that the main stations were identical for start and end dates, but interestingly were entirely different between the busiest and least busy day versus the whole month. It's interesting that these differ so much, though it could be that the disruption caused by the accident on the 26th displaced more people off their regular commutes that hailed from different areas than the norm. Also interesting is the loyalty of the members of the service, observed in the next viz. 

![image](https://github.com/Duffye23/citibike-challenge/assets/58863493/ba70c3b9-f6c0-41a0-a8a4-052c2eda5d27)</br>
On balance, member usage dwarfs casual usage. As shown in the previous viz, members are strongly loyal to repeated use of the service. However, what is interesting is that the casual user doubles members in terms of average trip length. This could be due unfamiliarity with where the stations are, or simply that the causual users are using the service mostly to sightsee or get around the city, whereas members could be using the service to more efficiently commute. This is backed up as the trend for lower usage occurs on weekends as can be seen in the first and second viz.

![image](https://github.com/Duffye23/citibike-challenge/assets/58863493/102d7b99-c7d5-479f-8915-63807ada9532)</br>
Finally, I made a map that observed each end station's average trip length. No real observation to be made in my opinion, as there are no visible patterns. Just an interesting visual and can be delved into further.

# Future Considerations
I think a study could be made into the use of CitiBike as a backup transportation alternative and could be used to secure further funding. 

Sources:
Carleton Bootcamp zoom recordings and lectures.
Subtracting time in Excel: https://support.microsoft.com/en-us/office/add-or-subtract-time-16aa6697-6d6e-49c1-8e2c-3398a7cad6ad#:~:text=Joy%20and%20Leslie.-,In%20cell%20D2%2C%20subtract%20the%20end%20time%20from%20the%20start,and%20dragging%20to%20cell%20D4.</br?
Converting minutes to Numeric: https://techcommunity.microsoft.com/t5/excel/convert-minutes-to-numeric-value/m-p/250689 </br>
July 26th explanation: https://www.reuters.com/world/us/crane-collapses-new-york-city-least-two-injured-2023-07-26/</br>
July 16th explanation: https://www.youtube.com/watch?v=aIAF3kjIigQ&ab_channel=CBSNewYork</br>




