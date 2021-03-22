# An Analysis of Kickstarter Campaigns
An analysis of historical kickstarter campaigns, focused on theater projects, to better understand how our client Louise's recent campaign compares to other similar campaigns.
## Overview of Project
The goal of this analysis is to provide our client, Louise, with historical information on Kickstarter campaigns similar to her campaign. We are working to help our client understand the variables that can help make a campaign successful.
## Analysis and Challenges
Our analysis focused primarily on the launch date and campaign goals, as these are variables that we can control, and have an effect on the success of a campaign. 
### Challenges
Some extreme outliers on goals and funding provided a challenge, but we were able to work around this by dropping campaigns into goal dollar value categories, and were thus able to ignore or look at unusually high dollar targets in it's own category. There were relatively few of these high dollar value campaigns, so the sample size may not be high enough to draw conclusions in that range. The data also includes campaigns that are currently live, and thus should not be compared. We filtered these out of the data, so we were only looking at completed Kickstarter campaigns.
### Analysis
Launch date appears to have an effect on the success of past Kickstarter campaigns. 

![Theater_Outcomes_Based_On_Launch_Date] (https://github.com/aaronsond/kickstarter-analysis/blob/ce7a59254cc56c6690a4c28b564ee0cec64fc972/Resources/Theater_Outcomes_vs_Launch.png?raw=true)

As the above chart shows, the success rate of Kickstarter campaigns increases when they are started in a specific time of year; starting in April, peaking in May, then gradually decreasing the rate of successful campaigns until September. There are also local peaks in Febuary and October, though they may not be significant. 

The dollar value of a campaign also effects it's probability of success. 

![Outcomes_vs_Goals](https://github.com/aaronsond/kickstarter-analysis/blob/ce7a59254cc56c6690a4c28b564ee0cec64fc972/Resources/Outcomes_vs_Goals.png)

Lower dollar value campaigns have succeeded at a higher rate, gradually declining as the campaigns' expectations get higher. There is a rise again in the percent of success in the $35,000 to $39,999 and $40,000 to $45,000 categories, but these categories account for a total of 9 campaigns. Conclusions should not be drawn from a sample of 9 campaigns. 

## Results

### Launch Date
From looking at the data on launch date, we can make two conclusions. Theater kickstarter campaigns are more likely to succeed when launched in May, with similar but less strong effects in April, June, and July. We can also conclude that many more campaigns of this type are launched in that window; the number of launched campaigns is much higher during this time. 

### Goals
The data on goals on these campaigns, and their outcomes, makes it clear that campaigns with lower goals are more likely to reach them. 

### Limitations
This is not a perfect data set for all conclusions. For one, there is very little data on high dollar value target campaigns, because there have not been many campaigns in the higher money categories. The outlier, high dollar value campaigns are both hard to compare with other data, and also can skew our understanding of the rest of the data set, as they are outliers in the data. 

### Other Possible Tables and Graphs

Other angles of analysis that may be worth looking into include box plots for financial targets, to better vizualize the outliers and where the bulk of the campaigns reside. We could also build a table to look at how this data may vary by country; I would suggest a line chart where percentage of successful campaigns is represented for different countries at different dollar values. We could also look at the number of backers, and average donation size, to better understand how the size of the donator pool influences success.
