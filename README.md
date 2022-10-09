# Kickstarter_Challenge

## Overview of Project
### Discover insights about Theater/ Play campaign outcomes when comparing "successful", "failed", and "canceled" campaigns based on launch date and funding goals. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
<img width="476" alt="Theater_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/111904266/194728252-857ac424-0c0c-4564-903f-c5b457e5793f.png">


### Analysis of Outcomes Based on Goals
<img width="589" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/111904266/194728264-14302d53-991c-4914-b805-edbfcf066c53.png">


### Challenges and Difficulties Encountered
The first challenge I encountered was noticing the Date Created and Date Ended were numbers I have never seen before. Learning about UNIX timestamps was a first for me along with the conversion. The second challenge is two columns (maybe since we did not use them) Staff_pick & Spotlight. Both these columns are TRUE/ FALSE statements which I am still unclear of their meaning and relation to the data.

A difficulty I ran into was during the analysis Outcomes based on Goals using =COUNTIFS. My total number "failed" was one short of the actual total and it took me a while to find that one. After creating the line chart, I realized I forgot Row #12 - 45000 to 49999, which did not have a value in "successful" or "canceled" so it was an anomaly for a while.

## Results

### Conclusion about Outcomes based on Launch Date
Kickstart campaigns in the Theater category had the highest success rate when started in May & June and had a 50% chance of being successful when started in December. 

### Conclusions about Outcomes based on Goals
The Kickstarter campaigns in the Theater/ Plays category had a 50% or more success rate when the fundraising goal was less than $20000. 

### Limitations of this Dataset
* This data set was collected from year 2009-2017 which is less than 10 years and not the most recent. 
* This data does not account for the cost associated with the campaign. 
* What kind of marketing and or events were used to accomplish campaign goals?

### Other tables or graphs we could create?
* A pivot table with a line graph showing how many days the campaign was open would be useful. Was it too short or too long to be successful?
* Was the number of backers a factor in being successful for not?
* A table with a stacked bar graph showing individual country success with Theater/Play Kickstarter campaigns would be interesting. 








