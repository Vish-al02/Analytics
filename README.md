### UFC Fighters Analysis

## Overview
This project analyzes UFC fighter statistics to explore relationships between fighting styles, stances, weight classes, win percentages, and career length. The goal is to uncover insights into which styles are more successful and how weight class impacts fighter performance.

## Dataset
- **Source:** [Kaggle - UFC Fighters Statistics Dataset](#)  
- **Description:** Contains various metrics for UFC fighters such as wins, losses, strike accuracy, weight, takedown accuracy etc.
- **Preprocessing:** The dataset was cleaned by removing missing values, irrelevant columns (e.g., Nickname), and deriving new columns such as win percentage, total fights, and weight classifications.


## Objective
- **Weight Classification:** Categorize fighters into standard UFC divisions (Flyweight, Bantamweight, Featherweight, Lightweight, Welterweight, Middleweight, Light Heavyweight, Heavyweight) based on their weight.
- **Fighting Style Classification:** Classify fighters as **Striker**, **Grappler**, or **Mixed Style** based on performance metrics.
- **Performance Analysis:** Compare win percentages, career lengths, and style distributions across weight classes.
- **Insight Generation:** Determine which fighting style and weight class combinations correlate with higher success.

## Methodology
1. **Data Cleaning:**
   - Dropped irrelevant row (nickname) and rows with missing values.
2. **Feature Engineering:**
   - **Win Metrics:** Calculated win percentage based on relevant metrics(striking accurary, takedown defence) and total fights for each fighter.
   - **Fighting Style Classification:** Applied logic based on average striking and grappling metrics to classify fighters as Strikers, Grapplers and Mixed Style Fighters.
   - **Weight Classification:** Created a column assigning fighters to weight classes based on their weight in kg.
     

3. **Exploratory Data Analytics (EDA):**
   - **Fighting Style Distribution:** Certain weight classes show a dominance of a specific fighting style, with variations across divisions.
   - **Win Percentage:** Strikers generally have a higher win percentage compared to Grapplers and Mixed Style fighters and fighters with good defence have an advantage in total wins
   - **Career Longetivity:** Although career lenght varies accross sytles, there is little correlation between career longetivity and win percentage.
   - **Overall Insight:** The effectiveness of a fighting style seems to depend on the weight class, suggesting that specialized strategies may be more effective in specific divisions.

## How to Run the Project
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/UFC_Fighters_Analysis.git

 
