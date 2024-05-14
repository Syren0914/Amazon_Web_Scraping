# Amazon Product Scraper

This Python script is designed to scrape product details from Amazon.com using Playwright and Selectolax libraries. It reads ASINs (Amazon Standard Identification Numbers) from a CSV file named `products.csv`, visits each product page on Amazon, and extracts the product title and price.

## Setup

### 1. Installation

- Install Python (if not already installed).
- Install the required Python packages by running: 



### 2. WebDriver Installation

- The script uses Playwright, which automatically manages the WebDriver. You don't need to install or manage WebDriver manually.

## Usage

### 1. CSV File:

- Create a CSV file named `products.csv`.
- Add ASINs of the products you want to scrape. One ASIN per line.

### 2. Running the Script:

- Run the script `amazon_scraper.py`:


### 3. Output:

- The script will visit each product page, extract the title and price, and print the details using the `rich` library.
- You can customize the output or save it to a file as needed.

## Code Structure

- **`amazon_scraper.py`**: Python script to scrape Amazon product details.
- **`products.csv`**: CSV file containing ASINs of the products to scrape.

## Dependencies

- **playwright**: A Python library for automating web browsers.
- **selectolax**: A fast HTML parser library with CSS selectors.
- **rich**: A Python library for rich text and beautiful formatting in the terminal.

## Disclaimer

- **Ethical Use**: Ensure to use this script responsibly and follow Amazon's terms of service. Automated scraping of websites might be against the terms of service of some websites. Make sure your use case aligns with Amazon's policies.

- **Rate Limiting**: Amazon might detect and block excessive scraping. You may need to implement delays between requests or use proxies to avoid being blocked.

- **Data Accuracy**: The accuracy of the scraped data depends on the structure of Amazon's website. Any changes to the website's structure might require adjustments to the code.

