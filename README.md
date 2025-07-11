# 🧾 Go Stock Scraper

A simple and efficient stock data scraper built with Golang and [Colly](https://github.com/gocolly/colly) that fetches real-time stock details such as company name, current price, and percentage change from Yahoo Finance. The scraped data is saved in a CSV file for easy access and analysis.

---

## 🔧 Features

- ✅ Scrapes company name, stock price, and daily change percentage
- ✅ Uses Yahoo Finance as the data source
- ✅ Writes results to `stocks.csv`
- ✅ Handles request errors gracefully

---

## 📦 Technologies Used

- **Go (Golang)** — Core programming language
- **Colly** — Web scraping framework
- **encoding/csv, log, os, fmt** — Go standard packages

---

## 📁 Output

Sample format of `stocks.csv`:

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/go-stock-scraper.git
cd go-stock-scraper
go get github.com/gocolly/colly
go run main.go

## 👨‍💻 Author
#Nachiket Jayant Deshpande

