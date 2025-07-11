# 📚 Audible Book Scraper (Selenium-Based)

This Python automation script scrapes book data from [Audible.com](https://www.audible.com) — including **titles**, **authors**, and **lengths** — and saves the results to a structured CSV file. Built using Selenium WebDriver in headless mode for performance and reliability.

---

## ✅ Key Features

- Extracts key book details from Audible’s search results
- Supports multi-page navigation automatically
- Outputs clean CSV with title, author(s), and duration
- Built to run headlessly for smooth automation
- Easily customizable for other Audible sections or filters

---

## 💡 How It Works

1. Launches a headless Chrome browser
2. Loads Audible’s search results page
3. Iterates through all available pages
4. Scrapes data from each audiobook listing:
   - Title
   - Author(s)
   - Length (duration)
5. Stores everything in a local `Books.csv` file

---

## 🌐 Geographic Compatibility

Audible serves different regional domains (like `.in`, `.co.uk`, etc.), each with unique page structures.

> This script is specifically designed for the **U.S. version** of Audible (`https://www.audible.com`).  
> To ensure it functions as intended:

### ✅ Recommended:
- Use a **VPN set to the United States**
- Make sure you're on `https://www.audible.com/search` (not `audible.in` or any local redirect)

Running it without this setup may result in missing or incorrect data due to regional layout changes.

---

## 🚀 Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/swayamworks/audible-book-scraper.git
   cd audible-book-scraper
#   a u d i b l e - b o o k - s c r a p e r  
 