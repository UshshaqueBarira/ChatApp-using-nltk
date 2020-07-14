# ChatApp-using-nltk

The chat app is made using Python as language on Pycharm software.
The packages imported are:
Numpy
Pandas
Sklearn
nltk
re

The functions used is:
pos_tag
lemmatized
cosine_similarity
CountVectorizer
pairwise_distances
and many more...

The steps used for building the chatbot was:
1.importing packages
2.loading data set
3.remove the stopwords
4.Normalised the text using a created function--> lower case,remove special characters, tokenize,put in tags,wordlemmatizer(), put in ofr loop to add in the array of lematized words.
5.apply the same on the dataset creating a new column in the datatset.
6.use countvectorizer()
7.transform it to an array
8.get feature names and run it into a variable

The algorithm used to get the nearest answer to the question asked is done through cosine_similarity.
This would get us the best of the responses based on the cosine values we have computed of the response from database.

Happy Implementing!
