# Reddit-Vaccine-Data
Analysing COVID-19 Vaccine related user comments on Reddit Platform using Doc2Vec generated clusters and Topic Modelling Methods

# <h2> This is part of an ongoing project
  
  
Introduction
The COVID-19 pandemic led to one of the biggest races in the Bio-Technology industry to create effective and safe vaccine immunization solutions to win the war against a deadly disease that has to date taken appx. 6 Million lives and crashed economies all over the globe. 

Motivation
However, the speed of development, corporatization, and other alleged ill-effects of quite a few of these vaccines has led to many being hesitant to take the vaccine along with those who are already against the concept of inoculations. These factors coupled with the requirement of booster doses, government and private intervention in form of vaccine mandates, ineffective distribution and vaccine mismanagement are speculated to have driven this negative sentiment further.
Social Media in the age of the internet plays a huge role in both spreading awareness and misinformation regarding these vaccines. Reddit is one of the most used Social Media platforms that allows free and open discussions regarding the pandemic.
To probe into COVID-19 vaccine discussions on Reddit we perform a sentiment analysis and topic clustering approach on these discussions.

Methodologies
•	Extracting Data from Reddit using the Reddit API.
•	Performing a VADER lexicon sentiment analysis to understand the overall sentiment.
•	Using Doc2Vec models to generate word-embeddings and further clustering them to generate useful clusters.
•	Applying LDA Topic Modelling to detect latent topics.
