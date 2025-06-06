# Aviation Accident Lab

This project is for the final lab about aviation accidents. The goal was to clean and analyze data from airplane accidents from 1983 to 2023. We want to find out which airplane makes and models are more safe — with lower serious/fatal injury and destruction rates.

## Files

- `Aviation_Accident_Cleaning.ipynb`: Notebook for Part 1. I cleaned the data here, removed bad columns, fixed types, and created new useful columns like injury rate and destruction rate.
- `Aviation_Accident_Analysis.ipynb`: Notebook for Part 2. I made the analysis here — summary statistics, graphs, and final recommendations for safer airplane types.
- `cleaned_aviation_data.csv`: The cleaned version of the dataset after Part 1.

## What I Did

###  Part 1: Data Cleaning
- I filtered the data to keep only airplane accidents after 1983.
- I removed helicopters and amateur-built planes (client not interested).
- I created new columns for:
  - Injury Rate = serious/fatal injuries ÷ total estimated passengers
  - Destruction = Yes/No based on aircraft damage
- Removed columns with too many missing values (less than 20,000 non-nulls).
- Cleaned and simplified plane `Make` and `Model`.

###  Part 2: Analysis
- I found the top 15 airplane **makes** with lowest average injury rate.
- I plotted violinplots and barplots to compare injury and destruction rate.
- I made **separate analysis** for small vs large aircraft.
- I also checked other variables like `Weather Condition` and `Purpose of Flight` to see how they affect injuries and damage.

## Key Insights

- Some small airplane makes (like Piper and Beech) have low injury rates.
- Large airplanes from McDonnell Douglas and Boeing had better safety profiles.
- Flights in bad weather and personal/private use planes had more serious outcomes.

## Conclusion

I recommend airplane makes that had **low destruction and injury rates**, and also highlight two key factors: **weather condition** and **flight purpose**, that affect safety a lot.

