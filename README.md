# Lahmann-Baseball-Database
This is a group project I worked on with my classmates. This project uses pyspark ML and created a SparkSession object. The project was created in Databricks. The project is arranged into sections (Section A, B, etc.) and subsections.

## Project Objective
In this project, we will be working with the Lahman Baseball Database. This database in maintained by Sean Lahman and contains pitching, hitting, and fielding statistics for Major League Baseball from 1871 through 2020.

## Section A: Load and Prepare Data
The Lahman Database consists of 27 tables. The names of the data files contains these tables provided below. Each of these files in a comma-separated format and contains headers. For the first four sections of the project, we worked exclusively with the **People**, **Batting**, **Teams** and **TeamsFranchises** tables.

 <p align="center">
  <img src="https://user-images.githubusercontent.com/58959101/158272207-4ad0927c-46af-4447-b838-3cbe0f93b189.png" /p>
 </p>
 
 ## Section B: Teams and Franchises
A distinction is made between teams and franchises in MLB. A franchise is a collection of players, managers, and owners that change continuously and gradually over time, but are considered to be the same entity for the sake of record keeping. A franchise might consist of several "teams", with each "team" referring to a certain period in the franchise's history.
 
A franchise might undergo many changes during their history, such as changing their name, moving to a new city or chaning a league. Some of these changes will result in the franchise ending one team and starting another, but it will still be the same franchise.

In this section, we explored some historical statistics relating to franchises:

    - B.1 Number of Franchises by Year: Determine the number of MLB franchises that existed each year.
    
    - B.2 Franchise Statistics: Calculate a few statistics for each franchise that has ever existed.
    
    - B.3 Franchises with the Most Names: Determine the greatest number of names that have been used by any one franchise.
    
    - B.4 Age of Current Franchises: Determine the ages of the 30 current franchises.
    
    - B.5 Franchises with Best Win/Loss Ratios: Identify the 10 franchises who have the best win/loss ratios.
    
    - B.6 Win/Loss Ratios in Recent Years: Calculate the win/loss ratio for each of the current franchises during the period since 1998.
    
## Section C: Batter Statistics
In this section we calculate and explore certain career statistics for each player who has ever batted in an MLB game. Two statistics in particular that we will look at are **batting average** and **slugging percentage**.
    - A player's **batting average (BA)** is their number of hits divided by their number of at-bats.
    - A player's **slugging percentage (SP)** is the average number of bases they have advanced during each at-bat.

We can use the following formulas with the respective columns: H, 2B, 3B, HR, and AB.

 <p align="center">
  <img src="https://user-images.githubusercontent.com/58959101/158273340-7981258b-3dbb-49ab-ad4d-8c2d2a4a514b.png" /p>
 </p>

We explore the following:

    - C.1 Calculating Career Statistics: Calculate career statistics for each MLB batter.
    
    - C.2 Most Seasons Player: Identify the 10 batters who have played in the most seasons.
    
    - C.3 Most At-Bats: Identify the 10 batters who have had the greatest number of at-bats.
    
    - C.4 Highest Batting Average: Identify the 10 batters who have the highest batting averages.
    
    - C.5 Highest Slugging Percentage: Identify the 10 batters who have the slugging percentages.
    
    - C.6 Relationship between Batting Average and Slugging Percentage

## Section D: Trends over Time
In this section we explore how certain statistics have changed during the history of the MLB.

We explore the following:
    - D.1 Calculating Averages by Year: Calculate the average height and weight of players by year, as well as the overall batting averages and slugging percentages for all players by year.
    - D.2 Trends for Height and Weight
    - D.3 Trends for Batting Statistics
    - D.4 Trends for American and National Leagues
    - D.5 Average Number of Games: Determine the average number of games played by each team during each MLB season.
    
## Section E: Pitching Data
This section will explore the pitching data by starting off with looking at some all time career records, as well as looking deeper into performance statistics and doing some custom analysis of pitchers' performance all time and in recent years to determine interesting trends and useful data about modern pitching performance.

We explore the following:
    - E.1 Most Winning Pitchers: Examine the most winning pitcher of all time and produce a plot outlining some stats over his career.
    - E.2 Pitchers with Most Shutouts in a Single Year: Analyze pitching data by year and display the pitchers with most shutouts in a single season.
    - E.3 Pithcers Least Hits against Average: Investigate the batting average against data by finding the pitchers who faced at least 100 batters in the year 2020.
    - E.4 Pitchers with Best Batting: Which pitchers contributed the most on both sides of the game.
    - E.5 Pitchers Risk Score: Investigate how likely a pitcher will score.

## Section F: Qualification for the Hall of Fame
