# Internshala Internship Scraper

This project scrapes Python internships from [Internshala](https://internshala.com) using **Selenium + BeautifulSoup + Pandas**.

---

## Features
- Scrapes: **Title, Company, Location, Stipend, Duration, Skills, Apply Link**
- Filters out **promoted ads** automatically
- Handles **pagination** (first 10-12 pages)
- Logs scraping progress and errors
- Saves data to **CSV** and **Excel** files

---

## Tech Stack
- Python
- Selenium
- BeautifulSoup
- Pandas

---

## ChromeDriver Setup
1. Download ChromeDriver matching your **Chrome browser version**:  
   [https://chromedriver.chromium.org/downloads](https://chromedriver.chromium.org/downloads)
2. Extract `chromedriver.exe` and place it in this project folder
3. Make sure `chromedriver.exe` is **not pushed to GitHub**  
   > The `.gitignore` file includes `chromedriver.exe` to keep the repo clean and OS-independent

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Internshala_Scraper.git
