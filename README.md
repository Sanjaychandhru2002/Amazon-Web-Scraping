# Amazon Web Scraping

This project involves scraping data from Amazon using Python libraries like BeautifulSoup and requests. It extracts information about a specific product, such as the title, brand, and date, and saves it to a CSV file for further analysis.

## Setup

To run the script, ensure you have the required Python libraries installed:

```bash
pip install beautifulsoup4
pip install requests
```

Additionally, you may need to install the lxml parser:

```bash
pip install lxml
```

## Usage

1. Update the `URL` variable with the Amazon product URL you want to scrape.
2. Run the Python script `amazon_web_scraping.py`.
3. The script will extract the product information and save it to a CSV file named `AmazonWebScraper Dataset.csv`.

## Automation

To automate the scraping process, you can use the provided `check_brand()` function along with a scheduler tool like `cron` (on Unix-based systems) or Task Scheduler (on Windows). This will enable periodic scraping of the Amazon product data at defined intervals.

## Note

Ensure compliance with Amazon's terms of service and robots.txt guidelines when scraping data from their website.
