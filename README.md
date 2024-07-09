*Name*:*CHARITHA CHOWDARY ENUKURTHI*
*Company:*CODTECH IT SOLUTIONS*
*ID:* CT04DA2294*
*Domain*:*Data Analyst*
*Duration*:*15 June to 15 July 2024*
*Mentor*:**SRAVANI GOUNI*

## Overview of the Project

### Project: Exploratory Data Analysis(EDA) on IPL Ball-by-Ball dataset

### Objective:
The objective of this project is to perform Exploratory Data Analysis(EDA) on a dataset containing about the IPL Ball-by-Ball data from 2008to 2024.The aim is to uncover insights on players trnd,distributions,correlations,and outliers through visualizations.

### Key activities,Technologies used and key insights are breifly below :

Imports necessary libraries:

pandas for data manipulation and analysis.
matplotlib.pyplot and seaborn for data visualization.
Loads the dataset:

Reads a CSV file named IPL_BallByBall2008_2024(Updated).csv into a pandas DataFrame called ipl_data.
Preprocesses the data:

Converts the 'Date' column to datetime format, handling any errors that occur during conversion.
Converts the 'Ball No' column to integer type, handling any errors that occur during conversion.
Fills missing values in the 'type of extras', 'wicket_type', 'Player Out', and 'fielders_involved' columns with 'none' or 'no wicket' as appropriate.
Sets up Seaborn style:

Configures Seaborn to use the 'whitegrid' style for the plots.
Creates visualizations:

Histogram of Runs Scored per Ball:

Plots a histogram with a kernel density estimate (KDE) for the 'runs_scored' column.
Customizes the plot with title, x-label, and y-label.
Bar Plot of Wicket Counts by Type:

Computes the count of different types of wickets from the 'wicket_type' column, excluding 'no wicket'.
Plots a bar plot showing the counts of different wicket types.
Customizes the plot with title, x-label, y-label, and rotates the x-axis labels for better readability.
Bar Plot of Top 10 Players Involved in Dismissals:

Computes the count of dismissals each player has been involved in from the 'fielders_involved' column, excluding 'none'.
Selects the top 10 players involved in dismissals.
Plots a bar plot showing the counts of dismissals for the top 10 players.
Customizes the plot with title, x-label, y-label, and rotates the x-axis labels for better readability.
Correlation Heatmap of Numerical Features:

Selects numerical features ('Innings No', 'Ball No', 'runs_scored', 'extras', 'score') from the DataFrame.
Computes the correlation matrix for these numerical features.
Plots a heatmap of the correlation matrix, with annotations and a color map for better visualization.
Customizes the plot with title and adjusts the appearance using Seaborn.
This sequence of code preprocesses the IPL dataset and generates various insightful visualizations to understand the distribution of runs, types of wickets, top fielders involved in dismissals, and the correlations between different numerical features.

### OUTPUT OF THE PROJECT

![Screenshot 2024-07-09 142739](https://github.com/Charitha-03/CODTECH-Task1/assets/156454784/a3e0a790-947a-4017-8e6c-e865931e72aa)
![Screenshot 2024-07-09 142757](https://github.com/Charitha-03/CODTECH-Task1/assets/156454784/993ae197-b255-41e4-8bb4-c812aa9b8a60)
![Screenshot 2024-07-09 142815](https://github.com/Charitha-03/CODTECH-Task1/assets/156454784/4add1cd5-6d7a-439e-9421-3c167a7d8dc6)
![Screenshot 2024-07-09 142834](https://github.com/Charitha-03/CODTECH-Task1/assets/156454784/03c257aa-8d92-46ee-a1f3-3a90aa9fc172)





