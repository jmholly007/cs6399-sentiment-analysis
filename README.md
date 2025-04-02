# CS6399 Project – Sentiment Analysis on Student Feedback

## Overview

This project performs sentiment analysis on anonymized student feedback to evaluate course and instructor satisfaction. Using NLP techniques, it classifies student responses to help universities identify patterns and improve instructional quality.

## Project Goals

- Apply NLP to clean and tokenize feedback
- Use VADER for sentiment analysis
- Visualize insights with an interactive Power BI dashboard
- Enable filtering by course, instructor, delivery mode, and sentiment

## Tech Stack

- Python (Jupyter Notebook)
  - pandas, spaCy, nltk, vaderSentiment
- Power BI (for dashboard visualization)
- Data source: synthetically generated `.csv` file

## How to Run the Notebook

1. Clone this repo or download the ZIP
2. Open `notebook/sentiment_analysis.ipynb` in Jupyter
3. Install dependencies: pip install -r requirements.txt

4. Run the notebook cells to:
- Clean feedback
- Tokenize + lemmatize (spaCy)
- Analyze sentiment (VADER)
- Output CSV for Power BI

## Power BI Dashboard

The dashboard includes:
- Sentiment distribution (pie chart)
- Sentiment by course and delivery mode
- Recent student feedback table

You can open the `.pbix` file in Power BI Desktop (free version) to explore.

## Notes

- Database storage (Access/SQLite) was deemed unnecessary and removed from the final pipeline.
- A second dashboard page was proposed but excluded for simplicity, as all key insights were represented in a single-page layout.

## Author

Joshua Holly  
CS6399 – Angelo State University
