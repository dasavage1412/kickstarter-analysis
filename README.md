# Analysis for Kickstarter Data
Preforming Kickstarter analysis to uncover trends
# Kickstarting with Excel

## Overview of Project

### Purpose
-This project was an analysis of a Kickstarter fund raising data set. The purpose of the project was to provide the client with a better understanding of what Kickstarter projects had worked in the past and which ones didn’t. This was accomplished through the organization and manipulation of the data set. Using these tools, we were able to glean critical insights into what parameters for a Kickstarter program have the best chances of working. For example, being able to see outcomes for theater-based Kickstarter, additionally being able to see what sub type of Kickstarter are the post popular/successful (plays for example)
 

## Analysis and Challenges
-Much of the analysis was done using variations of filtering, and pivot tables. Using pivot tables allowed the data to be cleaned up and for the most relevant data to be observed. (Parent outcome.PNG .) One of the additional analysis that was done was a simple breakdown percentage of successful campaigns by goal amount. 

### Analysis of Outcomes Based on Launch Date
-With this data set I think there will be a temptation to say that campaigns launched in May-August will have the highest chance of succeeding. My first conclusion is that April is the best month to launch a campaign because it has the greatest spread between the number of failures and successes. My second conclusion is that the rest of the year may have little effect on the outcome of a campaign. During the other months of the year successes and failures seem to mirror each other. If there was a significant effect due to time of the year the plots of the lines would be more divergent. With April into May being the only exception to this general rule.   
 
### Analysis of Outcomes Based on Goals
-From this data we can conclude that as the goal for a given project increases its chance at succeeding decreases. Also, as goal in creases the chances that the project is canceled completely grows to 25%. It is worth considering that if a project is going to be above 1000 that a soft cap is placed at 14999 for any given project. The Vast bulk of campaigns happen at less than 15K and one you hit that point it is a less that 50% chance to succeed. A more conservative approach would be to limit projects to no more than even 10K to have the best chance at success, (albeit using 50% as a benchmark is totally subjective.)

 
### Challenges and Difficulties Encountered
-One of the larger challenges that I ran into was getting the Year column into the Kickstarter data set. I was eventually able to use the =TEXT formula to convert the data correctly. Related to that issue was getting the Date conversion function to work for every cell. The function would stop applying approximately every 1000k cells I manually applied the drag function.

## Results (Conclusions to the two deliverables are in the analysis section respectively)
- One of the most distinct limitations to the data set is that there is no region identified by country. For example, the US is huge and there may be a direct correlation to success and failure by state. Given that states can also be huge there may be a correlation even on the county level. Given that there wouldn’t be a uniform way to apply that same region size to other countries the data may be better if localized on a country by country basis and broken into approximate regions for each. Additionally, there is no way to gauge the quality of individual campaigns. We may be able to guess that the ones with the most funding are high quality and had a large amount of work put into them, but that is not known. This could mean that certain subcategories have disproportionately lower or higher quality campaigns. Quality being the general amount of work that went into a campaign, page attractiveness, social media presence etc. 

###What are some other possible tables and/or graphs that we could create?
-One of the key graphs that I would include would be a comparison of the top campaigns by subcategory. This would show if there were any major differences between amount raised and the type of campaign. It is outside the scope of this project but I would provide examples of the those campaigns to the client for reference. 
