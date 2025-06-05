# scraping_train_route
# 🚆 Indian Train Route Scraper Project

This project contains two Python scripts to scrape data about long-distance trains in India from [IndiaRailInfo](https://indiarailinfo.com).

## 📁 Versions

### ✅ 1. BeautifulSoup Version

- Located in: `bs4_version/`
- Uses `requests` and `BeautifulSoup` to scrape static HTML content.
- Suitable for simple scraping needs.
- Limitation: Cannot load additional pages dynamically.

### ✅ 2. Selenium Version

- Located in: `selenium_version/`
- Uses `Selenium WebDriver` to interact with the browser.
- Can click on the "Next" button to load all dynamic content.
- Best for full data extraction.

---

## 📦 Dependencies

Each version includes its own `README.md` with setup instructions.

- `bs4_version/README.md`
- `selenium_version/README.md`

---

## 📄 Output

Each script generates a CSV file with train route data including:

- Train No, Name, Type, Zone, From, To, Duration, Halts, Days, Classes, Distance, Speed, Return Train, etc.

---

## 📬 Contributing

Feel free to fork, raise issues, or submit pull requests.

---
