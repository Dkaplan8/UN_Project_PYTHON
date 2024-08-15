A Guided Exploration of UN Data: Gross Domestic Product and Internet Usage:

This project involves analyzing two datasets provided by the United Nations: Gross Domestic Product (GDP) per capita and the percentage of individuals using the Internet. The aim is to explore and visualize the relationship between economic indicators and internet usage across various countries over time. The analysis is conducted using Python, primarily leveraging pandas for data manipulation and seaborn/matplotlib for visualization.

Project Structure

Data Folder: The project begins by setting up a data folder to store the two CSV files:

gdp_percapita.csv
internet_use.csv 

A Jupyter Notebook is used to perform the analysis, with sections divided by markdown cells to document findings and observations.

Data Preparation and Cleaning:

Loading Data:

The datasets are read into pandas DataFrames (gdp_df and internet_df), and initial exploration is conducted to understand the structure and contents.

Data Cleaning: 

Unnecessary columns are removed, and columns are renamed for clarity. The datasets are then examined for missing data and consistency.

Data Analysis and Visualization:

GDP Analysis: 

The GDP dataset is analyzed to identify trends over time, distributions in specific years, and comparisons between countries. Various plots (histograms, boxplots, scatterplots, etc.) are created to visualize GDP per capita for selected years (1990, 2000, 2010, and 2020). Special attention is given to countries with exceptionally high or low GDP values.

Internet Usage Analysis: 

The internet usage dataset is similarly explored to identify trends in global internet adoption. The percentage of internet users is compared across countries and years, with specific focus on the year 2014.

Combined Analysis: 

The GDP and internet usage datasets are merged to investigate the correlation between economic prosperity and internet penetration. The merged data is used to identify outliers and generate insights into the relationship between GDP per capita and internet usage percentage.

Advanced FacetGrid Visualization: 

For countries with the highest internet usage in 2014, the project includes a FacetGrid analysis to compare GDP trends over time.

Conclusion:

The project concludes with a comprehensive analysis of the data, highlighting key findings and providing visual evidence to support the exploration of the relationship between GDP and internet usage. The use of Python's data analysis and visualization libraries allows for deep insights into the global economic and technological landscape.

Project Maintainer: Douglas Kaplan
Contact Information: Douglasjkaplan@gmail.com
Date: 8/12/24
