# Analysing Data – Assignments Repository

This repository contains all assignments for the course **Analysing Data** in the Master's programme **Digital Humanities**. 

### Assignment 1

In assignment 1, I have applied Natural Language Processing (NLP) techniques using NLTK and spaCy to analyze a collection of literary texts. The project included sentence splitting, tokenization, word frequency analysis, and visualization of the most common words. It also compares the effects of *Porter* and *Lancaster* stemming on word statistics and examines differences between the two stemmers.
Additionally, the assignment analyzes three translations of [Tom Sawyer](https://nl.wikipedia.org/wiki/Tom_Sawyer_(personage)) by performing Part-of-Speech (POS) tagging with spaCy to compare linguistic patterns across languages. In the second part, Named Entity Recognition (NER) is applied and evaluated by comparing automatic annotations with a small manually annotated dataset. The results are implemented and presented in a Jupyter Notebook. 

### Assignment 2

In this assignment, I have investigated whether specific storytelling features can predict the overall story strength score in posts from the [ChangeMyView](https://www.reddit.com/r/changemyview/) dataset. Using the data, simple linear regression was performed to examine the relationship between the __story_score__ (dependent variable) and several narrative features: __agency_score__, __event_score__, __world_score__, __curiosity_score__, __surprise_score__, and __suspense_score__ (independent variables).

The analysis includes visualizing the data with scatterplots, fitting regression lines, calculating R² scores, analyzing residual plots, and testing the normality of residuals using the Shapiro–Wilk test. The results and full explenation of the exercise can be found in the __Assignment2.pdf__. The full code can be found in the attached Jupyter Notebook. 

## Technologies Used
- Python
- Jupyter Notebook
- pandas
- matplotlib
- scikit-learn
- scipy
- NLTK
- spaCy

## Author
Lise Marit Feringa <br>
Master's Programme Digital Humanities <br>
Analysing Data <br> 
