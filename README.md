# Unemployment_GA_FL_SC_TN
In this project, I used a combination of Python's data analysis and visualization libraries to fetch, process, and analyze monthly unemployment data at a state level. The main goal was to study unemployment rates for certain states and visualize the rates for March 2020, marking the start of COVID-19 pandemic.

The primary tools and libraries used in this project include:

  Python: Served as the base programming language for all data processing, analysis, and visualization tasks.
  pandas: This Python library was used extensively for data manipulation and analysis, specifically for structuring data into DataFrames, handling missing values, and reshaping data.
  NumPy: Utilized for performing numerical operations.
  Matplotlib: Used for generating a bar chart to visualize the unemployment rates.
  Plotly Express: Employed to create an interactive line chart that allows for a more comprehensive exploration of the data.
  fredapi: This library was crucial for fetching economic data directly from the Federal Reserve Bank of St. Louis's database, FRED.

The project started with fetching unemployment rate data from FRED, which was then filtered based on certain criteria (seasonal adjustments and unit type) and relevant fields were selected. The time-series data for each state was retrieved and stored into a list as individual pandas DataFrames. These were then concatenated to form a final DataFrame, which was cleaned by removing any rows with missing values.

The project focused on the unemployment rates of a subset of states (GA, FL, SC, and TN). A line chart was generated to visualize the trend of unemployment rates for these states.

Finally, a bar chart was created to display the unemployment rates for the selected states in March 2020, which was a significant period due to the beginning of the COVID-19 pandemic. The chart was designed without a legend for cleaner presentation.

This project showcases a strong proficiency in using Python for data analysis, from fetching and cleaning data to performing analysis and generating visualizations to interpret the results. It demonstrates a strong understanding of the Python data analysis ecosystem, including libraries like pandas, Matplotlib, Plotly, and fredapi.
