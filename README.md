# Analysing Data – Assignments Repository

This repository contains all assignments for the course **Analysing Data** in the Master's programme **Digital Humanities**. 

<ins>Assignment 1</ins>

In assignment 1, I have applied Natural Language Processing (NLP) techniques using NLTK and spaCy to analyze a collection of literary texts. The project included sentence splitting, tokenization, word frequency analysis, and visualization of the most common words. It also compares the effects of *Porter* and *Lancaster* stemming on word statistics and examines differences between the two stemmers.
Additionally, the assignment analyzes three translations of [Tom Sawyer](https://nl.wikipedia.org/wiki/Tom_Sawyer_(personage)) by performing Part-of-Speech (POS) tagging with spaCy to compare linguistic patterns across languages. In the second part, Named Entity Recognition (NER) is applied and evaluated by comparing automatic annotations with a small manually annotated dataset. The results are implemented and presented in a Jupyter Notebook. 

<ins>Assignment 2</ins>

In this assignment, I have investigated whether specific storytelling features can predict the overall story strength score in posts from the *ChangeMyView* dataset. Using the data, simple linear regression was performed to examine the relationship between the __story_score__ (dependent variable) and several narrative features: __Agency__, __Event Sequencing__, __World Building__, __Curiosity__, __Surprise__, and __Suspense__ (independent variables).

The analysis includes visualizing the data with scatterplots, fitting regression lines, calculating R² scores, analyzing residual plots, and testing the normality of residuals using the Shapiro–Wilk test. The results are interpreted in a short report discussing which features best predict story strength and what other factors might influence the score. 

Technologies Used
- Python
- Jupyter Notebook
- pandas
- matplotlib
- scikit-learn
- scipy
- NLTK
- spaCy

Author
Master's Programme Digital Humanities
Course: Analysing Data

