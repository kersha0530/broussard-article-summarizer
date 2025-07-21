# Final Project: Mental Health Article Summarizer

**Course**: Web Mining & Applied NLP (44-620)  
**Student**: Kersha Broussard  
**Project**: Custom Article Summarizer using NLP and Web Scraping  
**Article Analyzed**: [US News - Mental Health](https://health.usnews.com/conditions/mental-health)

## 🧠 Project Overview
This project uses Python, BeautifulSoup, spaCy, and spaCyTextBlob to mine a health-related article for:
- Most common words and ideas
- Sentiment (polarity) of the content
- Visualization of sentence relevance scores
- A generated summary using both token and lemma importance

## 💻 Technologies Used
- Requests & BeautifulSoup for web scraping
- spaCy & spaCyTextBlob for NLP and sentiment analysis
- Matplotlib for visualizations
- Jupyter Notebook in a virtual environment

## 🎯 Project Goals
- Extract article HTML and convert to plain text
- Perform polarity sentiment analysis
- Find top 5 frequent tokens and lemmas
- Score each sentence using these
- Visualize score distributions with histograms
- Build a concise summary using cutoff thresholds

## ✅ Key Results
- Generated a summary that captured the essence of the article
- Found the most relevant content using word and idea frequency
- Determined overall sentiment and compared summary sentiment to the original

## 📸 Screenshots
*(Insert notebook screenshots here showing outputs from Q2–Q13)*

## 🧠 Reflections
I gained hands-on experience combining web scraping and NLP to generate structured insights from unstructured text. It was rewarding to see how sentiment and frequency analytics can highlight core ideas and tone from lengthy content.

## 🔗 Links
- [GitHub Repo](<https://github.com/kersha0530/broussard-article-summarizer/tree/main>)
- [Notebook File](<INSERT NOTEBOOK LINK>)

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
