# Website Scraping of Top Companies in the United States by Revenue

## Project Overview
This project involves scraping data from a website listing the top companies in the United States by revenue and organizing the data into a structured format for analysis. The main tools used are Python, BeautifulSoup, requests, and pandas.

## Tools and Technologies
- **Python:** Programming language used for scripting.
- **BeautifulSoup:** Python library for parsing HTML and extracting data.
- **requests:** Python library for sending HTTP requests to access web pages.
- **pandas:** Python library for data manipulation and analysis.

## Project Details
- **Objective:** To scrape and organize data on the top companies in the United States for further analysis.
- **Data Source:** [https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue]
- **Data Points:** Company name, industry, revenue, number of employees, etc.

## Implementation
1. **Sending HTTP Requests:** Used `requests.get()` to retrieve HTML content from the website.
2. **Parsing HTML:** Employed `BeautifulSoup` to parse the HTML and locate the relevant data.
3. **Extracting Data:** Extracted data points such as company name, industry, revenue, and number of employees.
4. **Creating DataFrame:** Organized the extracted data into a pandas DataFrame for analysis and storage.

## Results
- Successfully scraped and structured data from over 100 company profiles.
- The data is ready for further analysis, such as identifying trends and insights.

## Repository
- [GitHub Repository](https://github.com/a-wahid123/web-scrapping-project123)

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/a-wahid123/web-scrapping-project123
