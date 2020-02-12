# comparing-baltimore-boston-household-income-and-parent-income
Description: 
In Baltimore, Children with higher parent incomes tend to have higher household incomes when grown up. However, there is no significant correlation between household incomes and parent incomes. Hence, Boston has better social mobility than Baltimore.
![](https://github.com/Jason112Fu/comparing-baltimore-boston-household-income-and-parent-income/blob/master/Baltimore.png) ![](https://github.com/Jason112Fu/comparing-baltimore-boston-household-income-and-parent-income/blob/master/Boston.png)
https://www.opportunityatlas.org/
https://github.com/Jason112Fu/comparing-baltimore-boston-household-income-and-parent-income/blob/master/Baltimore_Boston.xlsx

Method:
.cvs files are raw data of household incomes of children with 25th, 50th, 75th percentile parent incomes seperately, and (1) are from Baltimore and (2) are from Boston. First I gave each household income data a mark of its percentile parent income. Then merged three tables into one. After that, I creat a Pivot table with row: household income, colomn: percentile parent income and value: count number of percentile parent income. Thus, by filter household income, I can know how many people with <33% household income are from each parent income groups. Same as 33%-67% and >67%. 
