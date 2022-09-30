# An Analysis of Kickstarter Campaigns
## Previous analysis results of kickstarter campaigns

  ![Outcomes Based on Launch Date](https://user-images.githubusercontent.com/105877888/170364445-c3746e0e-0eb5-4323-97d4-e0494b56b240.png)
  ![Parent Category Outcomes](https://user-images.githubusercontent.com/105877888/170364470-fab4a9c3-95e7-45b5-b829-7549e8ed6340.png)
  ![Subcategory Outcomes](https://user-images.githubusercontent.com/105877888/170364493-35755532-6c99-4ea7-b300-d887a9333735.png)
  ![GB Musical Chart](https://user-images.githubusercontent.com/105877888/170364504-37814b2d-83a4-410c-a825-ca08a1bb5f23.PNG)


## Overview of the new project
### Purpose
**Take the outcomes of theater and plays as examples, to analyze how successful of Louise crowdfunding campaigns. According to the analyzed data, give out some recommendations to Louise.**

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/105877888/170613303-fd4a268e-82a7-456b-957d-9fdf818dda9c.png)

1. Creating a pivot table to pull out theater outcomes data accompanied with launch date. 
2. Drawing a line chart to show successful, failed, and canceled theater campaigns of launch month dependence. 

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/105877888/170626438-3d0576e7-f0d6-4ff2-854e-d44b4413dd32.png)


1. Caculating the percentages of successful, failed, and canceled campaignes based on crowdfunding goal amount.
2. Creating a line chart to visualize the outcomes of plays based on campaign goals. 

### Challenges and Difficulties Encountered

 *_```=COUNTIFS```function contains several criterion, which makes the formulas very long, Especially the referenced cells are from another worksheet. One need to be careful to confirm the cell name. ```Alt+Enter``` (to input in new line)also would help to make it easier to read._

 *_When selected column has huge number of rows and the whole column needs to be selected. Keyboard shortcut ```Ctrl+↓``` can help to scroll to the end of column. For short, we can use column name only instead. (e.g.```E2:E4115``` --> ```E:E```)_

 *_Right click is more convenient than looking for tools from the ribbons above if presence. e.g. changing the color of chart lines, formatting axis._

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  *Successful theater campaigns are more than failed theater campaigns in each month, especially during the middle of the year. 
   So theater is an efficient crwdfunding way. 
   
  *May is the best month to launch theater campaingns. 
  
- What can you conclude about the Outcomes based on Goals?
  
  *For plays, which campaign goals are lower than $20,000, are easy to get accomplished.
  
- What are some limitations of this dataset?
  
  *The cost of campaign is not included. Net goals and net pledged amount should be caculated by deducting the cost or budget.

- What are some other possible tables and/or graphs that we could create?
  
  *Comparison of total crowdfunding amounts in different countries by converting all currency to US dollar```$```.
  
  *Analysis of outcomes based on daily crowedfunding amount during the campaign.
