# 📈 Extracting and Visualizing Stock Data

## 📌 Description
Extracting essential data from a dataset and displaying it visually is a crucial part of data science, as it enables informed decision-making.  
In this project, stock price data and revenue data are extracted for **Tesla** and **GameStop**, cleaned, and visualized using interactive graphs.

---

## 📚 Table of Contents
1. Define a Function that Makes a Graph 
2. Question 1: Use yfinance to Extract Stock Data  
3. Question 2: Use Web Scraping to Extract Tesla Revenue Data  
4. Question 3: Use yfinance to Extract Stock Data  
5. Question 4: Use Web Scraping to Extract GameStop Revenue Data  
6. Question 5: Plot Tesla Stock Graph  
7. Question 6: Plot GameStop Stock Graph  

---

## 🛠️ Technologies Used
- Python  
- yfinance  
- pandas  
- requests  
- BeautifulSoup (bs4)  
- Plotly  

---

## ⚙️ Installation (For Local Setup)
If you are working locally using Anaconda or any Python environment, install the required libraries using:

```bash
pip install yfinance
pip install bs4
pip install nbformat
pip install --upgrade plotly

📊 Project Workflow
🔹 Step 1: Define Graphing Function

A reusable function make_graph() is defined to plot:

Historical Stock Prices

Historical Revenue

The function accepts:

Stock price DataFrame (Date, Close)

Revenue DataFrame (Date, Revenue)

Stock name (for graph title)

🔹 Step 2: Extract Tesla Stock Data

Stock data is extracted using the yfinance library

Ticker Symbol: TSLA

Full historical data is retrieved using period="max"

🔹 Step 3: Extract Tesla Revenue Data

Revenue data is scraped from an HTML page using requests and BeautifulSoup

Quarterly revenue data is extracted

Data cleaning includes:

Removing $ and commas

Converting data to numeric format

Removing null or invalid entries

🔹 Step 4: Extract GameStop Stock Data

Stock data is extracted using yfinance

Ticker Symbol: GME

Full historical stock price data is collected

🔹 Step 5: Extract GameStop Revenue Data

Revenue data is scraped using BeautifulSoup

Quarterly revenue table is extracted

Data is cleaned and converted to numeric values

🔹 Step 6: Data Visualization

Interactive graphs are created using Plotly

Each dashboard contains:

Top panel: Historical Share Price

Bottom panel: Historical Revenue

Graphs display data up to June 2021

📈 Visualizations Generated

Tesla Stock Price vs Revenue Graph

GameStop Stock Price vs Revenue Graph

Each visualization is interactive and includes a date range slider for better analysis.

🎯 Key Learnings

Extracting financial data using APIs

Web scraping structured data from HTML pages

Data cleaning and preprocessing

Creating interactive dashboards using Plotly

Applying end-to-end data science workflow
