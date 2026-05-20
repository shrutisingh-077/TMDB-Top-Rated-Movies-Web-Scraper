# TMDB-Top-Rated-Movies-Web-Scraper
A Python-based web scraping project that extracts top-rated movie data from TMDB using BeautifulSoup and Requests. The project collects movie details such as title, release year, ratings, runtime, genres, descriptions, and links, then cleans and exports the dataset into CSV/Excel format for data analysis and visualization
## Overview
This project is a Python-based web scraping application developed to extract top-rated movie data from TMDB (The Movie Database) using BeautifulSoup and Requests libraries. The scraper collects structured information such as movie titles, release year, ratings, runtime, genres, descriptions, and movie links from multiple pages of TMDB.
# Features
Scraped 100+ top-rated movies from TMDB
Extracted multiple movie attributes:
Movie Name
Release Year
Rating
Runtime
Genres
Description
Movie URL
Removed duplicate movie records using Python sets
Implemented pagination for multi-page scraping
Converted runtime into analysis-ready numeric format
Exported cleaned dataset to CSV and Excel files
Used custom headers to avoid request blocking
# Technologies Used
Python
BeautifulSoup
Requests
Pandas
Regular Expressions (Regex)
Jupyter Notebook
# Project Workflow
Sent HTTP requests to TMDB pages using Requests
Parsed HTML content using BeautifulSoup
Extracted movie links dynamically
Visited each movie page individually
Scraped detailed movie information
Cleaned and transformed scraped data
Stored data in structured DataFrame
Exported final dataset into CSV/Excel format
# Key Learnings
Real-world web scraping techniques
Handling dynamic website structures
HTML tag inspection and parsing
Duplicate data handling
Data cleaning and preprocessing
Working with structured datasets using Pandas
Exporting datasets for analytics projects
# Sample Output Columns
| Column Name     |
| --------------- |
| Movie Name      |
| Year            |
| Rating          |
| Runtime         |
| Runtime_Minutes |
| Genres          |
| Description     |
| Movie Link      |
