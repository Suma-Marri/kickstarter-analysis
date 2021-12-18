# Kickstarting with Excel

## Overview of Project
Louise is a playwright who wants to kickstart a crowdfunding campaign to help fund her play. She has a play, Fever, ready and she also has has a big budget of $10,000. 

### Purpose
Before she starts anything, she wants to analyze pervious crowdfunding data to see if there are any factors that a crowdfund campaign successful or not. We made multiple charts and graphs to predit the best tips st atart her campaign. 

## Analysis and Challenges
[Theater_Outcomes_vs_Launch](Resources/Theater_Outcomes_vs_Launch.png)

[Outcome_vs_Goals](Resources/Outcomes_vs_Goals.png)

### Analysis of Outcomes Based on Launch Date
According to out line grpah in Theater_Outcomes_vs_Launch.png, shows that the best time for Louise to launch her crowdfund campaign is around May. She should avoid December - January time too, because the the success rate is lower compared to the other months. Also, crowdfund campaigns lauched during that time are usually failed or canceled more often during that time. 

### Analysis of Outcomes Based on Goals
According to the analysis in the file Outcomes_vs_Goals.png, the lower the goal, higher the chances of successfully reaching that goal. As shown in the line graph, you can see that if you have a $10,000 goal, the success rate is higher than the failed and cancel rate. With Louise's budget of $10,000, she has a high chance of successfully reaching her goal price. 

### Challenges and Difficulties Encountered
Something I had trouble with was when I was creating the analysis on the outcomes based on goals, I noticed that after creating the chart, there were lots of records missing. I decided to change most of the formulas I used from less than (<) to less than and equal to (<=) and greater than (>) to greater than or equal to (>=). By doing so, I was able to get more records in the analysis and make my analysis more accurate. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The best time to start a theater crowdfunding campaign is during the month of May and the worst time would be in January. I think that September - March time should be avoided because that is when the success rate is the lowest. 

- What can you conclude about the Outcomes based on Goals?

There is a higher chance that the campaign with be successful with lower goal amount. Once the goal is over $15,000, the success rate starts to decrease and there is a higher risk of failure. However, you can see that there is a higher success rate between $35,000 to $45,000. I beleieve that this happens because they know that their goal is really high, they probably planned the event and have the connections to run the crowdfunding campaign successfully.

- What are some limitations of this dataset?

One problem is that the range in the goals column is a large range, so graph will not have percise information. Also, we can also add another filter on country, so that way we can see if it is more successful or failed in one country. When we anaylzed the correlation between launch date and outcome, we took an analysis from 2009 to 2017. Maybe from 2009 to 2015, May was a very successful time, but in 2016 to 2017 was not and April would seem a better time to lauch a crowdfund campaign becuase the fail rate is really low. We could get a better conclusion if we filtered out the years.

- What are some other possible tables and/or graphs that we could create?

We can create a table and chart on how much more did they pledged. Did the failed crowdfunding campaigns close to their goal? Did the successful crowdfunding campaigns barely passed their goal? I think that a dot plot comparing with the goal and the profit amount would be a great way to see what makes is the best goal range. We could also compare the goal price and launch date with successful campaigns and also calulate the mean, mode, median, variance, and standard deviation to see the spread of the data. We can also plot the comarison on a scatterplot and get a linear regression to get the correlation between launch date and goals with campaign success.
