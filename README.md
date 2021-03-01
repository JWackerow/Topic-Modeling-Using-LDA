# Topic-Modeling-Using-LDA
Topic models are used to identify topics that best describe a set of documents. This notebook used Latent Dirichlet Allocation to try and identify topics in news articles.

* After loading the data, a function is built to preprocesses the text. This step uses spacy to lemmatze and only allow words that have the specified pos tags.
* Use the gensim library to create bigrams/trigrams, the dictionary and corpus in bag of words format.
* Build LDA model and feed the model the corpus and dictionary that was created in the previous step.
* Loop through a range to test which number of topics resulted in the highest coherence score.
* Use pyLDAvis library to visualize the topics and most salient terms.
