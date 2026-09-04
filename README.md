# Flight Review Insights

Analyzed airline customer reviews to understand sentiment, grouped customers by satisfaction level, and built models to predict whether a customer would recommend the airline. Also used Gemini AI to read negative reviews and summarize the main complaints with suggested fixes.

## What's inside
- Data cleaning and text preprocessing on airline review data
- Sentiment scoring using TextBlob
- Customer segmentation using KMeans clustering
- Recommendation prediction using Logistic Regression and XGBoost
- LLM-powered complaint theme extraction using Gemini

## How to run
1. Open `Airline_Review_Analysis.ipynb` in Google Colab
2. Add your own Gemini API key as a Colab Secret named `GEMINI_API_KEY` to run the LLM summarization section
3. Run all cells in order

## Requirements
pandas, numpy, scikit-learn, xgboost, textblob, google-generativeai
