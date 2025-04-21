# Overview
This repo contains the following Programming Historian lessons:
- [Sentiment Analysis for Exploratory Data Analysis](https://programminghistorian.org/en/lessons/sentiment-analysis)
- [Analyzing Multilingual French and Russian Text using NLTK, spaCy, and Stanza](https://programminghistorian.org/en/lessons/analyzing-multilingual-text-nltk-spacy-stanza)

*Third Programming Historian lesson, "Counting Word Frequencies with Python" is in another repo, linked [here](https://github.com/Erynn-Gutierrez/Word-Frequencies).*

# Lesson Details

### Lesson #1
#### [Sentiment Analysis for Exploratory Data Analysis](https://programminghistorian.org/en/lessons/sentiment-analysis), [analysis.ipnyb](https://github.com/Erynn-Gutierrez/programming-historian-lessons/blob/main/analysis.ipynb)
This lesson introduces sentiment analysis as a tool for exploring large textual datasets, particularly emails; but this can be applied to any historical text. The lesson is framed around the Enron email corpus, guiding users through formulating research questions, employing Python and the Natural Language Toolkit (NLTK) — specifically the VADER sentiment analyzer — to calculate and interpret sentiment scores. 

In approaching the lesson, I followed a hands-on, step-by-step process: installing Python and NLTK, preparing the Enron dataset, and writing Python scripts to analyze sentiment. The lesson encourages iterative experimentation—adjusting methods and parameters to suit my research questions—while also highlighting the importance of skepticism and critical thinking when interpreting computational outputs in historical research contexts. I ran into a bug considering this lesson hasn't been updated for a couple of years, and referred to Github repos and Stack Overflow to get the punkt package running.

### Lesson #2
#### [Analyzing Multilingual French and Russian Text using NLTK, spaCy, and Stanza](https://programminghistorian.org/en/lessons/analyzing-multilingual-text-nltk-spacy-stanza), [multilingual-analysis](https://github.com/Erynn-Gutierrez/programming-historian-lessons/blob/main/multilingual-analysis.ipynb)

This lesson addresses the challenges of computational text analysis for non-English and multilingual texts, using an excerpt from Tolstoy’s *War and Peace* (which contains both French and Russian) as a case study. The lesson introduces three key preprocessing tasks: tokenization, part-of-speech tagging, and lemmatization. It shows how to perform these using three major Python NLP libraries: NLTK, spaCy, and Stanza. It also covers automatic language detection within mixed-language texts and discusses the strengths and limitations of each tool when working beyond English.

Approaching this lesson, I followed it step-by-step: installing the necessary Python libraries, loading and preparing the multilingual text, and then applying each library to process and analyze the data. The lesson also emphasizes experimentation, encouraging me to compare how each tool handles French and Russian, and to consider the unique challenges of multilingual analysis, like language-specific tokenization and the need for appropriate models over others.
