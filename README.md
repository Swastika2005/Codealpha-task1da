🕸️ Web Scraping Books Data from BooksToScrape.com

This project scrapes book details such as title, price, availability, and rating from the Books to Scrape website and saves it into a CSV file for further analysis.

Features

✅ Scrapes multiple pages (50 pages, 1000+ books)

✅ Extracts book title, price, availability, and rating

✅ Saves data into a CSV file for easy analysis

✅ Handles HTTP errors gracefully

Installation

Make sure you have Python installed (3.8+) and then install the required libraries:

pip install requests beautifulsoup4

Usage

Run the Python script:

python book_scraper.py


The script will:

Scrape all book pages (50 pages total)

Extract Title, Price, Availability, and Rating

Save the data into booksc.csv

Sample output CSV columns:

Title	Price	Availability	Rating
A Light in the Attic	£51.77	In stock	Three
Tipping the Velvet	£53.74	In stock	One
Notes

Make sure you have a stable internet connection while running the scraper.

You can adjust the number of pages by changing the range(1, 51) in the script.
