# Python-Topic-Modeling-and-visualization-using-pyLDAvis
Purpose: To perform text analytics including creating word clouds, perform sentiment analysis and topic modeling

Description: The data for this assignment has been collected from psychcentral.com. This website offers an online forum for posting questions and answers related to mental health. Please visit https://forums.psychcentral.com for more information. Our objective is to perform text analytics to discover useful information related to mental health.

Steps performed:

Loading the necessary libraries
Reading the csv file using pandas
Text Pre-processing steps: 3a. Removing digits and converting text to lowercase 3b. Removing Punctuations using re 3c. Removing Stopwords using spacy 3d. Lemmatization and Stemming
Top frequency words (unigrams and Bigrams) and their dataframe and graphical represenations
Word clouds
Latent Dirichlet Algorithm to get the topics and top terms in those topics  (Hyperparameters: n(Topics), n(Terms), n(iterations))
