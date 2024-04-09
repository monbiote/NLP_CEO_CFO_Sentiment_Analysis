# Natural Language Processing: Sentiment Analysis of Earnings Call Transcripts

### How Do CEOs and CFOs Modify Their Sentiment in Times of Economic Crisis?
#### By Mathieu Breier, Edward Monbiot, Amber Walker
##### Date: March 18th, 2024

#### Abstract
This paper explores the dynamic shifts in sentiment expressed by CEOs and CFOs during economic crises and assesses the accuracy of their communications in such times. We analyzed earnings call transcripts from four distinct companies, applying sentiment analysis to texts from both CEOs and CFOs. The sentiment scores obtained were then regressed against share price data to gauge the correlation with actual company performance. Our findings reveal that although CEOs generally exhibit higher sentiment scores, this disparity lessens during periods of economic crisis. Significantly, the analysis indicates that CFOs consistently offer a more accurate reflection of company performance in relation to share prices. This study acknowledges its own limitations and suggests directions for future research, aiming to deepen the understanding of executive sentiment in corporate communications during economic downturns.

### Section 1) Web Scraping Earnings Calls Transcripts 
### Section 2) Sentiment Analysis of Earnings Calls

---

## Web Scraping Earnings Calls Transcripts
### Efficient and Scalable Data Scraping from fool.com
#### Section Overview

This section focuses on implementing web scraping techniques to gather large datasets efficiently. It provides a scalable framework for data collection, essential for data-driven decision-making processes.
---

#### Description
- **Objective:** Focused on scraping financial data related to cruises and airlines.
- **Scraping Breakdown:**
   - **Cruises Scraping:** Data scraping from: Royal Caribbean and Norwegian Cruise Line.
   - **Airlines Scraping:** Data scraping from: Delta Air Lines and Southwest Airlines.

### Libraries Used:
- NumPy
- Pandas
- Selenium
- BeautifulSoup

### Highlights:
- Implementation of a flexible and scalable data collection pipeline using Selenium.
- Scraped data stored in Pandas dataframes
- Verification steps to ensure all quaterly earnings transcripts have been completely scraped
- Company transcripts transformed to CSV files for Data Analysis
---

# Sentiment Analysis of Earnings Calls
- **Objective:** Analyzing sentiment in company earnings call transcripts during the COVID-19 economic crises.

### Contents:
   - **Preprocessing:** Prepare earning calls transcripts for analysis (lowercasing, stemming, removal of HTML tags, stopwords and extra spaces etc.)
   - **Sentiment Analysis:** Create pipeline to do sentiment analysis, primary tool: Loughran McDonald Sentiment Analyzer.
   - **Sentiment Over Time:** Analyzing CEO & CFO sentiment scores during COVID-19 crisis and plot against share price and trading volumes.
   - **Regression Analysis:** OLS regression to explore relationships between CEO and CFO sentiment and market data.

### Libraries Used:
- Yahoo Finance
- Seaborn
- BeautifulSoup
- Selenium
- Scikit-learn

### Highlights:
- Creation of a preprocessing pipeline for earnings call transcripts.
- Aggregated word cloud generation using TF-IDF.
- Detailed sentiment analysis with a focus on economic downturns.
- Visualisation of CEO and CFO sentiment trends over time.
- Regression analysis to quantify the relationship between sentiment and stock performance.

---

## Getting Started
To get started with these projects, clone this repository and ensure you have the required dependencies installed. Detailed instructions for setup and execution are provided in each project's respective notebook.

## Acknowledgements
Special thanks to all contributors and mentors who have provided guidance and support throughout these projects.

