# kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends

## Overview of Project: 

The purpose of this analysis is to help an up-and-coming playwright, Louise, who is planning a crowdfunding campaign to fund her play, Fever. She hopes to raise at least $10,000 and wants to know if there are any hidden factors that might help her campaign succeed.

## Analysis and Challenges: 

I performed data analysis on several thousand crowdfunding projects to see if I could find any trends that make a campaign more likely to be successful. I analyzed two data points - launch date and goal amount.

## Outcomes by Launch Table
<img width="492" alt="Outcomes_by_Launch_table" src="https://user-images.githubusercontent.com/66224990/162629680-7a4f70b8-1e65-4464-9efc-e8852f0a2cdf.png">

## Outcomes by Goal Table
<img width="906" alt="Outcomes_by_Goal_table" src="https://user-images.githubusercontent.com/66224990/162629691-29958c5e-f7d1-4b28-bc27-2b1207cc763c.png">


I did not run into any challenges during my analysis. 

## Outcomes by Launch

The first analysis I performed compared the outcome of the campaigns based on the date they were launched. The graph shows the total number of campaign outcomes for each month of the year. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/66224990/162535786-e245d62d-b658-4c81-a3dd-6c52acc60c93.png)

I saw a trend based on launch date as there was a peak and decline in the success rate based on which month the campaign was launched. The most successful campaigns were launched in Spring and Summer months, with a peak in May. The least successful campaigns were launched in Winter months.  

I concluded the following: 
* A Spring or Summer launch would be more likely to result in a successful campaign. The graph showed the highest number of successful campaigns launched from April to August.
* There is a fairly consistent chance of failure throughout the year. The graph showed around 30 - 50 campaigns failed month by month.  

## Outcomes by Goals
The second analysis I performed compared outcome of the campaigns based on the fundraising goal amount. The graph shows the percentage of campaign outcomes for each goal amount group. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/66224990/162535812-afd5c23e-a0d8-4f1c-b523-86e1aab6e41a.png)

I did not find a trend of the success rate being affected by the goal amount, but the most successful campaigns were ones with goals of $1000 or less. There was also a peak around $35,000; however there is no evidence that the goal amount was the reason for that spike.

Campaigns in Louise’s goal range of “$10,000 to $14,999” were about 55% likely to succeed. 

Given the data did not point to a trend we concluded that goal amount does not have an affect on the success rate of the campaign. We suggest analyzing additional data points to find trends. 

## Limitations and Additional Analysis Suggestions

There were limitations in this data set as it only showed the total number of backers and the total amount pledged. It also did not include details about the plays, except for the title and a short blurb. 

Factors that could possibly show some trends would be:
* Amount each backer pledged
* Minimum pledge amount (if any)
* Genre of each play

If we had other data points such as the above suggestions we could create a box and whisker plot, which would show any possible outliers that may be skewing the distributions in our analysis. 
