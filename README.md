# Kickstarting With Excel
## Overview of Project
### Purpose
An analysis was completed of successful, failed, and canceled kickstarter campaigns. This analysis looked at the outcomes of 1,369 Kickstarter campaigns for theater based on their outcomes which were either successful, failed, or canceled. The analysis then looked at the outcomes of all theater campaigns based on their start date and play campaigns based on their funding goals.

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
First, an analysis of the outcomes Kickstarter campaigns for theater based on launch date was completed. Similarly to the previous analysis conducted on theater and play campaigns, May had the highest number of launched campaigns at 166, and also the highest number of successful campaigns at 111 and highest number of failed campaigns at 52. The number of successful campaigns continue to decline until August, whereas the failed campaigns were roughly 50 from May to August. The highest number of canceled campaigns was 7 for campaigns that began in January, which declined to about 3 for the remainder of the year, with no canceled campaigns being started in October.
![theater_outcomes_vs_launch](https://user-images.githubusercontent.com/82389466/115124093-6266aa80-9f8e-11eb-91b0-4eb1008fe04a.png)

### Analysis of Outcomes Based on Goals
Lastly, an analysis of the outcomes of play campaigns based on their funding goals was conducted. The highest percentage of successful plays and lowest number of failed plays, 76% and 24% respectively, occurred for campaigns with funding goals less than $1000 USD. Campaigns with funding goals between $1000 and $5000 USD had the second highest percentage of successful campaigns and lowest number of failed campaigns with a success rate of 73% and failed rate of 27%. Play campaigns with funding goals between $45,000 and $50,000 USD had the highest number of failed campaigns and lowest number of successful campaigns, with failed campaigns making up 100% of this campaign goal range. There were no canceled campaigns for plays in this data set.
![outcomes_vs_goals](https://user-images.githubusercontent.com/82389466/115124142-b07bae00-9f8e-11eb-8be4-74eb5e88d34a.png)

### Challenges and Difficulties Encountered
The main challenge of working with this data set was creating a pivot table to list the number of successful, failed, and canceled theater campaigns based on their month of launch. This challenge was overcome by filtering the data set on the theater parent category field and years field, by adding them to the filters for the pivot table. Then, the data had to had to be organized by months using out Date Created Conversion field on the rows section of the table, and then removing the additional date fields to display only the months of the year.

## Results
Based on the analysis of the outcomes based on launch date data set, I can conclude that May is the best time for Louise to launch her play campaign because the highest number of successful campaigns begin in may. I can also conclude that while successful campaigns occur much less in October than in May, that there is little chance she will have to cancel her campaign because the data indicated that no canceled theater campaigns began in October.

Based on the analysis of the ouctomes based on goals data set, I can conclude that Louise's campaign goal should be less than $5000 USD, as campaigns with goals less than $1000 USD and goals between $1000 and $5000 USD have the highest percentage of success and lowest percentage of failure. I can also conclude that a campaign goal of $45,000 USD or more would likely be unsuccessful.

This data set has several limitations. For the outcomes based on launch data set, we do not know what the average campaign goals are for each month of the year. Secondly, for the outcomes based on goals data set, we do not have any data regarding how many campaigns were canceled, or what their goals were. Lastly, the data set did not contain a total run time for campaigns, which may affect their degree of success, failure, or cancellation.

This data set would benefit from additional tables and graphs. Firstly, a table and graph displaying the outcomes percentages based on campaign length would be helpful in determining how long successful, failed, and canceled campaigns run for. Lastly, a table and graph displaying the campaign length based on campaign goals would be helpful in determining how long the successful, failed, and canceled campaigns ran for before reaching their outcome.

<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

# An Analysis of Kickstarter Campaigns
An analysis of 4,113 Kickstarter campaigns was completed to determine the number of campaign outcomes which were: successful, failed, cancelled, and live campaigns.
---
First, this analysis contained a breakdown of campaign outcomes by parent category. This analysis revealed that Kickstarter campaigns in the "Theater" parent category were the most common and most successful, and also had the most failed campaigns.
---
![Parent Category Outcomes](https://user-images.githubusercontent.com/82389466/114943750-7a1a2380-9e14-11eb-88c3-a2a8e93f8d91.png)
---
Second, an analysis of campaign outcomes by sub-category was completed. This analysis revealed that campaigns in the "Plays" sub-category vastly outnumber all other sub-categories, and were the most successful. 
---
![Subcategory Outcomes](https://user-images.githubusercontent.com/82389466/114943969-d4b37f80-9e14-11eb-8302-355eaeb07452.png)
---
Third, an anlysis of campain outcomes by the month in which they were started was completed. This analysis revealed that most campaigns began in May, and that the highest number of successful and failed outcomes was also in May. 
---
![Outcomes Based on Launch Date](https://user-images.githubusercontent.com/82389466/114944183-22c88300-9e15-11eb-8d38-09c26139be74.png)
---
An analysis of 5 Kickstarter campaigns for "Plays," for the Edinburgh Fringe Festival was also completed. This analysis revealed that all 5 plays met or exceeded their campaign goals and were successful. 
---
An analysis of successful and failed campaigns for the "Plays" subcategory in the United States was also completed. The data indicates that plays with an average goal of about $5000 USD were successful, whereas plays with an average goal of about $10,500 failed. The mean was lower than the standard deviation of goals and pledged sets of data for the successful campaigns, indicating that the data below the mean is closer to the center. The upper quartile and mean for goals and pledged data sets for successful campaigns indicates that both sets of data have a similar distribution. For the unsuccessful campaigns, the mean was much lower than the standard deviation for the goals and pledged data sets, which indicates there are some outliers that drive the data. Additionally, the upper quartile of the goals and pledged data sets was close to the mean, indicating both sets of data had a similar distribution. 
---
Lastly, an analysis of of campaigns for the "Musical" sub-category in Great Britain was completed. This data indicated that most campaigns for the "Musical" subcategory had goals amount between $1000 and $5000 USD, with a mean of $4000. Most of the campaigns in this subcategory had a pledged amount between $0 and $1500 USD, with a mean of $1000 USD. This anlysis revealed that on average, Kickstarter campaigns in Great Britain within the "Musical" subcategory had an average pledged amount 4 times lower than the average goal amount.
---
![Great Britain Data Distribution](https://user-images.githubusercontent.com/82389466/114946187-b0f23880-9e18-11eb-94e5-fd3fe04b49bf.png)
---
I reccommend that Louise launch her initial play campaign with a goal of $5,000 USD in the US in May, which is the best time of the year to start a successful campaign based on the Kickstarter data that was analyzed. The "theater" and "plays" parent category and sub-category, respectively, were the most common and successful campaigns. Sucessfull campaigns for "Plays" in the US had an average goal of $5000 USD, and it is reccommended she lower her budget to meet this goal successfully. Failed campaigns for "Plays" in the US had an average goal of $10,000 USD, which is Louise's goal, which is not likely to be met. Additionally, I reccomend that Louise lower her budget for her musical to $1000 USD, as the $4000 USD budget is four times higher than the average pledged goal for musical campaigns in Great Britain.
---
