# Kickstarting with Excel

## Overview
- Create graphs to show overall outcomes based on goals and outcomes based on launch date.
- Take the outcomes of theater and plays as examples, to analyze how successful of Louise crowdfunding campaigns. According to the analyzed data, give out some recommendations to Louise.

## Result
### Basic analysis results
- Line Chart of Outcomes Based on Launch Date

  ![Outcomes Based on Launch Date](https://user-images.githubusercontent.com/105877888/170364445-c3746e0e-0eb5-4323-97d4-e0494b56b240.png)
- Stacking Bar Chart of Parent Category Outcomes

  ![Parent Category Outcomes](https://user-images.githubusercontent.com/105877888/170364470-fab4a9c3-95e7-45b5-b829-7549e8ed6340.png)
- Stacking Bar Chart of Subcategory Outcomes

  ![Subcategory Outcomes](https://user-images.githubusercontent.com/105877888/170364493-35755532-6c99-4ea7-b300-d887a9333735.png)
  
- Measures of Spread - Descriptive Statistics

 <img width="1513" alt="Measures of Spread" src="https://user-images.githubusercontent.com/105877888/208597569-fe1315c8-04b4-4954-a53e-9702ca2f1a14.png">

- Box and Whisker Plot of musical outcome distribution in Great Britain

  ![GB Musical Chart](https://user-images.githubusercontent.com/105877888/170364504-37814b2d-83a4-410c-a825-ca08a1bb5f23.PNG)

### Advanced analysis results
- Analysis of Outcomes Based on Launch Date

  1. Creating a pivot table to pull out theater outcomes data accompanied with launch date. 
  2. Drawing a line chart to show successful, failed, and canceled theater campaigns of launch month dependence. 

  <img width="1182" alt="Pivot table" src="https://user-images.githubusercontent.com/105877888/208598222-9a5db05e-537e-4634-b6d4-ff064158573e.png">

- Analysis of Outcomes Based on Goals

  1. Caculating the percentages of successful, failed, and canceled campaignes based on crowdfunding goal amount.
  2. Creating a line chart to visualize the outcomes of plays based on campaign goals. 

  ![Outcomes Based on Launch Date with table](https://user-images.githubusercontent.com/105877888/208598065-4da91047-d0ac-4740-a1c8-c6aae0e9c4c4.png)


## Challenges and Difficulties Encountered

 *_```=COUNTIFS```function contains several criterion, which makes the formulas very long, Especially the referenced cells are from another worksheet. One need to be careful to confirm the cell name. ```Alt+Enter``` (to input in new line)also would help to make it easier to read._

 *_When selected column has huge number of rows and the whole column needs to be selected. Keyboard shortcut ```Ctrl+↓``` can help to scroll to the end of column. For short, we can use column name only instead. (e.g.```E2:E4115``` --> ```E:E```)_

 *_Right click is more convenient than looking for tools from the ribbons above if presence. e.g. changing the color of chart lines, formatting axis._

## Summary and Potential Questions 

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
