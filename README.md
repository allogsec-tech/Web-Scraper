# Web-Scraper
A Web-Scraper which uses Selenium automation and Scrapy framework in python3 for scraping data from various websites.

REQUIREMENTS:-

1. PYTHON 3.6
2. Scrapy
3. Selenium
4. MySQL

EXECUTION:

1. Get the database schema and stores table data from the database folder inside /web-scraper/spiders/
2. Enter the area and pincode in store_locations table.
3. Enter the SKUs in item_sku_codes table.
4. Run the main_program.py file

OUTPUT:

1. CSV files are obtained inside the csv_files folder.
2. Scrape sessions are maintained inside scrape_sessions table.
2. Scraped-Data is populated inside the scrape_reports table.
3. An email is sent to the the intended recipients as specified in report_recipients table.

