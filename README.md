# Kickstarting with Excel

## Overview of Project
Louise is funding her new play, _Fever_, through a Kickstarter crowdfunding campaign with a goal of $10,000. She has access to Kickstarter data for other campaigns and had an analysis completed to determine when she should launch and if her goal is achievable. 
### Purpose
After launch, she raised close to her goal in a short time frame. She wants to know the results of other campaigns based on when they launched and their funding goal. She wants to focus the results on theater productions and a subset of those that matches hers campaign, theatre-plays.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Theater Outcomes vs Launch](/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
![Outcomes bs Goals](/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
I struggled to create a repeatable COUNTIFS formula to calculate the number of plays based on outcome and goal. I wanted a formula that could be copied and pasted to other rows based on the goal ranges. Instead of imbedding the ranges directly in a formula, I split the lower and upper range values into two separate columns, each with a mathematical symbol to note what direction (greater than, less than, etc) the values needed to fall to be considered. This allowed me to be certain that my formula was correct and the ranges were entered correctly.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
May is the most common month for Theater campaigns to launch.

Theatre campaign success rate outweighs failed and canceled rate.

- What can you conclude about the Outcomes based on Goals?
Play campaigns do not get canceled, as there are 0% cancelations across the board.

- What are some limitations of this dataset?
The dataset does not contain any information related to the content of the campaign itself. For example, was there a video included in the campaign? Or just an image? If we were provided details on what marketing materials were present, we would have been able to see how this factors into a campaign's success rate.

We do not have any further breakdown of the genre of play being proposed by Louise or historically. The genre - comedy, historical, tragedy, etc. - would have allowed us to further see sucess rates of plays based on that categorization.

- What are some other possible tables and/or graphs that we could create?
I would have changed the chart type for Theater Outcomes vs Launch to a 100% stacked column and limited the results to only plays. Since we know that Louise's campaign is a play, it would be prudent to see the results for other like campaigns. This is also helpful because we know that the other two theater subcategories, musicals and spaces are not as successful as plays. The 100% stacked bar graph would allow me to see what percentage of plays were successful based on the launch month, regardless of how many were launch. Using % instead of real numbers allows for more appropriate trending. For example, the line graph makes it look like May is the most successful month for launching a play campaign. With the 100% stacked, June is actually more successful with ~70% success compared dto ~68% in May. Overall, all plays have a success rate between 60-70% regardless of when they are launched, with the exception of December which is only ~48% successful.

I would also have wanted to see the success rate of plays by launch year instead of launch month. This would have allowed me to see if play campaign success was trending positively or negatively. 
