# Source2vec

This repository contains source code embeddings for various programming languages.

Source code files are preprocessed using standard tokenization (it could not be ideal solution for source code), this is work in progress. Also we are working on enhancing embeddings with ASTs and PDGs.

## Java

Created from 1792 million tokens  
Window (context) size 5  
Minimum number of occurrences 10  
Vocabulary http://dizp.fufygen.eu/embeddings/java/java_vocab.txt.zip  

### Word2vec

TBA

### FastText

TBA

### GloVe

http://dizp.fufygen.eu/embeddings/java/glove/java_glove_vectors.bin.zip  
http://dizp.fufygen.eu/embeddings/java/glove/java_glove_vectors.txt.zip  

## Python

Created from 838 million tokens  
Window (context) size 5  
Minimum number of occurrences 10  
Vocabulary http://dizp.fufygen.eu/embeddings/python/python_vocab.txt.zip  
Sample visualisation (FastText, 128 vector size) ![fasttext vis](images/python_fasttext_128.png)

### Word2vec

http://dizp.fufygen.eu/embeddings/python/word2vec/python_word2vec.zip  

### FastText

http://dizp.fufygen.eu/embeddings/python/fasttext/python_fasttext_model.bin.zip  
http://dizp.fufygen.eu/embeddings/python/fasttext/python_fasttext_model.vec.zip  
http://dizp.fufygen.eu/embeddings/python/fasttext/python_fasttext_model_128.bin.zip (vector size 128)  
http://dizp.fufygen.eu/embeddings/python/fasttext/python_fasttext_model_128.vec.zip (vector size 128)  

### GloVe

http://dizp.fufygen.eu/embeddings/python/glove/python_glove_vectors.bin.zip  
http://dizp.fufygen.eu/embeddings/python/glove/python_glove_vectors.txt.zip  

## C

Created from 6589 million tokens  
Window (context) size 7  
Minimum number of occurrences 20  
Vocabulary http://dizp.fufygen.eu/embeddings/c/c_vocab.txt.zip  

### Word2vec

TBA

### FastText

http://dizp.fufygen.eu/embeddings/c/fasttext/c_fasttext_model.bin.zip  
http://dizp.fufygen.eu/embeddings/c/fasttext/c_fasttext_model.vec.zip  

### GloVe

http://dizp.fufygen.eu/embeddings/c/glove/c_glove_vectors.bin.zip  
http://dizp.fufygen.eu/embeddings/c/glove/c_glove_vectors.txt.zip  

...if you need another languages or different params feel free to open issue

## Common parameters

Vector size 64  
Word2vec vectors are created using skipgram method  
FastText vectors are created using 2 to 6 character ngrams  

## How to load embeddings (python)

see [load_embeddings.ipynb](load_embeddings.ipynb)

## Dimensionality reduction and visualisation of embeddings

see [visualise_embeddings.ipynb](visualise_embeddings.ipynb)


Paper comming out soon.