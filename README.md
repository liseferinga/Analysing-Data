# Analysing Data – Assignments Repository

This repository contains all assignments for the course **Analysing Data** in the Master's programme **Digital Humanities**. 

### Assignment 1

In assignment 1, I have applied Natural Language Processing (NLP) techniques using NLTK and spaCy to analyze a collection of literary texts. The project included sentence splitting, tokenization, word frequency analysis, and visualization of the most common words. It also compares the effects of *Porter* and *Lancaster* stemming on word statistics and examines differences between the two stemmers.
Additionally, the assignment analyzes three translations of [Tom Sawyer](https://nl.wikipedia.org/wiki/Tom_Sawyer_(personage)) by performing Part-of-Speech (POS) tagging with spaCy to compare linguistic patterns across languages. In the second part, Named Entity Recognition (NER) is applied and evaluated by comparing automatic annotations with a small manually annotated dataset. The results are implemented and presented in a Jupyter Notebook. 

### Assignment 2

In this assignment, I have investigated whether specific storytelling features can predict the overall story strength score in posts from the [ChangeMyView](https://www.reddit.com/r/changemyview/) dataset. Using the data, simple linear regression was performed to examine the relationship between the __story_score__ (dependent variable) and several narrative features: __agency_score__, __event_score__, __world_score__, __curiosity_score__, __surprise_score__, and __suspense_score__ (independent variables).

The analysis includes visualizing the data with scatterplots, fitting regression lines, calculating R² scores, analyzing residual plots, and testing the normality of residuals using the Shapiro–Wilk test. The results and full explenation of the exercise can be found in the __Assignment2.pdf__. The full code can be found in __Assignment2.ipynb__. 

## Technologies Used
- Python
- Jupyter Notebook
- pandas
- matplotlib
- scikit-learn
- scipy
- NLTK
- spaCy

### Assignment 3
In this assignment, I investigate two tasks involving __Large Language Models__. First, I have designed a small research proposal exploring whether an LLM’s internal representations of stories are more closely aligned with the book version or the movie adaptation.
The (refined) research question is stated as follows: 

_By using probing tasks on factual, stylistic, and interpretive elements, to what extent does an LLM’s narrative knowledge align more with the book version or the movie adaptation?_

The proposal defines an outline for the process to find an answer to this research question by describing a probing-based methodology. It also discusses limitations, and considers the use of roles of both annotators as legal support. A small exploratory experiment with prompt-based analysis is included at the end.  

In the second part, I implement a prompting pipeline using the Ollama library to classify song lyrics into genres using the provided dataset (__genreLyrics_train.csv__ and __genreLyrics_test.csv__). Both zero-shot and few-shot prompting strategies are tested and evaluated using Precision, Recall, and F1-score. The results are compared across genres and discussed in terms of performance differences and limitations.

The full code for Part 2 can be found in the Jupyter notebook in the folder for Assignment 3. The dataset is included in the data/ folder and must be kept in the same directory structure for the code to run correctly.

## Author
Lise Marit Feringa <br>
Master's Programme Digital Humanities <br>
Analysing Data <br> 
