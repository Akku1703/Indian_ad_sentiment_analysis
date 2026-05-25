# 🇮🇳 Indian Digital Advertising — Sentiment Analysis
**MBA DS/AI Project | IIT Mandi | 2025**

## Problem Statement
Despite ₹650B+ in annual digital ad spend, Indian users are 
increasingly frustrated with ads on streaming platforms. 
This project quantifies that frustration using NLP.

## Key Findings
- 58.6% of ad-related reviews are Negative
- "Paid but still ads" is the #1 complaint (1,547 reviews)
- SonyLIV has the worst ad sentiment (-0.308)
- MX Player is the only platform with positive sentiment
- Digital ad spend forecast: ₹945B by 2030

## Data Sources
- Primary: Google Play Store reviews (7,623 reviews, 8 platforms)
- Secondary: FICCI-EY Media & Entertainment Reports 2005–2024

## Tools & Technologies
- Python 3.11, Pandas, NumPy
- VADER Sentiment Analysis
- Scikit-learn (Linear Regression)
- Matplotlib, Seaborn
- google-play-scraper

## Project Structure
    indian_ad_sentiment_analysis/
    ├── data/           raw scraped reviews
    ├── notebooks/      01_sentiment_analysis.ipynb
    ├── outputs/        all charts
    └── requirements.txt

## How to Run
    conda create -n adsentiment python=3.11
    conda activate adsentiment
    pip install -r requirements.txt
    jupyter notebook