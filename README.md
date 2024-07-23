**Set of real world data science tasks completed using the Python Pandas library.**

We use Python Pandas and Matplotlib to analyze and answer business questions about 12 months' worth of sales data. The dataset contains hundreds of thousands of electronics store purchases, broken down by month, product type, cost, purchase address, and more.

**Data Cleaning Tasks**

To begin our analysis, we start by cleaning the data. This involves the following tasks:

1.  Dropping NaN values from the DataFrame
2.  Removing rows based on specific conditions
3.  Changing column types using methods like 'to_numeric', 'to_datetime', and 'astype'

**Data Exploration**

After cleaning the data, we move on to the data exploration section. Here, we address five high-level business questions:

1. What was the best month of sales, and how much was earned that month?
2. Which city has highest number of sales?
3. What time should we display advertisements to maximize the probability of customer's buying product?
4. What products are most often sold together?
5. What product sold the most and why?


**Methods and Techniques**

To answer these questions, we utilize various pandas and matplotlib methods, including:

1. Concatenating multiple CSV files to create a new DataFrame (pd.concat)
2. Adding columns
3. Parsing cells as strings to create new columns using .str
4. Applying functions using the .apply() method
5. Using groupby to perform aggregate analysis
6. Plotting bar charts and line graphs to visualize our results
7. Labeling our graphs for clarity
