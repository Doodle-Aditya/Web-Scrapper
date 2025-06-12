# 🕸️ Web Scraping Quotes with BeautifulSoup & Pandas

This project demonstrates how to scrape data from a practice website using Python's `requests`, `BeautifulSoup`, and `pandas` libraries. It collects quotes, author names, and tags from [Quotes to Scrape](http://quotes.toscrape.com), a site designed specifically for learning web scraping.

---

## 📌 Project Objectives

- Learn how to send HTTP requests and parse HTML.
- Extract structured data (quotes, authors, tags) from a webpage.
- Store the data in a `pandas` DataFrame.
- Export the final dataset to a CSV file.

---

## 📂 Dataset Structure

After scraping, the dataset contains the following columns:

| Column Name | Description                      |
|-------------|----------------------------------|
| `name`      | Name of the author               |
| `quote`     | Text of the quote                |
| `category`  | Associated tags/categories       |

---

## 🛠️ Technologies Used

- **Python 3.10+**
- **BeautifulSoup (bs4)**
- **requests**
- **pandas**

---

## 🚀 How to Run

1. Clone this repository or download the `.ipynb` file.
2. Install dependencies (if not already):

```bash
pip install requests beautifulsoup4 pandas
