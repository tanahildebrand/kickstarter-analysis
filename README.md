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
I struggled to create a repeatable COUNTIFS formula to calculate the number of plays based on outcome and goal. I wanted a formula that could be copied and pasted to other rows based on the goal ranges. Instead of imbedding the ranges directly in a formula, I split the lower and upper range values into two spearate columns, each with a mathematical symbol to note what direction (greater than, less than, etc) the values needed to fall to be considered. This allowed me to be certain that my formula was correct and the ranges were entered correctly.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
