# DATS6103 - Data Mining: Individual Project 2
*Data Mining Cocktail Recipes*

*Evan Carraway*

*April 9, 2019*

![Bottles](/Bottles.JPG)

Objective: The purpose of this project is to continue learning and improving skills in data mining and extracting information from raw data using Python by analyzing cocktail recipes on the Internet.

Due Date: April 9, 2019 by 4:30 PM

## Tasks
1. Scrape 2,000 cocktail recipes from the Internet
2. Identify and rank cocktail characteristics by overall popularity
3. Trend cocktail popularity over time by ingredient

## Subtasks
1. Create an effective presentation describing your data set of choice
2. Present the topic and the rationale on why you are picking that topic
3. Topic and its data MUST be complex and not at all obvious
4. The topic will be checked for plagiarism
5. State where the data came from
6. State your data cleaning and preprocessing
7. Your code needs to be working and be well commented
8. Your analysis needs to be clear, organized, and in depth
9. Indicate any classifications, clusters, associations/correlations, etc.
10. Discuss your predictions you might have and your reasoning behind them
11. Describe your learning processes
12. Present an overall conclusion

## Abstract

Cocktails have seen a resurgence in popularity over the past decade that continues into this year and many businesses are seeking to enter or expand on this market (Mitchell, 2018). As a result of analysis of changes in consumer preferences, even chains like Pizza Hut are offering cocktails (Wall, 2015). At the same time, businesses are using analytics to tweak their menus and drink recipes (Carr, 2012).

By analyzing cocktail recipes online, we can find insights into what types of cocktails have grown in popularity over time, as well as what ingredients should be stocked in bars today to make the most cocktail recipes. I will being using Python, BeautifulSoup and Selenium to scrape cocktail recipe websites as well as Pandas and a variety of data manipulation/visualization tools to normalize data, make predictions and derive insights.

## Assumptions and Questions

If one were to open a bar, you would want to have a good selection of popular cocktails for guests. The basic cocktails most people might be familiar with are the Old Fashioned, the Whiskey Sour and the Margarita as those have been the most popular in bars in the last several years (Millington, 2018). Given a limited budget for purchasing supplies and finite menu space, we would want to know what types of spirits would make the most drinks and what flavor profiles to target. I might like spirit-forward cocktails, but others might prefer sweet cocktails. Using these assumptions will give us a starting point to find and analyze data about cocktails from the Internet.

## Tools Used

For this exercise, we used Python 3 in Jupyter for interactive computing, with the Pandas data manipulation and analysis libraries, as well as the Plotly statistical data visualization library to generate interactive charts and figures. For data retrieval and parsing we will use Selenium and Beautifulsoup. For storage and retrieval of data sets we will use SQLite.

## Cocktail Recipe Website

The dataset we will be using for this project is the liquor.com cocktail recipe list. The site contains roughly 2,000 unique cocktails that have been added by users from 2009 to 2019. Recipes can be searched and accessed at https://www.liquor.com/recipe-search/