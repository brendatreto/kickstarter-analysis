# Kickstarting with Excel
## Overview of project
### Purpose
Louise, an aspiring playwright, wants help planning a successful crowdfunding campaign. Analyzing this data will help her identify factors that could make her campaign a success and avoid any possible mistakes. In this project we will help Louise determine the role that factors such as the type of project, launch date, goal, and length, play in the outcome. The given data encompasses important information, but without the proper analysis it has little to no use.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
For the first part of the analysis, we tried to find the relationship between the launch date and the outcome of the campaign. To do this, we did the following:
1. Created a column to get a better visualization of the year the campaign was launched.
2. Created a pivot table to filter by category and year and see the way it relates to the outcome of the campaign. By doing this, we extracted the data we were interested in and saw how it correlated.
3. We filtered the information by choosing the theater category and sorting the outcome in descending order.
![Launch date_pivot](https://user-images.githubusercontent.com/22451540/146825776-bf909803-77c7-44b4-9bf5-19aac741356a.PNG)
4. To continue the analysis, we made a chart to visualize the relationship between outcome and the month the campaign was launched.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/22451540/146819041-0254eb5c-f812-466d-b2c5-92952842a64a.png)
5. This line chart was helpful to discover trends based on months. Have we used a different chart (pie or bar) we would not have been able to discern pattern in the behavior of campaigns over the year.
After this process was completed, we found out that:
* Campaigns launched in May have higher success rates than those launched in December.
* Campaigns launched in October have a high tendency of failure.
* We can observe that although successful campaigns have higher rates, failed campaigns follow a similar trend with peaks in the months of February, May, and October and decreases in the months of March, September, and December. Further research needs to be done to fully understand the causes of this behavior.
### Analysis of Outcomes Based on Goals
To continue with the process, we organized the information to be displayed based on goals and its relationship with successful and failed campaigns. By doing this, we tried to visualize whether the goal set was a factor in the outcome. The information was organized as follows:
![Outcomes Based on Goal](https://user-images.githubusercontent.com/22451540/147399418-431d12f4-b7bc-441c-b5c3-d0e17ce15b28.PNG)

We started by setting ranges to analyze the goal. These ranges varied from less than 1000 to more than 50,000 US dollars. We continued the process using the *countif* function to calculate the number of successful campaigns that met the criteria of goal amount and subcategory of plays. We adjusted the formula in the different rows to match the range and in the different columns to match the outcome of the campaign. Then, we quantified the percentage of this outcomes in relation to the total of campaigns that shared a goal. This gave us a chart with clean data and specific information. 
The next step was to select a chart to display this new information. 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/22451540/147399516-d47e2225-e2e4-43a9-a134-f8aaea91ebd5.png)

A line chart was used because we wanted to see how the percentage of outcomes varied along the different ranges set. Because we used percentages, and there were zero canceled projects, these results mirrored each other. However, we can still appreciate that there are certain goals set where campaigns have higher chance to be successful and that is, when the amount is less than 1,000 or from 35,000 to 44,999. And we can also see that the higher the among the greater is the chance of failure. 
### Challenges and Difficulties Encountered
The biggest challenge I encountered was in managing such a big set of information. I am aware that this is small in comparison to what I will be able to do in a few months, nevertheless, it was an adjustment. The easiest way to overcome this challenge was to break down the information and follow step by step the directions to get to the expected result. Once I finished with the suggested activities, I created a copy of the file to play with the data and try to understand the different ways in which it could have been analyzed.
## Results
**What are two conclusions you can draw about the Outcomes based on Launch Date?**
1. Most successful campaigns seem to happen around the months of summer.
2. Overall, theater campaigns tend to be successful

**What can you conclude about the Outcomes based on Goals?**

Greater goals should be avoided because they have grater chances of resulting in failure. It is easier to get successful results with smaller goals, but we need to take into consideration if these amounts are enough for the desired project. 

**What are some limitations of this dataset?** 

Although the blurb of the project is important to understand the nature of the campaign it could have been useful to categorize  this information and use it in a quantitative manner to see if it had any relation with the outcome.

**What are some other possible tables and/or graphs that we could create?**
- It would have been interesting to match the outcomes with launch date and goal, to find a relationship between this to variables.
- Perhaps it would have been wise to analyze the outcomes based on launch date using percentages as well. This could help us analyze the number of campaigns that were launched each month using the same baseline.
