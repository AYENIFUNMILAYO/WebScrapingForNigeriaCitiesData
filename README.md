# WebScrapingForNigeriaCitiesData
Web scrapping of Nigeria cities data from the falling rain site

## FallingRain Web Scraper
This repository contains a Python-based web scraping tool designed to extract geographical and population data from FallingRain, a website that provides detailed location-based information such as latitude, longitude, and elevation. The scraper fetches data from region-specific URLs, scrapes tables with specific data, and saves the results into a CSV file for further analysis.

## Features
Scrapes geographic and population data, including:
Name
What (description of the place)
Region
Country
Latitude & Longitude
Elevation (in feet)
Estimated population
Handles dynamic navigation through pages and regions.
Saves scraped data in CSV format (scraped_table_data.csv).
## Dependencies
This script requires the following Python libraries:

requests: For making HTTP requests.
pandas: For handling tabular data and saving it to CSV.
BeautifulSoup4: For parsing HTML and XML documents.
lxml: For HTML parsing.

## Nigeria Cities Data Scraper
This project contains a Python script that scrapes city data from the FallingRain website, specifically for Nigeria. The data includes information such as city names, geographical coordinates, population estimates, and elevation.

## Description
The script in this repository scrapes data on Nigerian cities from the FallingRain website using Python libraries such as requests, BeautifulSoup, and pandas. The data collected from the website is stored in a CSV file, making it easier to analyze and use for various projects.

## Features:
Scrapes only Nigerian city data.
Collects city names, latitude, longitude, population estimates, and elevation details.
Saves the data into a CSV file (scraped_table_data.csv).
##Key Libraries Used:
requests: For making HTTP requests to retrieve web pages.
BeautifulSoup: For parsing HTML content.
pandas: For manipulating and saving the scraped data.
How It Works
The script starts by fetching the base URL for Nigeria on the FallingRain website.
It extracts the relevant links that contain alphabetical listings of Nigerian cities.
The script navigates through these links, specifically scraping data from the third alphabetical listing page.
If the table is not found on the third page, it continues by scraping from the fourth page.
Finally, the collected data is saved in a CSV file (scraped_table_data.csv) in the current directory.
Installation
To use this script, follow the steps below:

Clone this repository to your local machine:

bash
Copy code
git clone https://github.com/yourusername/nigeria-cities-scraper.git
Install the necessary Python dependencies:

The scraped data will be saved in a CSV file named scraped_table_data.csv.

##License
This project is licensed under the MIT License.
