# WebScraping-Challenge
My Module 11 Web Scraping Challenge Repo.


## What is included

This project is comprised of two Jupyter Notebooks:

part_1_mars_news scrapes titles and preview text from Mars news articles.

part_2_mars_news scrapes and analyses weather data from a tables


## Part One

The part one Jupyter Notebook does the following things:

        Uses automated browsing to visit the Mars News site
        Creates a Beautiful Soup object and extracts text elements
        Takes that object to extract titles and preview text of the news articles
        Stores each title-preview pair in a Python dictionary with two keys: title and preview
        Stores those dictionaries in a Python list
        Prints the list to the notebook


## Part Two

The second Jupyter Notebook has two parts, scraping and analysis

# Scraping

The scraping part of the notebook does the following:

    Uses automated browsing to visit the Mars Temperature Data Site
    Creates a Beautiful Soup object to scrape the HTML table
    Assembles the data into a Pandas DataFrame
    Casts the data into appropriate data types (datetime, int, float)
    Export the DataFrame to a CSV File

# Analysis

After scraping the data and creating the Dataframe, I answered the following questions:

    How many months exist on Mars?
    How many Martian (and not Earth) days worth of data exist in the scraped dataset?
    What are the coldest and the warmest months on Mars (at the location of Curiosity)?
    Plot the average monthly temperature as a bar chart.
    Which months have the lowest and the highest atmospheric pressure on Mars?
    Find the average daily atmospheric pressure by month and plot as a bar chart.
    About how many terrestrial (Earth) days exist in a Martian year?


