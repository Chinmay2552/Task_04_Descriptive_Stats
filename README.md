# Task_04_Descriptive_Stats
Project Overview

This project explores different ways of summarizing and analyzing a real-world dataset — specifically, Facebook posts related to the 2024 U.S. presidential election. The main goal was to calculate basic descriptive statistics using three different methods in Python:

1. **Pure Python** (no external libraries)
2. **Pandas**
3. **Polars**

Each script analyzes the dataset to find things like:
- Count, average, minimum, maximum, and standard deviation (for numbers)
- Number of unique values and the most common values (for text/categorical data)

pure_python_stats.py – This script uses only built-in Python modules like csv and math to analyze the dataset without relying on any third-party libraries.

pandas_stats.py – This version uses the Pandas library to perform the same analysis in a much more efficient and readable way.

polars_stats.py – This script uses Polars, a high-performance DataFrame library, as an alternative to Pandas for fast and scalable data analysis.

1. Upload the dataset: `2024_fb_posts_president_scored_anon.csv`
2. Place it in the same folder as the scripts.
3. Run the scripts:

python pure_python_stats.py
python pandas_stats.py
python polars_stats.py
