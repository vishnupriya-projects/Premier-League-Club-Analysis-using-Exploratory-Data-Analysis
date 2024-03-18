# Premier-League-Club-Analysis-using-Exploratory-Data-Analysis
Premier League Club Investment Analysis for an Investment company using Exploratory Data Analysis 
# Brief Introduction:
The data contains the information of a Premier League Clubs, where an  XYZ investment Company is looking for a best club for investment.
# Objective: 
The management of the firm XYZ aims to invest in one of the top-performing club in the English Premier League. To aid in their decision-making process, the analytics department has been tasked with creating a comprehensive report on the performance of various clubs. However, some of the more established clubs have already been owned by the competitors. As a result, the firm wishes to identify the clubs they can approach and potentially invest to ensure a successful and profitable deal.
# Data: 
Premier League Final Data.csv- : The data set contains information on all the teams so far participated in all the premier league tournaments.
# Data Columns:
Club: Name of the football club
Matches: Number of matches the club has played in the Premier League
Wins: Number of matches won by the club in the Premier League
Loss: Number of matches lost by the club in the Premier League
Draws: Number of matches drawn by the club in the Premier League
Clean Sheets: Number of matches in which the club has prevented the opposing side from scoring
Team Launch: Year in which the club was founded
Winners: Number of times the club has won the Premier League
Runners-up: Number of times the club has finished as runners-up in the Premier League
Lastplayed: Last played in premier league
# Data Cleaning and Preparation:
The following are the columns identified & need to fix for further analysis.
- The club name is mixed with row number, which need to clean club column.
- Runners-up column is not in numerical data type, need to change it for any numerical operations.
- Winners , runner-up columns have missing values, need to replace the values.
- In team-launch column, the year data is not in same format, need to change it.
- lastplayed_pl column is not in proper date format, need to fix it.
# Data Analysis and Insights: 
By using Exploratory Data Analysis, following are observations made which helps for further analysis.
- Majority of clubs played around 400 matches & few clubs played >1000 matches.
- Based on problem statement, few well played & experienced clubs are already taken by competitors, investor was looking for clubs having good performance clubs irrespective of their experience.
- To identify the clubs based on objective, we can consider the clubs who played less matches, i.e <800 for our further analysis.
- Other parameters also calculated such as win, loss, draws, goals, clean sheets and calculate % rate based on matches played by each club to deep down further on performance of clubs.
- If we find the names of club based on above analysis we can say that
    - In terms of experience: Leicester City
    - In terms of winners in Premier league: Leicester City
    - In terms of winning rate: Leeds United
    - In terms of drawn rate: Brighton & Hove Albion
- So to conclude best out of all, weights were given for each factor & calculated the score to get best performing club.
- Below was the weights given for each factor to get Score for each team on the per defined metric.
    - Give a score of 15 if club have a relatively high experience in the Premier League
    - Give a score of 10 if club have matches played above average (372)
    - Give a score of 15 if club has won premier league
    - Give a score of 15 if club has winning rate above Q3
    - Give a score of 10 if club has losing rate below Q1 and drawn rate above Q3
    - Give a score of 10 if club has clean sheet above Q3
    - Give a score of 10 if club has been a runners-up in premier league.
- Based on above score we can say that in terms of all scores 'Blackburn Rovers' was on top followed by 'Leicester City'.
- If we closely look the latest experience of both, Leicester City has recently played in 2023, were Blackburn Rovers was played in 2012 which is quiet long back.
- so that we recommend 'Leicester City's' is better choice for investment based on recent form and its performance.

