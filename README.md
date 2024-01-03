# Largest Companies in the USA by Revenue - Web Scraping Project
## Overview:

This Python project leverages web scraping techniques to extract information from the Wikipedia page listing the largest companies in the United States by revenue. The BeautifulSoup library is employed to parse the HTML content, and the Requests library facilitates HTTP requests to retrieve the web page data.

To view the complete Webscrapping Project, click [here](https://github.com/Ani-Gomes3003/WebscrappingProjects/blob/main/Web%20Scrapping%20website%20.ipynb)

## Technologies Used:

**Python:** Core programming language for the project.
**BeautifulSoup:** Python library for pulling data out of HTML and XML files.
**Requests:** Simplifies the process of sending HTTP requests.

## Key Steps:

**Fetching HTML Content:**
The script uses the requests library to make an HTTP request to the Wikipedia page and fetch the HTML content.

**Parsing HTML:**
BeautifulSoup is then employed to create a parse tree from the HTML content, allowing easy navigation and extraction of relevant data.

**Table Extraction:**
The script identifies the target table (index 1) on the Wikipedia page, where information about the largest U.S. companies is presented.

**Header Extraction:**
The headers of the selected table are extracted, providing the column names for the data to be collected.

**Data Extraction and DataFrame Creation:**
The script iterates through the rows of the table, extracting the data from each cell. The extracted data is then organized into a Pandas DataFrame, establishing a structured format for further analysis.

## Future Enhancements:

**Implement data cleaning and validation steps for robust data extraction.**
**Enhance error handling to account for changes in the HTML structure of the Wikipedia page.**
