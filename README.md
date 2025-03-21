# Web-Scraping
Web Scraping With Scrapy and MongoDB

This project demonstrates how to build a robust web scraper using Scrapy, a powerful Python framework, combined with MongoDB for storing scraped data. We inspect a target website for CSS selectors, handling pagination aswell. I generated a unique identifier (e.g., by hashing the URL) for each item and use MongoDB's _id field to ensure only unique entries are inserted, by using an upsert operation with update_one(). 

Credit: https://realpython.com/web-scraping-with-scrapy-and-mongodb/
