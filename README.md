# The Space Jam Project

Welcome to The Space Jam Project, where we're on a mission to save Earth from an invasion by superhuman aliens using the power of basketball!

## Introduction

In this fantastic scenario, Earth is under threat from a new species of superhuman aliens, and our only chance of survival is to defeat their basketball team in a crucial match. To achieve this, we need to assemble the best basketball team possible.

## Objectives

Our goal is straightforward: draft the best basketball team to save humanity. To do this, we'll use data from the NBA API, using Python and advanced statistical analysis to find the best players. Our drafting process focuses on five main areas:

1. **Wins**: We'll prioritise players who help their team win games by looking at a mix of wins, win percentage, and usage percentage, showing how much they contribute to their team's success.

2. **Offensive Skills**: We'll assess players' ability to score and create opportunities for their teammates, considering factors like shooting accuracy, assists, and offensive rating. We'll also factor in effective field goal percentage and penalise turnovers to ensure a well-rounded offensive strategy.

3. **Defensive Skills**: Defence wins games, so we'll analyse players' ability to steal the ball, block shots, and grab rebounds. We'll also look at their hustle on the court to see how hard they work defensively.

4. **Efficiency**: We are going to calculate the TS% (True Shooting Percentage) and the Usage Percentage to showcase the ability of a player to do the most when they have the basketball in their hands.

5. **Impact**: We are going to calculate the PER (Player Efficiency Rating) using an adjusted formula to show how valuable a player is to their team.

With these factors in mind, we'll draft a starting line-up and bench players based on their positions and performance metrics. 

Additionally, we'll select two wildcard players—one focused on clutch performance and the other on defensive skills and physical attributes—to add versatility and resilience to our team.

Join us in The Space Jam Project as we build the ultimate basketball team to defend Earth and ensure the future of humanity through the game we love!

# Data Analysis Process for The Space Jam Project

In this chapter, we will outline our data analysis process for selecting the best basketball players to save humanity in The Space Jam Project. We will leverage the NBA API's endpoints, specifically `leaguedashplayerstats` and `playerestimatedmetrics`, to gather data for the first five parameters.

## Drafting Process

1. **Wins, Offensive Skills, Defensive Skills, Efficiency, and Impact**:
   - Utilize the NBA API's `leaguedashplayerstats` and `playerestimatedmetrics` endpoints to gather relevant player statistics.
   - Calculate and assess performance metrics for each player in the areas of wins, offensive skills, defensive skills, efficiency, and impact.
   - Store the data in CSV files for further analysis.

2. **Clutch Performance**:
   - Focus on statistics recorded in the last 10 seconds of the shot clock to determine clutch performance.
   - Extract relevant data from the NBA API and store it in a CSV file.

3. **Defensive Specialist**:
   - Utilize the NBA API's `LeagueHustleStatsPlayer` endpoint to identify defensive stats.
   - Select and aggregate the best defensive statistics to create a defensive specialist parameter.
   - Store the data in a CSV file for further analysis.

## Power BI Analysis

1. **Data Cleaning and Modeling**:
   - Import the CSV files into Power BI.
   - Perform data cleaning and modeling to prepare the data for analysis.
   - Create an Entity-Relationship Diagram (ERD) to visualize the relationships between tables.

2. **Calculation and Visualization**:
   - Perform additional calculations as needed based on the drafted parameters.
   - Select and filter the data to keep only the necessary information for visualizations.
   - Add extra data such as player headshots, PNGs, logos, nicknames, and descriptions.

3. **Visualization Techniques**:
   - Utilize radar charts to visually display player statistics in a visually pleasing manner.
   - Adjust all statistics for consistency and clarity in the radar chart.

4. **Dashboard Creation**:
   - Create three dashboards in Power BI:
     - One for starters.
     - One for bench players.
     - One for the wildcards.
   - Focus on aesthetics to ensure the dashboards are visually appealing.

## Conclusion

Thank you for joining us in The Space Jam Project! We hope you enjoyed our data analysis process and the creation of the ultimate basketball team to defend Earth. Please let us know if you liked it by pushing the heart button. All the photos used belong to the NBA.
