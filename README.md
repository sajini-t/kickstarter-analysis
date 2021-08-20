# Kickstarting with Excel
Performing analysis on Kickstarter data to uncover trends

## Overview of Project

We are making an analysis for Louise whose play 'Fever' reached her campaing goal in a short period of time. She wants to know how different campaigns fared in relation to their launch dates and fundraising goals. For this purpose, we are using Excel to create two analyses: outcomes based on goals and outcomes based on launch dates.

### Purpose
Our analysis can help Louise determine if she made the right choices of when she launched her campaign and for how much she set the campaign goal for her play 'Fever'. It will also help her future campaigns to be successful.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
<img src = "resources/Theater_Outcomes_vs_Launch.png" width = 500)>
Looking at the outcomes based on launch dates, we see that the month of May followed by June have the highest successful campaigns.

### Analysis of Outcomes Based on Goals
<img src = "resources/Outcomes_vs_Goals.png" width = 500)>
We see that the category with goal amount less than 1000 followed by goal amounts >=1000 and <=4999 have the highest number of successful plays.

### Challenges and Difficulties Encountered
With the Countifs function, even though I used fill handle to copy the formula across all cells and columns, I still had to change some values for all the cells. I should have used absolute reference for some of the Countifs. To cross check if my Countifs were correct, I created a seperate column to count the percentages of successful, failed and canceled and all added up to 100%.

## Results

### - What are two conclusions you can draw about the Outcomes based on Launch Date?
1. From the line graph I infer that the theater campaigns are the most successful during the months of May followed by June. So it would be the best time of the year for Louise to launch her campaign.
2. Even if the total number of projects is the highest in the months of May followed by June, number of successful campaigns are double the number of failed campaigns during these months. Canceled Theater campaigns are consistently very low for the entire year (below 10 canceled campaigns) for the Theater category. So it seems very promising to run Theater campaigns in the months of May and June.
### - What can you conclude about the Outcomes based on Goals?
1. Campaigns for the Subcategory 'play' with goals less than $1000 have the highest success percentage rate even though they only come second to the $1000 to $4999 category in the highest total number of campaigns. So, it would be good for Louise to set her goal in the <1000 category. Smaller campaign goal, higher success rate.
### - What are some limitations of this dataset?
There could be a possbility that successful movies come from experienced/successful directors. We don't have any information pertaining to the director of the plays/musicals etc.
### - What are some other possible tables and/or graphs that we could create?
A box and whisker plot between the goal and the pledge amounts for the Theater category can present a better picture of how high Louise can set her campaign's goal. We can also cross check if the successful plays that fall in the less than $1000 and $1000 to $4999 category correlate with the pledged amount. We can easily spot the outliers and decide whether to include them or not.

