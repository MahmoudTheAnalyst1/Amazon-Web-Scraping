# Amazon Products Web Scraping

## Project Overview

This project collects product data from Amazon Egypt search results using Python and web scraping techniques.

The project extracts product information from multiple search result pages and saves the collected data into a CSV file for further analysis.

## Tools & Technologies

* Python
* Requests
* BeautifulSoup
* CSV
* Pandas

## Data Collected

The following information was extracted:

* Product Title
* Rating
* Price
* Product Image
* Page Number

## Project Workflow

1. Send HTTP requests to Amazon Egypt using `Requests`.
2. Parse the HTML content using `BeautifulSoup`.
3. Identify product cards from the search results.
4. Extract product information.
5. Store the data in a Python list using `data.append()`.
6. Export the collected data to a CSV file.
7. The CSV file can then be used for data validation and analysis.

## Output

The final dataset is saved as:

`amazon_products.csv`

## Project Status

Web scraping and data collection are completed.

The next step is to validate and analyze the collected data.
