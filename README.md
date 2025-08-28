# Brand_Sentiment_Dashboard_14 CaseCraft Analytics Project Sprint Project 14

## 👟 Overview  
This project tracks public sentiment across Nike, Adidas, and Puma using synthetic tweet data and NLP techniques. It blends sentiment analysis, time-series tracking, and brand classification to decode consumer emotion and brand perception.

## 🎯 Objective  
To analyze tweet-level sentiment for three sportswear brands, compare emotional tone, and build a classifier to predict brand from tweet text.

## 🐦 Dataset & Features  
- Tweets: 1,500 synthetic entries  
- Brands: Nike, Adidas, Puma  
- Features: timestamp, tweet text, sentiment polarity (TextBlob)  
- Derived: sentiment label (Positive, Neutral, Negative)

## 📊 Visual Explorations  
- Bar chart: Sentiment distribution by brand  
- Line chart: Daily average sentiment polarity  
- Heatmap: Average sentiment per brand  
- WordClouds: Brand-specific emotional vocabulary  
- Confusion matrix: Brand prediction from tweet text

## 🔍 Sentiment Analysis  
- Nike leads in positive sentiment  
- Adidas shows more neutral feedback  
- Puma has slightly higher negative sentiment frequency  
- Sentiment fluctuates daily with brand-specific trends

## 🤖 Brand Classification Model  
- Model: Random Forest Classifier  
- Input: CountVectorizer on tweet text  
- Target: brand  
- Performance:  
  - Precision/Recall/F1-score: **1.00** across all brands  
  - Accuracy: **100%** on synthetic data

## 🧠 Key Insights  
1. **Nike Dominance**: Highest emotional engagement and positivity  
2. **Adidas Stability**: Consistent neutral tone, suggesting brand steadiness  
3. **Puma Challenge**: Slightly more negative sentiment, potential reputation gap  
4. **Text Signals**: WordClouds reveal distinct emotional vocabularies  
5. **Model Utility**: High accuracy in brand prediction supports campaign tracking

## ✅ Final Conclusion  
Sentiment dashboards reveal nuanced brand dynamics across Nike, Adidas, and Puma. Nike leads in emotional resonance, Adidas maintains stability, and Puma may benefit from reputation enhancement. This framework supports automated brand monitoring, perception tracking, and strategic marketing insights.