# Python Data Wrangling with Pandas

Week 3 assignment (Skill Nexis Data Analyst Internship).

This project cleans a messy fitness dataset (`data.csv`) using Pandas.

## What it does
- Fixes the date column (removes quotes, handles mixed formats, drops the row with no date)
- Removes duplicate rows
- Corrects wrong values (Duration typo of 450, swapped Pulse and Maxpulse)
- Fills missing Calories with the column mean
- Filters rows (Calories > 300)
- Adds new columns: Calories_per_min, Pulse_range, Weekday, Intensity
- Plots Calories vs Duration with Seaborn

## Files
- `Week3_Python_Data_Wrangling.ipynb`: the notebook
- `data.csv`: the raw data
- `cleaned_data.csv`: the cleaned output

## Tools
Python, Pandas, Matplotlib, Seaborn (Google Colab)
