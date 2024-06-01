# IPL Data Analysis with Spark

This repository contains code snippets and queries written in Apache Spark for analyzing Indian Premier League (IPL) cricket data. The analysis covers various aspects of IPL matches, players, teams, and match outcomes. Below are some key highlights and functionalities of the code provided:

## Setting up Spark Session
- Creating a Spark session for IPL data analysis.

## Data Import
- Importing IPL data from AWS S3 storage.
- Customizing schemas for the imported data to ensure data accuracy and consistency.

## Data Cleaning and Transformation
- Cleaning the imported data by removing unnecessary columns and filtering out invalid deliveries.
- Analyzing dismissal types and extra runs in cricket matches.
- Aggregating runs scored in each match and over.
- Identifying high-impact deliveries based on runs scored and wickets taken.
- Extracting and normalizing player names, categorizing players based on batting hand, and calculating years since debut.

## Exploratory Data Analysis (EDA)
- Analyzing dismissal types and extra runs in cricket matches.
- Evaluating the impact of the toss on match outcomes.
- Identifying teams with the most match victories after winning the toss.
- Visualizing average runs scored by batsmen in winning matches.
- Exploring the performance of bowlers during powerplay overs.

## Visualization
- Visualizing data using Matplotlib and Seaborn for better insights and understanding.
- Creating bar plots, count plots, and other visualizations to represent analysis results effectively.

## Interpretation
- Providing insights and interpretations based on the analysis results, such as the strategic importance of winning the toss and its correlation with match victories for IPL teams.

This repository serves as a comprehensive resource for analyzing IPL data using Apache Spark, offering valuable insights into match dynamics, player performances, team strategies, and overall tournament outcomes.
