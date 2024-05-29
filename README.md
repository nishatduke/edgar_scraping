# Historical Sentiment Analysis of SEC Filings
# README STILL IN CONSTRUTION, JUST A TEMPLATE FOR NOW :)
## Overview
This project aims to analyze the sentiment of SEC filings for public companies and correlate it with their stock performance over subsequent days. By leveraging the EDGAR database, the tool extracts historical filings, evaluates sentiment using various models starting with LLAMA, and predicts stock price movements 1, 7, and 30 days post-filing.

## Features
- **Historical Sentiment Analysis**: Analyze the sentiment from past SEC filings and visualize trends over time.
- **Stock Performance Correlation**: Correlate sentiment scores with stock price movements to gauge the impact of investor sentiments.
- **Real-time Sentiment Updates**: Get the latest sentiment analysis from the most recent SEC filings.
- **Interactive Web Interface**: Users can enter a stock ticker to view both historical sentiment and stock performance data.

## Technology Stack
- **Data Retrieval**: Python, Selenium for scraping SEC's EDGAR database.
- **Backend**: Django for API development.
- **Frontend**: React.js for interactive UI.
- **Database**: MySQL to store historical data and sentiment scores.
- **ML Models**: Starting with LLAMA for sentiment analysis, with plans to test and integrate more models.

## Getting Started
### Prerequisites
- Python 3.8+
- Node.js 14+
- MySQL TBD

### Installation
Clone the repository and install the dependencies.
```bash
git clone https://github.com/nishatduke/sec-sentiment-analysis.git
cd sec-sentiment-analysis
# Install Python dependencies
pip install -r requirements.txt
# Install Node.js dependencies
cd frontend
npm install
