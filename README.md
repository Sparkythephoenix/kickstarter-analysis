# kickstarter-analysis


Overview of Project
Purpose
This analysis is organized based on Kickstarter worksheet. The main goal of this analysis is to show Louise the outcome of different campaigns in relation to their launch dates and their funding goals.

Analysis and Challenges
Analysis of Outcomes Based on Launch Date
The analysis was conducted by creating a pivot table from the Kickstarter worksheet. Then the table was filtered by "Parent Category" and "Years". Columns, raws and values were filled out with pivot table fields. After this step "theatre" filter was applied to "Parent Category" and "live" was unchecked in column labels. After that, campaign outcomes were sorted in descending order. As the last step, this graph was created.

Analysis of Outcomes Based on Goals
For this analysis the new Table was created with the list of new columns and rows which contain preset "goal" amount ranges. To calculate the number of successful, failed and cancelled plays the COUNTIFS() formula was used with several conditions, as filtering on the Kickstarter "outcome" column, on the "goal" amount column using the "goal" amount ranges, and on the "Subcategory" column using "plays" as the criteria. Then the respective percentage was calculated from total amount of plays in every amount range. As the last step, this graph was created.

Challenges and Difficulties Encountered
During the first analysis there were no real challenges, however, it is possible that some people may place the pivot table fields not in right raws, columns and values. This may result in wrong data visualisation. For the second analysis the challenge was to find extra information on using COUNTIFS() formula for several conditions in Excel documentation. As a result, the documentation was checked and the correct syntax applied.

Results
What are two conclusions you can draw about the Outcomes based on Launch Date?
The best time to start the new play for Louise is April, because it is followed by three months of successful kickstarter projects.
2)The number of succful projects for plays decreases constantly from May till December, so after May it is not a good time to start the play.

What can you conclude about the Outcomes based on Goals? 1)According to analysis result, plays with the goal ammount of $1000 to $4999 have 73% success rate, which is second highest rate. Therefore Louise has good chances to succeed because her startup fundraising goal is $4000.
2)the trend shows that the more expensive the play is, the more chances it has to fail.November and December being the least successful time to start the project.

3)The exception from the trend is 6 plays in $35000-44999 range. This must be a special plays projects with expensive actors or director, because they all have 67% success rate.

What are some limitations of this dataset? One of the possible limitations in this analysis is that 3/4 of all data is from US, so basically we mostly analyse the situation in US rather than in the world. More data from other countries may allow us to compare different trends and draw conclusions.
The second limitation is lack of information why kickstarter projects were successful. In real Kickstarter people can add description, videos, pictures, etc. that can effect backer's choice.

What are some other possible tables and/or graphs that we could create?
we could create the graph of world distribution of succesful or failed startups.
