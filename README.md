# Kickstarter_Challenge

## Overview of Project
### Discover insights about Theater/ Play campaign outcomes when comparing "successful", "failed", and "canceled" campaigns based on launch date and funding goals. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
<img width="476" alt="Theater_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/111904266/194728252-857ac424-0c0c-4564-903f-c5b457e5793f.png">


### Analysis of Outcomes Based on Goals
<img width="589" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/111904266/194728264-14302d53-991c-4914-b805-edbfcf066c53.png">


### Challenges and Difficulties Encountered
Upon first look at the Kisckstarter dataset I noticed a few things right away. The first being the Date Created and Date Ended were numbers I have never seen before. Learning about UNIX timestamps was a first for me along with the conversion. The Second is two columns I still don't understand (maybe since we didn't use them) Staff_pick & Spotlight. 

A challenge I ran into was durring the analysis Outcomes based on Goals using =Countifs. My total number "failed" was one short of the actual total and it took me a while to find that one. After creating the line chart I realized I forgot the Row 40000 to 44999, which didn't have a value in "successfull" or "canceled" so it was an anomaly for a while.  

## Results

### Conculsion about Outcomes based on Launch Date
Kickstart campaings in the Theater categorgy had the hightest success rate when started in May & June and had a 50% chance of being successful when started in December. 

### Conslusions about Outcomes based on Goals
The Kickstarter campaings in the Theater/ Plays category had a 50% or more success rate when the fundraising goal was less than $20000. 

### Limitations of this Dataset
* This data is colected from year 2009-2017 which is less than 10 years and not the most recent. 
* This data does not acount for the cost associated with the campaign. 
* Marketing/ Events used to accopmlish campaign goals.

### Other possible tables or graphs we could create?
* It would be useful to know how many days the campaign was open. Was it too short or too long to be successful?
* Was the number of backers a factor in being successful for not?
* Which country had the most successful Theater/Play kickstarter campaigns? Which country had the least? 








