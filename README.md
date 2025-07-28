# Final Project: Mental Health Article Summarizer

**Course**: Web Mining & Applied NLP (44-620)  
**Student**: Kersha Broussard  
**Project**: Custom Article Summarizer using NLP and Web Scraping  
**Article Analyzed**: [Mental Health](https://en.wikipedia.org/wiki/Mental_health)

## 🧠 Project Overview
This project focuses on web mining and natural language processing (NLP) techniques and uses Python, BeautifulSoup, spaCy, and spaCyTextBlob to mine/summarize a Wikipedia article on **Mental Health**. The process combines sentiment analysis, token/lemma frequency extraction, and intelligent sentence scoring to produce two versions of a text summary. 
- Most common words and ideas
- Sentiment (polarity) of the content
- Visualization of sentence relevance scores
- A generated summary using both token and lemma importance


## 🛠 Tools & Libraries Used
- `requests`, `pickle` for HTML retrieval and storage
- `BeautifulSoup` for HTML parsing
- `spaCy` for NLP processing (tokenization, lemmatization, POS tagging)
- `TextBlob` for sentiment analysis
- `matplotlib` for histogram visualizations

## 🔍 Project Steps
1. **Web Scraping**: Fetched and saved the HTML from the Wikipedia article.
2. **Sentiment Analysis**: Used `TextBlob` to analyze polarity and subjectivity.
3. **spaCy Token & Lemma Frequency**: Identified the 5 most frequent tokens and lemmas (filtered and lowercased).
4. **Sentence Scoring**: Each sentence was scored by its frequency of interesting tokens/lemmas.
5. **Histograms**: Visualized token- and lemma-based sentence scores.
6. **Summary Generation**: Created two summaries (token-based and lemma-based) using a cutoff score.

## 📊 Summary Stats
- **Original Article Sentence Count**: 387
- **Token Summary Sentence Count**: 53  
  - Polarity Score: `0.00097`
- **Lemma Summary Sentence Count**: 53  
  - Polarity Score: `0.00439`

## 💡 Insights
- Most frequent tokens and lemmas highlighted recurring themes in the article.
- The summaries maintained the original sentence order and retained important information.
- Lemma-based scoring slightly outperformed token-based in terms of polarity.

## 📁 Files Included
- `mental_health_article.pkl` – HTML source
- `article_summarizer.ipynb` – Full notebook with analysis, visualizations, and summaries
- Summary plots: token-based and lemma-based histograms

## 🏁 Skills Demonstrated
- Web scraping
- Sentiment analysis
- spaCy NLP techniques
- Data visualization
- Text summarization with sentence filtering

## 👩🏽‍🎓 Student
Kersha Broussard  
Course: Web Mining & Applied NLP (44-620)


## 🔗 Links
- [GitHub Repo](<https://github.com/kersha0530/broussard-article-summarizer/tree/main>)
- [Notebook File](<https://github.com/kersha0530/broussard-article-summarizer/blob/main/broussard-article-summarizer.ipynb>)

# Final Project: Article Summarizer

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Polarity score printed with an appropriate label: 1 pt
* (Question 2) Number of sentences printed: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Histogram shown with appropriate labelling: 1 pt
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Cutoff score seems appropriate given histograms: 2 pts (1/score)
* (Question 8) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 8) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 9) Polarity score printed with an appropriate label: 1 pt
* (Question 9) Number of sentences printed: 1 pt
* (Question 10) Summary contains a shortened version of the article (less than half the number of sentences): 1 pt
* (Question 10) Summary sentences are in the same order as they appeared in the original article: 1 pt
* (Question 11) Polarity score printed with an appropriate label: 1 pt
* (Question 11) Number of sentences printed: 1 pt
* (Question 12) Thoughtful answer based on reported polarity scores: 1 pt
* (Question 13) Thoughtful answer based on summaries: 1 pt
