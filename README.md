# Kimo Store – Laptop Data Scraper

## Project Overview
This project is a Python web scraping script built with Selenium to collect laptop product information from the Kimo Store website.

The scraper navigates through multiple pages in the laptop collection and extracts product details.

## Website
https://kimostore.net/collections/laptops

## Technologies Used
- Python
- Selenium
- XPath
- CSV

## Data Extracted
The scraper collects the following information for each laptop:

- Product Name / Description
- Price
- Rating
- Number of Reviews
- Stock Availability

## Output
The extracted data is saved in a CSV file named `all products.csv`.

## Features
- Scrapes multiple product pages.
- Extracts product information using XPath.
- Handles products with missing ratings or reviews.
- Organizes the extracted data into dictionaries.
- Exports all collected data into a CSV file.

## How to Run

1. Install Python.
2. Install Selenium:

```bash
pip install selenium
```

3. Run the script:

```bash
python kimo_store.py
```

4. The scraped data will be saved in `all products.csv`.

---

**Note:** This project was created for learning and demonstrating Python web scraping skills.
