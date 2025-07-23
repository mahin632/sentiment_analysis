# 📊 Task 3: Sentiment Analysis
This project performs sentiment and emotion analysis on Instagram captions to understand public opinion, detect emotional tone, and extract insights for content strategy, marketing, and product development.

## 📁 Dataset
Source: Instagram Dataset from Kaggle

File: Instagram data.csv

Key Columns:

Caption: Text of the Instagram post

Hashtags, Impressions, Likes, etc. (optional metadata)

## 🧠 Objectives
1. Classify each caption as positive, negative, or neutral.

2. Detect specific emotions (e.g., joy, anger, fear) using lexicon-based NLP.

3. Analyze real-world Instagram data to understand trends.

4. Derive insights to inform marketing and content strategies.

5. Visualize sentiment and emotion distributions.

## 🛠️ Tools & Libraries
| Tool                    | Purpose                         |
| ----------------------- | ------------------------------- |
| `pandas`                | Data handling and preprocessing |
| `TextBlob`              | Sentiment analysis (polarity)   |
| `NRCLex`                | Emotion detection               |
| `matplotlib`, `seaborn` | Visualization                   |
| `WordCloud`             | Word frequency visualization    |

## 📦 Installation
Install dependencies:
```bash
pip install pandas textblob matplotlib seaborn wordcloud nrclex
python -m textblob.download_corpora
```
## 🚀 How to Run
1. Place Instagram data.csv in your working directory.

2. Run the Python script or Jupyter notebook provided.

3. Outputs:

Cleaned captions

Sentiment and emotion labels

Visualizations of results

Exported CSV: instagram_sentiment_emotion_analysis.csv

## 📈 Sample Visualizations
📊 Sentiment distribution (positive, negative, neutral)

🎨 Emotion bar chart (joy, anger, fear, etc.)

☁️ Word cloud of most common terms

## 📌 Applications
🧠 Marketing Strategy: Understand what emotions resonate with your audience.

📢 Content Optimization: Tailor future posts based on sentiment success.

📊 Public Opinion: Detect mood shifts over time or in response to campaigns

## 📤 Output
The results are saved to:
```bash
instagram_sentiment_emotion_analysis.csv
```
