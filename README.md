 Project Overview
This project performs Sentiment Analysis on Twitter data using NLP techniques to classify public opinion as Positive, Negative, or Neutral. The analysis provides actionable insights for marketing and social media strategy.

📂 Dataset
DetailInfoSourceSentiment140 — Twitter DatasetPlatformKaggleTotal Records1.6 Million tweetsSample Used50,000 tweetsLabelsPositive / Negative

🛠️ Tools & Libraries
LibraryPurposepandasData loading and manipulationreText cleaning with regexnltk (VADER)Sentiment scoring and classificationmatplotlibData visualizationseabornStatistical chartswordcloudWord frequency visualization

🔄 Project Workflow
1. Load Dataset → 2. Set Column Names → 3. Sample 50K rows
       ↓
4. Text Cleaning (remove @mentions, URLs, special chars)
       ↓
5. VADER Sentiment Analysis (compound score)
       ↓
6. Visualizations (6 charts + WordCloud)
       ↓
7. Insights & Conclusions

📊 Results
SentimentCountPercentage
🟢 Positive23,81647.6%
⚪ Neutral14,09928.2%
🔴 Negative12,08524.2%

📈 Visualizations

Pie Chart — Sentiment distribution overview
Bar Chart — Sentiment counts comparison
Histogram — Compound score distribution with thresholds
Grouped Bar — Original labels vs VADER predictions
Line Chart — Average compound score by sentiment
Boxplot — Score spread per sentiment category
WordCloud — Top words for Positive, Negative, Neutral tweets


💡 Key Insights

47.6% of tweets are Positive — Twitter users generally express positive emotions
Negative tweets are dominated by words like hate, miss, ill, tired, cant
Positive tweets feature words like love, good, great, well, happy
Neutral tweets mostly discuss daily life — work, today, time, going
VADER compound scores show clear separation between positive and negative classes
