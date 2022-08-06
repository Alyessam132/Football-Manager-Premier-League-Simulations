# Football-Manager-Premier-League-Simulations
20 Football Manager Simulations of Premier League 2021-2022 in Power BI dashboard that includes Team and Players Details.

Football Manager is a game that is known for using the data to predict the future of clubs and players, So I used Football Manager 2021 to predict the Premier league 2021-2022 and Comparing it to the Actual Results.

This Project is inspired by the dashboards made in this video https://www.youtube.com/watch?v=1wLU4z3FEuA&list=LL .

The Steps used to build the dashboard:
1.Data Sources
- Make 20 Football Manager Simulation of the Premier League and extracting.
  - 1 HTML Premier League Table Per Simulation. 
  - 20 HTML Player details Tables (One for Each Club) Per Simulation.
- Wikipedia ( Actual 2021-2022 Premier League Tables).
- Premier League Website ( Pictures of the 20 Clubs).
- 
2. Data Modeling: Galaxy Schema is used to implement the Data Model as there are two Fact tables (FactClub and Fact Player).


The Assumptions used in the dashboard is:
1. The Players Used in the dashboard are the Players that The Team enter the league at the end of the 2021-2022 summer transfer window.
(i.e Newcastle Takeover and Winter Transfers will not be taken into account in the simulation)


The Data Model Schema Used is Galaxy Schema

The Dashboard includes Five Pages:
1. Team Overview: (Final Table and No of League Titles, Europe Qualifications and Relegations for Each team)
2. Team Detailed: (Detailed info for each club with simulated and actual data and performance of their best players at different categories)
3. Player Overview: (Top 10 Average Rating Players and Top Player at important Categories in Football like Goals, Assists, etc...)
4. Player Detailed (Goals): (Detailed Data about Players Goals and Expected Goals (xG) and Share of Team Goals)
5. Player Detailed (Assists):  (Detailed Data about Players Assists and Key Passes (xG) and Share of Team Assists)
