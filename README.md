Flight Review Insights

I analyzed airline customer reviews to see what people liked and disliked, grouped customers by how satisfied they were, and built models to predict whether someone would recommend the airline. I also used Gemini to read through negative reviews and pull out the main complaints along with some suggested fixes.

What's inside
Data cleaning and text preprocessing on airline review data
Sentiment scoring using TextBlob
Customer segmentation using KMeans clustering
Recommendation prediction using Logistic Regression and XGBoost
LLM-powered complaint theme extraction using Gemini
How to run
Open Airline_Review_Analysis.ipynb in Google Colab
Add your own Gemini API key as a Colab Secret named GEMINI_API_KEY to run the LLM summarization section
Run all cells in order
Requirements

pandas, numpy, scikit-learn, xgboost, textblob, google-generativeai
