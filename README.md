# 🐼 Pandas DataFrame Basics - Part 2: Fuel Economy Analysis
This repository contains a Jupyter Notebook (Copy_of_02_PandasDataFramessofona_02.ipynb) designed to reinforce fundamental data manipulation and analysis skills using the Pandas library in Python. The notebook focuses on exploring a vehicle fuel economy dataset, demonstrating key DataFrame operations and providing practical exercises.

---
## 🎯 Learning Objectives
This notebook is structured as a practical guide to solidify understanding of:
- Helpful Jupyter features: Leveraging the interactive environment.
- Importing a CSV dataset: Loading external data into a Pandas DataFrame.
- Selecting multiple columns: Accessing specific subsets of data.
- Counting True values in a Boolean series: Performing conditional counts.
- Filtering rows with Boolean masks: Selecting data based on specific criteria.
- Using AND and OR operators: Combining multiple filtering conditions.
- Understanding .copy(): Best practices for creating independent DataFrame copies to avoid unintended mutations.
- Sorting a DataFrame: Ordering data by one or more columns.
- Calculating descriptive statistics: mean(), median(), sum(), value_counts().
- Identifying extreme values: Using nlargest() and nsmallest().
- Feature Engineering: Creating new columns based on existing data (e.g., average_mileage, miles_per_litre).
- Correlation Analysis: Understanding relationships between numerical columns using .corr().

### ⛽ Dataset: mpg.csv (Miles Per Gallon)
The dataset used in this notebook (mpg.csv) contains 234 observations about different car models and their characteristics, primarily focusing on fuel economy. This dataset is excellent for practicing data exploration, cleaning, aggregation, and basic feature engineering.

----
## ✍️ Exercises
The notebook includes several hands-on exercises to apply the learned Pandas concepts:
- Create is_automatic column: A Boolean column indicating if a vehicle has an automatic transmission.
- Count automatic vehicles: Sum the number of automatic vehicles using the is_automatic column.
- Calculate subcompact percentage: Determine the proportion of vehicles classified as "subcompacts."
- Create fuel_economy column: Calculate a weighted average fuel economy (55% city, 45% highway).
- Filter by fuel_economy: Find all vehicles with a fuel_economy above the median fuel_economy.

----
### 🛠️ Technologies Used
- Python: The core programming language.
- Pandas: The primary library for data manipulation and analysis.
- Jupyter Notebook / Google Colab: The interactive environment for running the code and presenting the analysis.
