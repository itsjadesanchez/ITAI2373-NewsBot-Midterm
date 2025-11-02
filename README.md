# ITAI2373-NewsBot-Midterm
Overview

NewsBot Intelligence System is a complete end-to-end NLP pipeline, which is meant to automatically read, categorize, and derive actionable information out of news articles. Various methods of NLP are used in this project, which includes advanced text processing, TF-IDF feature extraction, part-of-speech tagging, dependency parsing, sentiment and emotion analysis, multi-class classification (SVM and Naive Bayes) and named entity recognition (NER). The system ensures trend analysis, business intelligence and media monitoring through structured representations and visualizations. This repository is a portfolio worthy example of real-world uses of NLP in practice.

Features

Text Preprocessing: Lowercasing, tokenization, stopword removal, lemmatization and normalization of raw text.

TF-IDF Feature Extraction: Text (cleaned) to numeric vectors to classify and analyse.

POS Tagging and Dependency Parsing: Grammatical extraction and syntax.

Sentiment Analysis: Assessment of article level sentiment and emotional tone utilizing VADER.

Multi-Class Classification: Politics, Sports, Technology, Business, Entertainment and Health classification of news articles with SVM and Naive Bayes.

Named Entity Recognition (NER): The recognition of a named entity such as PERSON, ORG, GPE, DATE and MONEY.

Data Visualization: Visualization of category distribution and other NLP insights.

Dataset

The BBC News Classification Dataset (approximately 2,000 articles) that we used in this project has six categories:

Business

Entertainment

Politics

Sports

Technology

Health

The data was cleaned and made available in tokenized text, which can be used in NLP modeling. The dataset has been sampled to satisfy the computing limit of Google Colab by removing missing values and sampling.

Installation

Clone the repository:

git clone YourUsername/ITAI2373-NewsBot-Midterm.git.

Go to the project folder:

cd ITAI2373-NewsBot-Midterm

Install necessary libraries of Python:

pip install requirements.txt

Obtain a copy of the dataset CSV file (newsbot_dataset.csv) and put it in the project folder.

Usage

Open the Jupyter Notebook (NewsBot_Midterm_Notebook.ipynb) at Google Colab or Jupyter Lab.

Process one cell at a time to run the complete pipeline, including preprocessing, classification and NER.

Categories distributions and outputs of NLP analysis will be presented in visualizations.

Example Outputs

Category Classification: Articles are automatically categorized based on their content.

Sentiment Scores: Compound sentiment scores are either positive, neutral, or negative.

Named Entities: The extracted entities are key people, organizations, places and dates.

Visualizations: Bar charts are used to describe the number of articles per category and the distribution of sentiments.

Team Contributions

Member A: TF-IDF implementation, visualization and preprocessing of the datasets.

Member B: POS tagging, dependency parsing and syntactic feature extraction.

Member C: classification model and sentiment analysis.

Member D: Multi-class assessment, NER, evaluation, and documentation.

Future Enhancements

And use transformer based models (e.g., BERT) to achieve higher classification accuracy.

Enhance the data to offer live news feeds.

Apply topic modeling and trend detection to get deeper information.

Improve the computational efficiency with large datasets.

License

The project is an educational one, and no commercial licensing can be used in this case.
