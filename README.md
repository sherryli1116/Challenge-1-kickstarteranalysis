# An Analysis of Kickstarter Funding Campaigns
## Overview of Project
Throughout this project, we wanted to help Louise, an upcoming playwright, filter out the successful funding campaigns in order to help funding her new coming play *Fever*. We were able to generalize data through more than 4000 Kickstarter campaigns and by looking at the "theater" category and "play" subcategory both independently. Last, we categorized the data by different spending levels and time frames to determine the amount of money she should set as her fundraising goal and also the best time to launch her campaign. 
### Purpose
This project aimed at providing insight analysis to Louise’s fundraising goal by seeing how different campaigns were performed in aspects to their launch dates and funding goals. 
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
In this analysis, we first chose the category "theater" and looked at each month individually to determine which month have launched the most number of successful campaigns. We visualized the data by using a pivot table, and the table contains a count of row labels, which are display by the months in a year. The number of successful, failed, canceled campaigns are also shown as well as the total amount of campaigns. 
A line chart was made in the end to show the overall trend of the successful launched campaigns data by months, it also displays the failed and canceled campaigns as supplementary information. 
![This is an image](https://github.com/sherryli1116/Challenge-1-kickstarteranalysis/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
In this analysis, we chose to use subcategory "play" as criteria to look at the successful launched campaigns by setting different levels of monetary goal, and the monetary goals were set from less than $1000 to more than $50000. We also calculated the percentage of successful, failed and canceled campaigns using the numbers we got from applying different parameters to the COUNTIF() function. 
A lined chart was made in the end to show the percentage of successful, failed, and canceled campaigns with the different levels of monetary goals, ranging from less than $1000 to more than $50000.
![This is an image](https://github.com/sherryli1116/Challenge-1-kickstarteranalysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
During the process of analyzing the Outcomes Based on Goals data, we had to use function COUNTIF() in order to give different parameter and filter out the useful information we need. We must make sure different monetary value level are not overlapping, for example we have "1000 to 4999" as an increment, then the next increment should start with greater than or equal to 5000 instead of 4999, because 4999 has already been included in the previous increment. Moreover, when we were creating pivot table that shows outcomes by launch data, we need to remember filter out "theater" since we are helping Louise to pursue her funding goal. It is very easy to ignore this detail, and we must always remember our final goal; what information we want to extract when analyzing the data. 
## Results 
From the Outcomes based on Launch Date data sheet, we can conclude that May is a good time for Louise to launch her campaign. According to our data, May has the most number of successful launched theater campaigns. In addition, June has the second greatest number of successful launched theater campaigns, and therefore theater campaign that has duration from May to June will also have high possibility in being successful. 
From the Outcomes based on Goals data sheet, we can conclude that campaigns goals that were set less than 1000 has the highest percentage successful in launching the campaigns. 
