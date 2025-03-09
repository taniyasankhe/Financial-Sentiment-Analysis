# 📊 Financial Sentiment Analysis

## 🚀 Project Overview
This project implements a **hybrid sentiment analysis tool** that combines **VADER (lexicon-based)** and **BERT (deep learning-based)** models to analyze financial news and real-time tweets for market sentiment. The goal is to provide insights into stock market trends based on sentiment analysis.

---
## 📌 Features

✅ **Financial News Sentiment Analysis** – Processes financial news headlines for sentiment classification.  
✅ **Hybrid Sentiment Analysis** – Uses **VADER for quick analysis** and **BERT for deep contextual understanding**.  
✅ **Visualizations** – Generates histograms and sentiment distribution plots.  
✅ **Real-Time Twitter Sentiment Analysis** – Fetches and analyzes live tweets using Twitter API v2.  
✅ **Rate Limit Handling** – Implements **exponential backoff** to handle API restrictions smoothly.  
✅ **Performance Evaluation** – Includes **classification reports** for model accuracy assessment.  

---
## 🛠️ Technologies Used

- **Python** 🐍
- **NLP:** VADER & BERT (Hugging Face Transformers)
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Twitter API:** Tweepy (API v2)

---
## 📂 How to Use

### 1️⃣ Install Dependencies
```bash
pip install vaderSentiment transformers torch scikit-learn pandas numpy matplotlib seaborn tweepy
```

### 2️⃣ Run Sentiment Analysis on Financial News
```python
python financial_sentiment_analysis.py
```

### 3️⃣ Fetch and Analyze Twitter Sentiment (Update Credentials in the Script)
```python
analyze_tweets("Tesla stock", count=10)
```

---
## 📊 Example Output
```bash
Tweet: "Tesla stock is looking strong today! 🚀"
VADER Score: 0.92
BERT Sentiment: Positive (Confidence: 0.98)
```

---
## 🔹 Future Enhancements

🔹 **Stock Price Correlation** – Relate sentiment trends with stock market fluctuations.  
🔹 **Dashboard (Streamlit)** – Create an interactive web app for live analysis.  
🔹 **Custom BERT Model Fine-Tuning** – Improve accuracy for financial texts.  

---
## 💡 Contributing
If you have ideas to improve this project, feel free to open a pull request or submit an issue. Contributions are welcome! 🚀

---
## 📝 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

