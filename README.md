# Module-11-Challenge

Part 1:

# Mars News Web Scraper

## Overview

This Jupyter notebook scrapes article titles and preview text from the Mars News website using BeautifulSoup and Splinter. 

## Contents

The notebook contains the following:

- Imports of BeautifulSoup and Splinter libraries
- Initialization of a Splinter browser
- Navigation to the Mars News website 
- Parsing of the page content with BeautifulSoup
- Extraction of all article text elements 
- Looping through text elements to get titles and preview text
- Storage of results in a list of dictionaries with `title` and `preview` keys
- Printing of final list to confirm success

## Usage

To use this web scraper:

1. Ensure Splinter, BeautifulSoup, and Jupyter notebooks are installed
2. Open the notebook in Jupyter
3. Run the cells in order to scrape the site and output the results

The final output is a list containing dictionaries with article titles and preview text ready for further analysis.

Part 2:

# Mars Weather Data Scraper 

## Overview

This Jupyter notebook scrapes temperature and pressure data from a table on the Mars Weather Data site using BeautifulSoup. It then analyzes and visualizes the data using Pandas.

## Contents

The notebook contains the following key parts:

- Imports of BeautifulSoup, Pandas, Matplotlib libraries
- Initialization of a Splinter browser  
- Navigation to Mars weather data site
- Scraping of data table using BeautifulSoup 
- Storage of data in Pandas DataFrame
- Data cleanup by changing dtypes 
- Data analysis to answer questions on Mars months, number of measurements, temperature and pressure trends over time
- Visualizations including line plots and bar charts
- Export of final DataFrame to CSV

## Usage 

To use this notebook:  

1. Ensure the required libraries are installed 
2. Open the Jupyter notebook
3. Run each cell in order to scrape, prepare, analyze, visualize, and export the Mars weather data

The output is a cleaned CSV file containing the weather data ready for further analysis and visualization.
