# //Kickstarter
## Overview of Project
The purpose of this analysis was to find key trends and patterns in a dataset containing theatrical productions, status, funding progress, as well as other identifying information. 
## Analysis and Challenges
Through these exercises, we analyzed the data by launch date and funding targets. 
When looking at the data by launch date, we focused on plays that were of the parent category “Theater” and all years that were available in our dataset. These values were mapped over the course of the year to identify patterns. 

![Date](https://github.com/ozzirk/kickstarter/blob/main/1-Theater%20Outcomes%20by%20Launch%20Date.png?raw=true)

The second analysis preformed was focused on the funding goal, and the later success, failure, or cancellation of that production. They were divided up into buckets and counted rates of success in each. 

![OutcomesonGoal](https://github.com/ozzirk/kickstarter/blob/main/1-Outcomes_vs_Goals.png?raw=true)

Some challenges that were faced along the way had to do with ensuring buckets were correct for the outcomes based on goals analysis. With no formatting of the numbers, it is easy to mistype a value and that could potentially skew the entire analysis. To work around this, I added two more columns to the table that acted as helper columns to ensure no numbers were missed. These informed the buckets, and were also concatenated to the group titles. 

![Challenge](https://github.com/ozzirk/kickstarter/blob/main/Challenge.png?raw=true)

## Results
_Theater Outcomes by Launch Date_
Looking at the Theater Outcomes by Launch date, we learned that May is the most successful month to launch, and October sees an uptick in failed outcomes relative to the rest of the dataset. Overall, there is a bit of seasonality to the data as it seems to follow a pattern throughout the year.  

_Outcomes based on Goals_
When looking at outcomes based on goals, it was clear that project success and failure is not linear with goal budget. Rather, certain price points have a better chance for success than others. From $0-$14,999, and from $35,000 to $44,999 have higher chances for success. $15,000-$19,000 is a 50/50 split between success or failure, and the rest of the budgets are more likely to fail.

_Limitations of the data_
Limitations of the dataset that were considered were lack of any campaign methodology metrics. Perhaps an underlying method of advertising the production could show another layer as to why certain ones were successful. It would be helpful to add additional tables that incorporate information about how the project was advertised. 

_Opportunities for additional analysis_
It would be interesting to examine the relationship between the number of backers and success. Are these projects gaining traction by the help of a few generous donors like friends and family? Or were the successful ventures those that captured a public audience early on, and were able to garner support from many people.

