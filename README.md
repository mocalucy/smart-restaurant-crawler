# 🗽 Smart Restaurant Crawler

This project is a web crawler designed to extract, process, and analyze restaurant data. It gathers location, name, and other metadata for restaurants and supports further analysis using natural language processing and geolocation mapping. This project is a full pipeline built with **Python**, combining **web crawling**, **natural language processing (NLP)**, **SQL-style data handling**, and **Google Map API integration**.

## 📂 Project Structure

```
smart-restaurant-crawler/
├── coordinates/           # Location data restaurants
├── model/                 # Model-related files (NLP or prediction)
├── rating/                # Scripts for handling restaurant ratings
├── src/                   # Core crawler logic and pipeline
├── buisness.json          # Output file storing extracted restaurant data
├── buisness.py            # Processes raw business data
├── inference.py           # Performs predictions or classifications
├── main.py                # Main crawler entry point
├── utils.py               # Helper functions
```

## 🌟 Features

- Crawls restaurant listings
- Extracts relevant metadata (name, address, category, etc.)
- Includes utilities for:
  - Geolocation mapping
  - Rating classification
  - Keyword or tag extraction
 
## 🌐 Demo (Frontend)

A simple frontend prototype is available to visualize the result:

👉 [smart-restaurant.github.io](https://smart-restaurant.github.io/#/)

Click **"ENG"** and **"Nearby"** to browse the extracted restaurant data.

> ⚠️ The frontend is not actively maintained and may not function perfectly — it's only intended as a demo to preview the data crawling and prediction results.

## 📝 Notes

- You may ignore unrelated files/folders if you're only using the restaurant crawler
- The project is built modularly to allow extension to other cities or domains
