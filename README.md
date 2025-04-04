🛍️ Amazon Review Sentiment Analysis
This project analyzes Amazon product reviews using natural language processing (NLP) techniques to classify sentiments (Positive, Neutral, Negative) and uncover insights into customer feedback. It combines TextBlob and VADER for polarity scoring, Wilson Lower Bound for review ranking, and interactive data visualizations using Plotly and Seaborn.

🔍 Features
📊 Sentiment classification using VADER and TextBlob
📉 Wilson Lower Bound score for statistically reliable review sorting
☁️ WordClouds for each sentiment category
🧼 Review text preprocessing using regex
📈 Interactive visualizations (ratings, sentiment distribution)
🔎 Class-level summary analysis

🧰 Tech Stack
Python 🐍
NLTK & TextBlob
VADER Sentiment Analyzer
Pandas, NumPy
Matplotlib, Seaborn
Plotly, Cufflinks
WordCloud

📂 Dataset
Used a real-world Amazon product reviews dataset with columns such as:
*reviewText
*overall (rating)
*wilson_lower_bound
*helpful, summary, etc.

🚀 How to Run
Clone the repo
Install dependencies (pip install -r requirements.txt)
Run the Jupyter Notebook
Explore the results interactively
