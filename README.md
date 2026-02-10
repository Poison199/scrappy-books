# Scrapy Books Scraper with MongoDB

This is a web scraping project built with Scrapy that crawls the Books to Scrape website (http://books.toscrape.com) and stores book data in a MongoDB database.

The scraper extracts:
- Book title
- Book price
- Book URL

It follows pagination to scrape all available pages.

---

## Features

- Scrapes multiple pages using pagination
- Extracts structured data using CSS selectors
- Stores results in MongoDB using a Scrapy item pipeline
- Prevents duplicate entries in the database
- Includes unit tests for spider functionality

---

## Project Structure

