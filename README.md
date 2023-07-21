# Web-Scraping-Amazon-Product-Information
This project is a Python web scraping script that gathers product information from Amazon's search results. The script scrapes product details from multiple pages and writes the data to a CSV file for further analysis and usage.

Purpose
The purpose of this project is to demonstrate web scraping using Python  to extract product details from Amazon's search results pages. The data includes product URLs, names, prices, ratings, number of reviews, descriptions, product descriptions, ASIN, and manufacturer.

Libraries Used
requests: Used to send HTTP requests to the Amazon website and retrieve the HTML content of the search result pages and product pages.
BeautifulSoup: Used to parse the HTML content and extract specific product information from the search results and product pages.
csv: Used to export the scraped product data to a CSV file.
Project Structure
The project consists of a Python script named amazon_product_scraping.py, which contains the web scraping code. Additionally, there's a CSV file named amazon_product_info.csv where the scraped data is stored.

Usage
Install the required libraries by running pip install requests beautifulsoup4 in your terminal or command prompt.
Run the amazon_product_scraping.py script using Python. The script will scrape product information from 20 pages of Amazon's search results for the keyword "bags" in this example. The data will be saved to the amazon_product_info.csv file in the same directory.
Scrape Data
The script collects the following information for each product:

Product URL: The URL of the product on Amazon's website.
Product Name: The name or title of the product.
Product Price: The price of the product on Amazon.
Rating: The average rating of the product (if available).
Number of Reviews: The total number of reviews for the product (if available).
Description: A short description of the product from the search result page (if available).
Product Description: A more detailed product description from the product page (if available).
ASIN: The unique Amazon Standard Identification Number for the product.
Manufacturer: The manufacturer or brand of the product.
Note
Web scraping should be done responsibly and in compliance with the website's terms of service. It's essential to respect the website's policies and not overload the server with too many requests. Always check and review the legality and ethics of web scraping for any website you intend to scrape.

Disclaimer: This project is for educational and illustrative purposes only. The developers do not endorse any unauthorized scraping of data or any violation of website policies.
