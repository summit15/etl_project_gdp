# etl_project_gdp
# 🌍 Global GDP Extractor - IMF Data Automation

## 📌 Project Overview

This project is designed for an international firm aiming to expand globally. As a Junior Data Engineer, I was tasked with developing an automated data pipeline to extract and process the list of **all countries sorted by their Gross Domestic Product (GDP)** in **billion USD**, as published by the **International Monetary Fund (IMF)**.

The IMF updates its GDP figures **twice a year**, and this script allows for **automated extraction, processing, and formatting** of this data, enabling timely insights for data-driven expansion strategies.

---

## 🚀 Features

- ✅ Automatically scrapes the latest GDP data from IMF sources
- ✅ Sorts countries by GDP in descending order
- ✅ Converts GDP values to **billion USD**, rounded to **2 decimal places**
- ✅ Saves the output in a clean and structured CSV/JSON format
- ✅ Designed to run biannually as IMF data is updated

---

## 🧰 Tech Stack

- **Language:** Python 3.x  
- **Libraries Used:**
  - `requests` – To fetch webpage content
  - `BeautifulSoup` – For HTML parsing
  - `pandas` – For data manipulation and export
  - `schedule` / `cron` – For automation (optional)


