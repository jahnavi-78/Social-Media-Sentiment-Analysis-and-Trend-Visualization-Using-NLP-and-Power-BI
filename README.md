# Social Media Sentiment Analysis and Trend Visualization

## 📌 Overview
This project analyzes the sentiment of social media posts using Natural Language Processing (NLP) and visualizes the trends using Power BI. It compares traditional rule-based sentiment analysis with modern Transformer-based models.

## 🛠️ Tech Stack
- **Language:** Python
- **NLP Models:** VADER (NLTK), Twitter-RoBERTa (Hugging Face / PyTorch)
- **Data Processing & Viz:** Pandas, Matplotlib, Seaborn, WordCloud
- **Dashboarding:** Power BI

## ⚙️ Features
1. **Text Preprocessing:** Cleans raw social media data by removing URLs, hashtags, mentions, and punctuation.
2. **Sentiment Classification:** Uses two distinct approaches to classify text as `Positive`, `Negative`, or `Neutral`:
   - `code_vader.py`: Lexicon and rule-based sentiment analysis.
   - `code_roberta.py`: Pre-trained Deep Learning model optimized for social media text.
3. **Word Clouds:** Automatically generates word clouds for each sentiment category to highlight frequent terms.
4. **Power BI Dashboard:** An interactive `.pbix` dashboard that visualizes sentiment distributions and trends over time.

## 🚀 How to Run
1. Clone the repository.
2. Install the required libraries: 
   ```bash
   pip install pandas matplotlib seaborn wordcloud nltk transformers torch scipy
   ```
3. Run the analysis scripts: 
   ```bash
   python code_roberta.py
   ```
   or 
   ```bash
   python code_vader.py
   ```
4. Open the `BI Social Media Project.pbix` file in Power BI Desktop to view the dashboard.
