# Automatized Clustering of Texts
The idea was to develop an automatic (not human inserted) way to classify texts coming from a group of press articles in the subject of Ethic AI.
So, the corpus was treated (stopwords erased, tokenized and lemmatized) and the texts were vectorized using the trained model for the french language present in the SpaCy library. Then, the matrix of distances calculated was saved as a pickle object (so that we didn't have to calculate it everytime). After this, the clustering was made with the scipy dendogram functions.

Each step of the treated corpus is present as zip files. The entirety of the code is in the python notebook 'clustering automatisé' and the final dendogram is the png file called 'dendogram python'.

OBS.: We did some work with R too, but I didn't add it here because the results weren't of much importance as this one.
