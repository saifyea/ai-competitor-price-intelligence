# 📊 AI Competitor Price Intelligence Tool

An AI-powered business intelligence tool that combines **web scraping**, **LLM-based market analysis**, and **competitor price monitoring** to help businesses make smarter pricing decisions.

## ✨ Features

- 🔍 Scrape product data from websites
- 📚 Extract product names, prices, and ratings
- 🤖 Analyze market data using Anthropic Claude AI
- 📈 Compare competitor prices
- 💡 Generate AI-powered pricing recommendations
- 📄 Export analysis reports in JSON format

---

## 🛠 Tech Stack

- Python
- BeautifulSoup4
- Requests
- Anthropic Claude API
- Python-dotenv
- JSON

---

## 🏗️ System Architecture

```text
             Competitor Website
                     │
                     ▼
            🔍 Web Scraper
                     │
                     ▼
        📊 Structured Product Data
                     │
                     ▼
      🤖 AI Market Analyzer (Claude)
                     │
                     ▼
     📈 Pricing Intelligence Engine
                     │
                     ▼
   💡 Business Recommendation
                     │
                     ▼
      📄 JSON Analysis Report
```
## ⚙️ Workflow

1. Scrape competitor product information.
2. Extract product names, prices, and ratings.
3. Send structured data to Anthropic Claude.
4. Generate market insights using AI.
5. Compare competitor pricing.
6. Recommend pricing strategies.
7. Save the final analysis as a JSON report.

---

## 📂 Project Structure

```text
ai-competitor-price-intelligence/
│
├── scraper.py                    # Scrapes product data
├── analyzer.py                   # AI market analysis
├── kids_toy_price_monitor.py     # Competitor pricing analysis
├── README.md
├── requirements.txt
├── .env.example
├── .gitignore
│
├── assets/                       # Screenshots
├── data/                         # Sample data
└── reports/                      # AI analysis reports
```

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/saifyea/ai-competitor-price-intelligence.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Create a `.env` file:

```text
ANTHROPIC_API_KEY=your_api_key_here
```

Run the project:

```bash
python kids_toy_price_monitor.py
```
---

## 💼 Business Use Case

Businesses need to continuously monitor competitor pricing to stay competitive.

This AI-powered tool helps businesses:

- 🔍 Track competitor product prices
- 📊 Understand market positioning
- 💡 Identify pricing opportunities
- 🤖 Generate AI-based pricing recommendations
- 📄 Create automated analysis reports

### Example Scenario:

A small e-commerce business wants to know:

> "Am I pricing my products correctly compared to competitors?"

This tool analyzes competitor prices and provides actionable recommendations.

---

## 📊 Example Output

### Competitor Price Analysis

```
Product: Flash Cards

Your Price: 250 BDT

Competitor A: 280 BDT
Competitor B: 230 BDT

AI Recommendation:

Keep current price.
Your pricing is competitive.
Consider highlighting value instead of reducing price.
```

### AI Generated Insights:

- Identified overpriced products
- Found competitive pricing opportunities
- Suggested balanced pricing strategy
