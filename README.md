# **ANALYSIS OF LOUISE'S KICKSTART CAMPAIGN**

## **Overview of Project**
### Purpose
Louise wants help with insights on project fundraising campaigns for theatre. 
Our purpose is to assess the relationship between fundraising goal levels and 
timing of campaign launches to develop insight into the most successful outcomes. 
Through an analysis of several thousand crowdfunding project data, we hope to 
uncover any hidden trends and offer a recommendation.


## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date

The approach to this analysis was done by pivot table and line graph. It was filtered by theatre
accounting for the number of times each possible outcome had occurred in a specific month
of a campaigns' launch date regardless of year launched. A line chart based on theatre
outcomes versus the launch months was created to see the peeks and valleys of 3 line 
trends corresponding to "successful", "failed" and "canceled" outcomes.

![](https://github.com/KJRE54/ProjectPics/blob/main/Theater_Outcomes_vs_Launch.png)

![](https://github.com/KJRE54/ProjectPics/blob/main/OutcomesBasedOnLaunchDatePivotTbl.png)

 

### Analysis of Outcomes Based on Goals
The approach to this analysis was to group the project's goal amounts in
dollar range categories and then count the number of projects that fell into
the outcome categories. Additional columns were created to look at the percentage
change of each outcome per dollar range and a line chart was created based
on this relationship to draw insight. 

![](https://github.com/KJRE54/ProjectPics/blob/main/Outcomes_vs_Goals.png)

![](https://github.com/KJRE54/ProjectPics/blob/main/Outcomes_vs_GoalsPivotTbl.png)
 

### Challenges and Difficulties Encountered
There were no difficulties encountered doing this analysis, but COUNTIFS statements 
could be challenging if one is not careful to set up the criteria levels 
correctly or select the right columns with the "$" signs in the excel formulas to 
hold columns and/or rows stationary.  Pivot tables can also pose a challenge if
the right labels are not assigned in the right pivot fields. Lastly, there is the 
challenge of accurately interpreting visual data or visualizing data in such a way 
that it does not really produce much insight.

## Results---

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The two conclusions drawn from this chart was among the campaigns in the theatre
category, the campaigns launched in between May & June and October were the
most successful based on the number launched. However, May & June months represent the
greater opportunity peak for successful launches. May and June represent 25% of most
campaigns launched during those months. Successful launches for all months represent 
61% of the total theatre-based campaign launches. Also, the outcomes' lines in the chart 
highlight the time range over months that infers seasonality of successful and failed campaigns.

- What can you conclude about the Outcomes based on Goals?

One can conclude by the greatest number of projects being skewed mostly towards
lower dollar ranges that Louise's estimated $12,000 fundraising goal fits in the 
dollar range with mostly successful campaigns on a percentage basis. This is a positive
validation for one of Louise's criteria.  Also, the graph chart shows that fundraising 
goals have a increased chance of fairing well if she raises funds that are mostly in the 
"less than $15,000" range. There is also smaller, but possible chance of success if the 
funding were to fall between $35,000 and $50,000. 

- What are some limitations of this dataset?

The measuring of different currency is not apples to apples. All money calculations should 
be based on one currency type to be sure we are capturing the same value. Filtering by year,
would've made the insights from data more acute. There may have been other economic forces 
happening in any given year that could influence the fundraising goals and thefore the results 
gleaned. But the challenge was focused on the number of projects by goals without giving attention
to different currency types that could skew the quality of insight drawn from analysis.

- What are some other possible tables and/or graphs that we could create?

Other possible tables and/or graphs could've been to look at each trend line filtered by 
country based on goal and outcome. We could've looked at outcome by launch date pivot 
table by quarter (see pic below), instead of by month . We could have bar graphed the play outcomes by 
country location to see if that produced any significant insights.

![](https://github.com/KJRE54/ProjectPics/blob/main/OutcomesBasedOnLaunchDateQTRSPivotTbl.png)
