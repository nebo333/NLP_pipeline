# NLP pipeline

Various jupyter nbs that preprocess different text inputs, vectorize and
prepare the text for different machine learning models. And various supervised
amnd unsupervised models to execute on the data.

** These scripts borrow heavily from Applied Text Analysis with Python
By Benjamin Bengfort, Rebecca Bilbro and Tony Ojeda **

## Precprocessing scripts

Takes both text and PDF docs previously dowloaded and creates a corpous reader, 
and leverages spacy to  id sentences, tokenize text, remove stop words and creates
lists of lists of preprocessed text. Finally, it pickles the files so they can be
read from disk.

Additionally, data is then vectorized in various ways in preparation for use in the
different ML models.

## Modelling scripts

Takes preprocessed data and creates a pipeline of the variouos class obects, selects
various models and trains and fits the models, generating various performance 
metrics.