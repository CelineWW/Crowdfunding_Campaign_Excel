# Kickstarting with Excel

## Overview of Project
### Purpose
**Take the outcomes of theater and plays projects as examples, to see how successful of Louise crowdfunding campaigns. According to the analyzed data, give out some recommendations to Louise.**

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/105877888/170613303-fd4a268e-82a7-456b-957d-9fdf818dda9c.png)

1. Creat a pivot table to pull out theater outcomes data by launch date. 
2. Draw a line chart to show successful, failed, and canceled theater projects by the month. 

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/105877888/170626438-3d0576e7-f0d6-4ff2-854e-d44b4413dd32.png)


1. Caculate the percentages of the number of successful, failed, and canceled projects based on funding goal amount.
2. Creat a line chart to visualize the plays project outcomes based on goal. 

### Challenges and Difficulties Encountered

 *_```=COUNTIFS```function contains several criterion, which makes the formulas very long, Especially the referenced cells are from another worksheet. One need to be careful to confirm the cell name. ```Alt+Enter``` also would help to make it easier to read._

 *_When selected column has huge number of rows and the whole column should be selected. Keyboard shortcut ```Ctrl+↓```might help. Sometimes, it doesn't work. For short, we can use column name onlyinstead. (e.g.```E2:E4115``` --> ```E:E```)_

 *_Right click always more convenient than looking up from the ribbons above. e.g. changing the color of chart lines, formatting axis._

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  *Successful theater campaigns are more than failed theater campaigns in each month, especially during the middle of the year. 
   So theater is an efficient crwdfunding method. 
  *May is the best month to launch theater campaingns. 
  
- What can you conclude about the Outcomes based on Goals?
  
  *For those campaigns of plays, which goals lower than $20,000 are easy to get accomplished.
  
- What are some limitations of this dataset?
  
  *The cost of each campaign is not included. Net pledged amount should be deducted by the cost or budget.

- What are some other possible tables and/or graphs that we could create?
  
  *Comparison of total outcomes in different country by convert all currency to US dollar```$```.
  
  *Analysis of outcomes based on daily crowedfunding during the campaigns.
