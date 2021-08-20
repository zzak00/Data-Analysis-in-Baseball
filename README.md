# Data-Analysis-in-Baseball
## Project Description

There's a new era of data analysis in baseball. Using a new technology called Statcast, Major League Baseball is now collecting the precise location and movements of its baseballs and players. In this project, you will use Statcast data to compare the home runs of two of baseball's brightest (and largest) stars, Aaron Judge (6'7") and Giancarlo Stanton (6'6"), both of whom now play for the New York Yankees.

<p>Statcast is a state-of-the-art tracking system that uses high-resolution cameras and radar equipment to measure the precise location and movement of baseballs and baseball players. Introduced in 2015 to all 30 major league ballparks, Statcast data is revolutionizing the game. Teams are engaging in an "arms race" of data analysis, hiring analysts left and right in an attempt to gain an edge over their competition. This <a href="https://www.youtube.com/watch?v=9rOKGKhQe8U">video</a> describing the system is incredible.</p>

<p><strong>In this notebook</strong>, we're going to wrangle, analyze, and visualize Statcast data to compare Mr. Judge and another (extremely large) teammate of his. Let's start by loading the data into our Notebook. There are two CSV files, <code>judge.csv</code> and <code>stanton.csv</code>, both of which contain Statcast data for 2015-2017. We'll use pandas DataFrames to store this data. Let's also load our data visualization libraries, matplotlib and seaborn.</p>
