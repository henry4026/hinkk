# captstone project1: analysis turnover rate between different industry in different year period
## Goal
exploratory data on quarterly workfoce indicator, analyze the changes of turnover rate during and after the economy recession with different industry
## Data 
this data set provide local labor market statistics by industry worker demographics, age and firm size with 80 columns and 235000 row.
## EDA and daily work
1. understand and clean the dataset.
2. create pandas data frame with the dataset
3. create different graphic to show the turnover rate changes between different industry in different time frame by using dataframe.
4. find the problems for monthly average paid, job gain and lost, and turnover rate.
5. completed a EDA and the graph for the result.
6. from this dataset it shows that during economy recession, there impact on turnover rate, job opportunity and monthly average paid.
## hypothesis testing.
1. the different between two different industry turnover rate in the same year
   1. use Welch's T-test and U-test to find the p-value.
   2. base on the result from these tests, i have enough evidence to reject the null hypothesis. it shows that real estate industry turnover rate is higher than finance and insurance industry.
2. same industry turnover rate in two difference years.
   1. use Welch's T-test and U-test to find the p-value.
   2. base on the result from these tests, i have enough evidence to reject the null hypothesis. it shows that the finance industry in 2017 the turnover rate is higher than in 2009.
   3. the turnover rate is impacted by economy recession in 2009.
