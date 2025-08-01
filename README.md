# 🕸️ CPWD eTender Scraper

This Python script scrapes tender information from the [CPWD eTender portal](https://etender.cpwd.gov.in/) using **Selenium WebDriver**. The data is extracted, structured, and exported to a CSV file for further use in data analysis, monitoring, or reporting.

---

## 🚀 Features

- Automates browser interaction to fetch data from a dynamic webpage.
- Extracts fields like:
  - NIT/RFP Number
  - Title of Work
  - Estimated Cost
  - EMD Amount
  - Bid Submission and Opening Dates
- Iterates through all paginated results.
- Outputs data into a clean CSV file: `tenders.csv`.

---

## 📦 Dependencies

Install the following Python packages before running the script:

```bash
pip install requirements
```

## Clone the repo 

``` bash
git clone https://github.com/kanishk-rezol/Web-scrapping
cd cpwd-tender-scraper
```