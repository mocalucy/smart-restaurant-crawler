# 🗽 Smart Restaurant Crawler (NYC Focus)

This project is a web crawler designed to extract, process, and analyze restaurant data — specifically focused on **New York City**. It gathers location, name, and other metadata for restaurants and supports further analysis using natural language processing and geolocation mapping.

## 📂 Project Structure

```
smart-restaurant-crawler/
├── coordinates/           # Location data for NYC restaurants
├── model/                 # Model-related files (NLP or prediction)
├── rating/                # Scripts for handling restaurant ratings
├── src/                   # Core crawler logic and pipeline
├── buisness.json          # Output file storing extracted restaurant data
├── buisness.py            # Processes raw business data
├── inference.py           # Performs predictions or classifications
├── main.py                # Main crawler entry point
├── utils.py               # Helper functions
```

## 🚀 How to Use

### 1. Clone the repository

```bash
git clone https://github.com/mocalucy/smart-restaurant-crawler.git
cd smart-restaurant-crawler
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

If `requirements.txt` is not provided, install common packages manually:

```bash
pip install requests beautifulsoup4 pandas spacy
```

### 3. Run the crawler (NYC example)

```bash
python main.py --city "New York"
```

The results will be saved to `buisness.json`.

## 🌟 Features

- Crawls restaurant listings in NYC
- Extracts relevant metadata (name, address, category, etc.)
- Includes utilities for:
  - Geolocation mapping
  - Rating classification
  - Keyword or tag extraction

## 📝 Notes

- You may ignore unrelated files/folders if you're only using the restaurant crawler
- The project is built modularly to allow extension to other cities or domains
