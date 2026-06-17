## Project Overview

This project collects book information from the Books to Scrape website and stores the extracted data in a structured CSV format for further analysis.

The scraper navigates through all available pages, extracts relevant book details, and compiles the data into a single dataset.

---

## Features

- Scrapes data from all 50 pages of the website
- Extracts information for 1000 books
- Handles website pagination automatically
- Cleans and structures scraped data
- Exports data to CSV format
- Uses Python, BeautifulSoup, and Pandas

---

## Dataset Information

The dataset contains the following fields:

| Column | Description |
|----------|------------|
| Book Title | Name of the book |
| Price | Book price (£) |
| Rating | Book rating (One to Five) |
| Status | Availability status |

### Dataset Summary

- Total Books Scraped: **1000**
- Total Pages Scraped: **50**
- Missing Values: **0**
- Output Format: **CSV**

---

## Technologies Used

- Python
- Requests
- BeautifulSoup4
- Pandas
- Jupyter Notebook

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/books-to-scrape-data-pipeline.git
