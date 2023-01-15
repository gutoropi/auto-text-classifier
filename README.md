# Automatized Clustering of Texts
The idea was to develop an automatic (not human inserted) way to classify texts coming from a group of press articles in the subject of Ethic AI.
So, the corpus was treated (stopwords erased, tokenized and lemmatized) and the texts were vectorized using the trained model for the french language present in the SpaCy library. Then, the matrix of distances calculated was saved as a pickle object (so that we didn't have to calculate it everytime). After this, the clustering was made with the scipy dendogram functions.
