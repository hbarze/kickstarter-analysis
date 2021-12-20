# Kickstarting with Excel

## Helping Louise create funding campaigns based on previous similar theatre campaigns

### Purpose
## The Purpose of this analysis is to help Louise use the results of similar campaigns to compare the launch dates and funding goals of those similar campaigns to her campaign. This information can help Louise determine the best time of the year to launch a campaign for her plays and create a funding goal that aligns with other successful similar plays. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The analysis of outcomes based on launch date resulted in a line chart with 3 lines for successful, failed, and cancelled campaigns. The x axis is the time at which the campaign was launched, and the y axis states the percentage of campaigns that were either successful, a fail, or a cancelled campaign based on the time at which they were launched. 

# An image of the outcomes based on launch date chart is displayed here: 
![/Users/henrybarze/Desktop/VDAB Projects/Modules/Module 1- Excel/Module 1 Challenge/Resources]

# Challenges I encountered during this analysis included determining the correct columns to include in the value section of the pivot table. At first, I was confused because when I inserted "outcomes" into the value section of the pivot table, I had "live" and "(blank)" as categories in the pivot table. However, after filtering the outcomes to exclude the "live" and "(blank)" columns, my pivot table appeared identical to the example provided, and then my chart also was correct. 

### Analysis of Outcomes Based on Goals
#The analysis of outcomes based on goals resulted in a pivot chart that displayed the percentage of successful and failed campaigns based on their fundraising goals, in funding goal brackets starting at less than 1000, next from 1000-4999, and then in 5000 increments until reaching goals in excess of 50000. Using the line chart I created, I can see that the most successful campaigns for plays used a fundraising goal between 25,000 and 25,999- these fundraising goals had a success rate of 100%. Campaigns using fundraising goals between 45,000 and 49,999 had the worst success rate, at 0%. 

And image of the outcomes based on goal chart is displayed here: 
![/Users/henrybarze/Desktop/VDAB Projects/Modules/Module 1- Excel/Module 1 Challenge/Resources]

### Challenges and Difficulties Encountered
# This analysis was straightforward for me, however I did run into a problem when I first created the line chart. My chart compared to the provided example was correct except for the 45000-49999 bracket, and the greater than 50000 bracket. After scanning through the excel code, I found a typo where I had accidentally written "=COUNTIFS(Kickstarter!$F:$F, "canceledl", Kickstarter!$D:$D, ">=50000",Kickstarter!$R:$R, "plays")" in cell D13, instead of "=COUNTIFS(Kickstarter!$F:$F, "canceled", Kickstarter!$D:$D, ">=50000",Kickstarter!$R:$R, "plays")". Once I removed the "l" from the end of "canceled", my chart updated and looked exactly like the example. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
# Two conclusions I can draw from the outcomes based on launch date are that the most successful campaigns are launched in early summer months (May, June, and into July) and that the campaigns that failed the most frequently were launched in October. Overall, campaigns launched in any month are more likely to be successful than fails, except for in December, where a campaign appears to have a success or failure rate of a little less than 40%. 
- What can you conclude about the Outcomes based on Goals?
# When examining outcomes based on goals, I can determine that the highest likelihood of a successful campaign uses a funding goal between 25000-25999, and that overall a funding goal for a play is more likely to be successful if the goal is less than 29999, with exceptions in the 35000-44999 range. 
- What are some limitations of this dataset?
# A limitation of this dataset is that it only appears to have campaigns launched as early as 2009, and as late as in 2017. This data is a bit outdated, and it would be better if we had more recent campaign data to help Louise create the best funding goal estimates for her plays. 

- What are some other possible tables and/or graphs that we could create?
# To further help Louise determine successful parameters of her funding projects, we could also analyze the success rates of plays based on the country they were launched in, the length of the name of the play, the average number of backers a successful campaign has, and the length of each campaign. 
